# SPM Analysis — metropolis
**Playlist:** metropolis (`37i9dQZF1DX8CopunbDxgW`) — "metropolis is your home for the best indie dance"
**Playlist Saves:** 870,270
**Tracks Analyzed:** 30
**Tracks Scored:** 26 (every track with a findable radio — stream counts recovered for all 30)
**Date:** 2026-07-06 (revised same day: all data gaps closed)

---

## Methodology

**SPM (Saves Per Million)** = Radio Playlist Saves ÷ Seed Track Streams × 1,000,000

For each track: title-only radio search (no artist name), seed verification via the `image_uri` path (`/radio/track/{trackID}/en`), save count from the radio playlist's Spotify page, stream count from the track's Spotify page.

**Methodology additions from this analysis (gap-closing techniques, now standard):**
- **Stream counts via mystreamcount.com API** — Spotify track pages only server-render play counts for an artist's top-10 popular tracks. For everything else, `POST https://www.mystreamcount.com/api/track/{id}/streams` (with the page's XSRF token) returns the exact total. 100% hit rate: recovered all 9 missing metropolis counts plus 9 more backfilled into the Beatport and BLOND:ISH analyses.
- **Zero-save radios** — when a radio playlist's header omits the "N saves" line entirely, the count is 0 (confirmed across 4 playlists). These score SPM 0, not N/A.
- **Same-song duplicate-release seeds** — Spotify relinks duplicate releases; a radio can be titled exactly as the playlist track but seed a different release ID of the same song. Verify via the playlist description ("With {artist}, ...") plus exact versioned-title match. This recovered Never Seen You Dance - DJ-Kicks Version (radio description: "With TEED, Amtrac, Dusky").
- **Candidate-description sweep** — for common titles, fetch every same-title radio's description and check the artist list before declaring no-seed. All 5 "Please Don't Go Radio" playlists were individually verified (Mike Posner's, Saison's, KC & The Sunshine Band's, K.W.S.'s, Last Known Species') — none is TEED's.

**Scale context:** Fresh-release indie dance editorial. Stream bases run from 3.4K (Mark Me Up) to 64.5M (Magnetic). Sub-100K-stream ratios are directional; the radios exist within days of release but engagement lags, so four radios sit at literally 0 saves.

---

## SPM Rankings

| Rank | Track | Artist | SPM | Streams | Radio Saves | Signal Read |
|------|-------|--------|-----|---------|-------------|-------------|
| 1 | Magnetic | The Bausa | 129 | 64,469,370 | 8,309 | The playlist's anchor — real scale, real intent |
| 2 | Bedroom Eyes | Poolside, Stevie Appleton | 124 | 129,255 | 16 | Strong early ratio, fresh release |
| 3 | Me and You | Bonobo | 120 | 1,292,691 | 155 | Strong early discovery on new Bonobo |
| 4 | Beautiful Noise In My Head | Soul Wun | 114 | 254,247 | 29 | High ratio, small base |
| 5 | Return To Bhibo | Barry Can't Swim | 112 | 2,780,811 | 311 | Best mid-scale signal in set |
| 6 | Dope Swings | LOVE LANGUAGE, America Rose | 112 | 8,969 | 1 | Micro base — directional only |
| 7 | Girl, Hold Tight (Marsha P) | Crush Club | 102 | 9,828 | 1 | Micro base — directional only |
| 8 | The Wave | Jungle | 83 | 10,021,531 | 836 | Solid signal at the set's second-largest scale |
| 9 | Molly In The Club | Sophia Stel | 77 | 260,936 | 20 | Positive early signal |
| 10 | Your Lovin' | Tonique & Man | 76 | 118,030 | 9 | Positive early signal |
| 11 | Runaways | Midnight Generation | 68 | 73,193 | 5 | Early positive |
| 12 | L.U.C.K.Y - (Live) \| Spotify RADAR | Fcukers | 66 | 30,190 | 2 | Even the live session pulls saves |
| 13 | I'm Summer (Ross from Friends Rework) | Zorro | 66 | 45,617 | 3 | Micro base |
| 14 | Goes Like | From Dave, That Franco | 64 | 31,104 | 2 | Micro base |
| 15 | Round The Block | 49th & Main, Jane | 61 | 444,984 | 27 | Modest positive |
| 16 | Hurt Nobody | Alex Bone | 53 | 75,820 | 4 | Micro base |
| 17 | Every Single Weekend (feat. Jamie xx) | The Avalanches | 52 | 1,517,641 | 79 | Moderate on real base |
| 18 | Lose Myself | The Bausa | 43 | 2,359,241 | 101 | Moderate |
| 19 | espiral | Ela Minus, Nick León | 21 | 46,760 | 1 | Weak |
| 20 | Run (feat. O.MMY) | Marsolo, O.MMY | 20 | 99,250 | 2 | Weak |
| 21 | ROUND & ROUND | Sam Gellaitry | 8 | 122,840 | 1 | Streams outrunning intent |
| 22 | Do It With Ya (ft. 3DDY) | ANOTR, 3DDY | 2 | 407,874 | 1 | Editorial-fed streams, no discovery yet |
| 23 | Scaredy Cat | Alex Bone | 0 | 6,242 | 0 | Radio live, zero saves |
| 24 | Falling Again | 3kelves | 0 | 167,998 | 0 | Radio live, zero saves |
| 25 | Mark Me Up | Machweo | 0 | 3,415 | 0 | Radio live, zero saves |
| 26 | Never Seen You Dance - DJ-Kicks Version | TEED | 0 | 178,235 | 0 | Radio live (duplicate-release seed), zero saves |

