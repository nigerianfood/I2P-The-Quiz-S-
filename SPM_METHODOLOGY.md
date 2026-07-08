# SPM Analysis — Standard Methodology

**SPM (Saves Per Million)** = Radio Playlist Saves ÷ Seed Track Streams × 1,000,000

This is the standing procedure for every playlist analysis in this repo. No track may be left as "stream data unavailable," and no track may be marked "no seed match" until every radio-recovery step below has been exhausted and documented.

---

## 1. Playlist intake

- Fetch the playlist page (`open.spotify.com/playlist/{id}`) via WebFetch — it is partially server-rendered and exposes name, description, save count, and the full tracklist with track IDs.
- Record: playlist name, ID, save count, and for each track: position, title, artist(s), track ID.

## 2. Radio playlist discovery (in order — stop at first verified hit)

1. **Title-only search** via the Spotify MCP: `"{Track Title} Radio playlist"`. Never append the artist name — artist names suppress auto-generated track radios from results.
2. **Version-qualified retry** for generic or versioned titles: include the full version string exactly as released (e.g. `"Faces Prod. by Roberto Ferrante 2020 Remaster Radio"`). This retrieves radios the plain title misses.
3. **Prior-run recovery**: for refreshes of rolling playlists, reuse radio IDs verified in earlier snapshots (git history) — radio seeds are stable once created. Re-confirm via the description check (step 4b).
4. **Candidate-description sweep** (mandatory before any no-seed verdict): fetch every same-title radio candidate's page and read its description, which always reads `"With {Artist A}, {Artist B}, {Artist C} and more"`.
   - a. If a candidate's description leads with the track's artist → it is that artist's radio.
   - b. **Same-song duplicate-release seeds**: Spotify relinks duplicate releases, so the correct radio may seed a *different release ID of the same song*. Accept it when BOTH the exact versioned title matches AND the description names the artist. Mark `YES_SAME_SONG_DUPLICATE_SEED` in the CSV.
5. **Google site search**: `site:open.spotify.com "{Title} Radio" "{Artist}"` — radio pages are indexed with their descriptions.
6. Only after all of the above: record `NO_DEDICATED_RADIO` with the evidence trail (which candidates were checked and whose radios they turned out to be).

**Seed verification:** the radio's `image_uri` must contain `/radio/track/{trackID}/en` matching the playlist track's ID (or the verified duplicate-release ID per 4b).

## 3. Save counts

- Fetch the radio playlist page via WebFetch and read the header's `"N saves"` line.
- **If the header omits the saves line entirely, the count is 0** — score SPM 0, not N/A. (Confirmed behavior across multiple zero-save radios.)

## 4. Stream counts (in order — every track must resolve)

1. **Spotify track page** (`open.spotify.com/track/{id}`): the play count is server-rendered only when the track appears in the artist's top-10 "Popular Tracks" module.
2. **mystreamcount.com API** for everything else — 100% hit rate to date, down to tracks with ~3K streams:
   ```
   GET  https://www.mystreamcount.com/track/{id}          # collects cookies + XSRF-TOKEN
   POST https://www.mystreamcount.com/api/track/{id}/streams
        headers: X-XSRF-TOKEN: {url-decoded cookie value},
                 Content-Type: application/json, Referer: {track page}
        body: {}
   ```
   Poll every ~8s until `{"status":"ready", "data":{...}}`; use the latest date's `total`. (`scratchpad/fetch_streams.sh` implements this.)
3. **kworb.net** per-artist songs page (`kworb.net/spotify/artist/{artistId}_songs.html`) as tertiary/cross-check, mainly for large catalogs.

## 5. Scoring and reporting

- SPM = saves ÷ streams × 1,000,000, rounded to the nearest integer (`<1` when it rounds to zero with nonzero saves).
- Deliverables per playlist: `{name}_spm_analysis.md` + `{name}_spm_analysis.csv`.
- Rankings table columns (always, ranked by SPM descending): `Rank | Track | Artist | SPM | Streams | Radio Saves | Signal Read`.
- CSV columns: `track_number, track_name, artist, track_id, streams, radio_playlist_id, seed_verified, radio_saves, spm_formula, spm`.
- Flag micro-base ratios (under ~500K streams) as directional; note date mismatches if saves and streams were fetched on different days.

## 6. Interpretation guardrails

- **Dilution check** on refreshes: streams growing much faster than saves (e.g. 5–7x streams vs. flat saves week-over-week) indicates editorial/algorithmic feeding, not organic discovery.
- Billion-stream catalogs compress SPM into single/low-double digits — compare within scale class, and lean on absolute saves for cross-playlist records.
- Zero-save radios on fresh releases are normal: radios are auto-generated before listeners engage.

## Known structural blind spots

- **Common titles**: another artist's hit owns all top search results (e.g. "Fallin'", "True Love"). The candidate sweep proves the negative.
- **Remaster/version ID churn**: legacy playlists may carry release IDs the radios don't seed (e.g. Madonna's 2024 remasters). Check for duplicate-release seeds before giving up.
- Search tools cap at 5 results; the cap is why steps 2–5 of radio discovery exist.
