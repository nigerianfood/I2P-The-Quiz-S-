# SPM Analysis — This Is BLOND:ISH
**Playlist:** This Is BLOND:ISH (`37i9dQZF1DZ06evO3SHkVW`)
**Playlist Saves:** 9,188
**Tracks Analyzed:** 30
**Tracks Scored:** 7
**Seeds Found, Stream Data Unavailable:** 2 (tracks 19, 27)
**Date:** 2026-06-28

---

## Methodology

**SPM (Saves Per Million)** = Radio Playlist Saves ÷ Seed Track Streams × 1,000,000

For each track, I searched Spotify for its title-only Radio playlist (e.g., "It Starts Now Radio"), verified the seed track via the `image_uri` path (`/radio/track/{trackID}/en`), fetched the radio playlist's save count, and fetched the track's total stream count from kworb's Spotify songs page.

**Key methodology note:** All searches use title-only queries (no artist name appended). Including the artist name can suppress auto-generated radio playlists from appearing in results.

**Scale context:** BLOND:ISH is a deep underground artist. Tracks range from 327K streams (Lovers On The Dancefloor) to 152M streams (Never Walk Alone). SPM values are structurally higher than catalog artists like Coldplay because denominators are orders of magnitude smaller. Scores here should be read within the underground electronic context.

---

## SPM Rankings

| Rank | Track | Artist | SPM | Streams | Radio Saves | Signal Read |
|------|-------|--------|-----|---------|-------------|-------------|
| 1 | It Starts Now | BLOND:ISH | 139 | 5,646,913 | 785 | Strongest discovery signal in set |
| 2 | Lovers On The Dancefloor | BLOND:ISH | 119 | 326,633 | 39 | Extreme ratio on ultra-low stream base |
| 3 | Natural Blues | BLOND:ISH | 51 | 8,543,954 | 439 | Active underground discovery engine |
| 4 | Wizard of Love - Radio Edit | BLOND:ISH | 36 | 31,037,235 | 1,122 | Highest absolute saves in set |
| 5 | Fortnight (feat. Post Malone) - BLOND:ISH Remix | BLOND:ISH | 20 | 42,411,567 | 830 | Cross-fandom streams compress ratio |
| 6 | Self Love | BLOND:ISH | 14 | 13,557,786 | 194 | Moderate catalog engagement |
| 7 | Sorry (with Madonna) - Eran Hersh and Darmon Remix | BLOND:ISH | 11 | 1,285,049 | 14 | Minimal active discovery |

---

## Key Findings

**It Starts Now leads at SPM 139 — by far the strongest discovery signal in the set.** On 5.6M streams, it pulls 785 radio saves: one save per every 7,193 streams. For an underground track, this is an extraordinary listener intent signal. It functions as an active discovery engine pulling listeners deeper into the BLOND:ISH catalog.

**Lovers On The Dancefloor (SPM 119) has an extreme ratio, but the base is very small.** Only 327K lifetime streams and 39 radio saves — both numbers are low in absolute terms. The ratio is striking, but should be read with caution: this is a near-unknown track where a small numerator and small denominator can produce a high quotient. The signal is real but fragile.

**Natural Blues (SPM 51) is the most structurally reliable data point.** 8.5M streams is meaningful scale for a BLOND:ISH original, and 439 saves is a genuine signal. This track — BLOND:ISH's own take on the Moby catalog — has consistent organic discovery activity.

**Wizard of Love - Radio Edit has the most absolute radio saves in the set (1,122) but ranks 4th at SPM 36.** With 31M streams, the denominator compresses the ratio. Still a strong catalog performer by any measure.

**Fortnight BLOND:ISH Remix (SPM 20) has the largest absolute save count among non-Wizard tracks (830), yet ranks 5th.** Its 42.4M streams are largely driven by Taylor Swift fans discovering the remix, not BLOND:ISH discovery-intent listeners — which structurally suppresses the SPM despite healthy raw numbers.

**Sorry (Eran Hersh and Darmon Remix) scores lowest at SPM 11 (14 saves / 1.3M streams).** This remix is catalog filler — generating passive streams without meaningful listener intent.

**Two seeds found with no calculable SPM:** Call My Name (253 radio saves) and Garden Of 3Den - Edit (39 saves) both have verified radio playlists seeded to the correct playlist version, but their stream counts are below kworb's tracking threshold and not visible on the Spotify track page. SPM cannot be calculated without a denominator. The raw save counts suggest Call My Name may have a meaningful signal if confirmed.

---

## Tracks Without Radio Seed Data (21 tracks)

These tracks had no matching Spotify radio playlist in the top 5 results, or the verified seed track ID did not match the playlist version:

| # | Track | Reason |
|---|-------|--------|
| 2 | Never Walk Alone | No seed match in top 5 results |
| 3 | Sete | No seed match in top 5 results |
| 8 | Sorry (with Madonna) | Sorry Radio seeds to original Madonna version, not BLOND:ISH remix |
| 9 | Es un secreto | No seed match in top 5 results |
| 10 | The Cure | "The Cure" band radio results dominate search |
| 11 | Higher - Notre Dame Remix | No seed match in top 5 results |
| 12 | nothin lasts 4ever | No seed match in top 5 results |
| 13 | Different Way - ARTBAT Remix | No seed match in top 5 results |
| 14 | In Da Jungle | No seed match in top 5 results |
| 15 | Remember Me | No seed match in top 5 results |
| 16 | Hold Tight (feat. Darla Jade) - Extended Mix | Extended Mix version does not seed radio |
| 17 | Can't Let You Go | No seed match in top 5 results |
| 18 | Tra Tra | No seed match in top 5 results |
| 20 | No One | "No One" (Alicia Keys) radio results dominate search |
| 21 | Shout It Out | No seed match in top 5 results |
| 22 | Don't Cha | No seed match in top 5 results |
| 23 | Waves (feat. Grace Tither) | No seed match in top 5 results |
| 24 | GOAT | No seed match in top 5 results |
| 25 | Kimbe (feat. Tay Iwar) | No seed match in top 5 results |
| 28 | Voyeur - Jay Shepheard & Martin Dawson Remix | Remix version does not seed radio in top 5 |
| 29 | Heartbreaker | No seed match in top 5 results |

---

## Seeds Found, Stream Data Unavailable (2 tracks)

Radio playlist seeds verified but stream counts below kworb tracking threshold and not visible on Spotify track page — SPM cannot be calculated:

| # | Track | Radio Playlist ID | Radio Saves |
|---|-------|-------------------|-------------|
| 19 | Call My Name | `37i9dQZF1E8NEvv1ittUBL` | 253 |
| 27 | Garden Of 3Den - Edit | `37i9dQZF1E8NeOnpgDk4w0` | 39 |

---

## Raw Data Reference

See `blondish_this_is_spm_analysis.csv` for full worksheet.

**Stream source:** kworb.net Spotify songs page (all-time totals for BLOND:ISH artist ID `6zsJjoCtL1WByG0VsuFWzR`).
**Save counts:** Fetched directly from each radio playlist's Spotify page.