---

## Key Findings

**Magnetic (The Bausa) is the playlist's clear anchor: SPM 129 with genuine scale.** 8,309 saves on 64.5M streams — the only track with both a large base and an elevated ratio. The Bausa also lands a second scored entry (Lose Myself, SPM 43).

**Bedroom Eyes (Poolside) jumps to #2 (SPM 124) once its real stream count (129K) is measured** — 16 saves on a days-old release is genuinely fast intent accumulation. Bonobo (120) and Barry Can't Swim (112) confirm the pattern: established underground names whose fans seed radios immediately.

**The bottom of the table is now the most instructive part.** Do It With Ya (ANOTR) has 408K streams but 1 radio save (SPM 2), and ROUND & ROUND (Sam Gellaitry) 123K streams with 1 save (SPM 8) — editorial placement is feeding streams faster than discovery intent is forming. Contrast Dope Swings: 9K streams but already 1 save (SPM 112). Same playlist, opposite dynamics — SPM separates the two within days of release.

**Four radios sit at literally 0 saves** (Scaredy Cat, Falling Again, Mark Me Up, Never Seen You Dance). The radios were auto-generated before any listener saved them — a clean baseline proving save counts are genuine listener actions, not seeded by Spotify.

**Every track's stream count was recovered** — including tracks with as few as 3,415 streams (Mark Me Up) — via the mystreamcount API once Spotify's own pages stopped short. No more "stream data unavailable" in any analysis.

**Only 4 tracks have no findable radio, each exhaustively verified:** all 5 same-title "Please Don't Go" radios were description-checked (none is TEED's), and Real Life / Fallin' / True Love (5K–10K stream micro releases) returned nothing across title-only search, artist-qualified search, and Google site search. These four genuinely have no reachable dedicated radio yet.

---

## Tracks Without a Findable Radio (4 tracks)

Each exhausted: MCP title-only search, artist-qualified search, Google `site:open.spotify.com` search, station-URL probe, and description-verification of every same-title radio candidate:

| # | Track | Streams | Evidence |
|---|-------|---------|----------|
| 3 | Please Don't Go (TEED) | 55,500 | All 5 "Please Don't Go Radio" playlists verified via description — Mike Posner's, Saison's, KC & The Sunshine Band's, K.W.S.'s, Last Known Species' — none is TEED's |
| 18 | Real Life (Fi Sullivan) | 9,839 | Candidate "Real Life Radio" verified: Cookin Soul/J Dilla — not Fi Sullivan |
| 23 | Fallin' (Plaisance, MATTII) | 5,481 | Alicia Keys and others own all title results |
| 29 | True Love (Birthday in Texas) | 10,403 | No radio in search or Google index |

---

## Raw Data Reference

See `metropolis_spm_analysis.csv` for full worksheet.

**Stream sources:** Spotify track pages (artist top-10 tracks); mystreamcount.com API for all others (fetched 2026-07-06).
**Save counts:** Fetched directly from each radio playlist's Spotify page; header omitting the saves line = 0 saves.
