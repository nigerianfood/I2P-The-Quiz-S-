# SPM Analysis — This Is Coldplay
**Playlist:** This Is Coldplay (`37i9dQZF1DXaQm3ZVg9Z2X`)
**Playlist Saves:** 4,190,948
**Tracks Analyzed:** 30
**Tracks Scored:** 9
**Date:** 2026-06-26

---

## Methodology

**SPM (Saves Per Million)** = Radio Playlist Saves ÷ Seed Track Streams × 1,000,000

For each track, I searched Spotify for its title-only Radio playlist (e.g., "Yellow Radio"), verified the seed track via the `image_uri` path (`/radio/track/{trackID}/en`), fetched the radio playlist's save count, and fetched the track's total stream count from kworb's Spotify songs data (validated against live Spotify page counts where available).

**Important context:** All 30 tracks in this playlist are Coldplay catalog recordings, the majority with over 200M lifetime streams. SPM values for billion-stream catalog tracks are structurally lower than for newer or underground releases — because the denominator is orders of magnitude larger. These SPM scores should be read within the catalog context, not compared directly to the electronic/dance playlists in this series.

---

## SPM Rankings

| Rank | Track | Artist | SPM | Streams | Radio Saves | Signal Read |
|------|-------|--------|-----|---------|-------------|-------------|
| 1 | Sparks | Coldplay | 17 | 2,122,202,789 | 36,329 | Strongest relative pull in catalog |
| 2 | Yellow | Coldplay | 14 | 3,828,868,045 | 54,398 | Evergreen discovery at scale |
| 3 | Fix You | Coldplay | 10 | 2,148,940,303 | 21,425 | Active catalog |
| 3 | Clocks | Coldplay | 10 | 1,546,818,318 | 15,143 | Active catalog |
| 5 | The Scientist | Coldplay | 9 | 2,903,985,662 | 25,893 | Active catalog |
| 6 | Everglow | Coldplay | 8 | 382,493,394 | 3,211 | Moderate catalog |
| 6 | Hymn for the Weekend | Coldplay | 8 | 1,970,255,089 | 15,480 | Moderate catalog |
| 8 | Speed of Sound | Coldplay | 7 | 409,879,000 | 2,944 | Passive catalog |
| 9 | Violet Hill | Coldplay | 4 | 235,334,932 | 897 | Minimal active discovery |

---

## Key Findings

**Sparks leads despite not being a "radio hit."** Sparks (2.1B streams) has a proportionally higher radio save rate than Yellow (3.8B streams) or The Scientist (2.9B streams). Listeners actively seek Sparks out from the radio playlist more than any other track in this set, suggesting it functions as a deep-cut discovery entry point rather than a passive skip.

**Yellow's save count is the largest in absolute terms (54,398), yet its SPM is only 14.** At nearly 4 billion streams, Yellow's organic reach dwarfs any radio save number. This illustrates why raw save counts alone mislead — the save-to-stream ratio is what reveals relative listener intent.

**Fix You and Clocks tie at SPM 10.** Both are defining Coldplay songs from the same era with comparable relative discovery rates, suggesting similar listener engagement profiles despite different total stream counts (~2.1B vs ~1.5B).

**The Scientist has the largest absolute save count among non-Yellow tracks (25,893) but ranks 5th.** Its 2.9B streams compress the ratio down to SPM 9 — still active catalog, but the sheer scale of its streaming footprint suppresses the score.

**Violet Hill is the lowest-performing track (SPM 4, 897 saves).** With only 897 radio saves on ~235M streams, it's generating passive playback with very little active listener curiosity. It functions as background rather than discovery.

**Scale context:** The highest SPM here (17) is below the floor of the Beatport Top 100 analysis (lowest scored: 23). This is structurally expected — Coldplay catalog tracks have 10–100× the stream count of typical electronic tracks, compressing SPM across the board.

---

## Tracks Without Radio Seed Data (21 tracks)

These tracks either had no matching Spotify radio playlist in the top 5 results, or the verified seed track ID did not match the playlist version:

| # | Track | Reason |
|---|-------|--------|
| 1 | All My Love | No seed match in top 5 results |
| 3 | Paradise | No seed match in top 5 results |
| 4 | feelslikeimfallinginlove (Single Version) | Zerb x Coldplay remix dominates "feelslikeimfallinginlove Radio" seeding |
| 9 | My Universe | No seed match in top 5 results |
| 10 | GOOD FEELiNGS | No seed match in top 5 results |
| 11 | WE PRAY (Single Version) | No seed match in top 5 results |
| 16 | Every Teardrop Is a Waterfall | Radio playlists exist but none seed to playlist version (`2U8g9wVcUu9wsg6i7sFSv8`) |
| 17 | Orphans | No seed match in top 5 results |
| 18 | Princess of China | No seed match in top 5 results |
| 19 | Higher Power | No seed match in top 5 results |
| 20 | In My Place | No seed match in top 5 results |
| 21 | WE PRAY (TWICE Version) | No seed match in top 5 results |
| 22 | Charlie Brown | No seed match in top 5 results |
| 23 | Biutyful | No seed match in top 5 results |
| 24 | Trouble | No seed match in top 5 results |
| 25 | Viva La Vida (Live from Spotify London) | Radio playlists exist but none seed to this live version |
| 26 | Up&Up | No seed match in top 5 results |
| 27 | Let Somebody Go | No seed match in top 5 results |
| 28 | Something Just Like This | Radio playlists exist but none seed to playlist version (`1dNIEtp7AY3oDAKCGg2XkH`) |
| 29 | Magic | No seed match in top 5 results |
| 30 | O | No seed match in top 5 results |

---

## Raw Data Reference

See `coldplay_this_is_spm_analysis.csv` for full worksheet.

**Stream source:** kworb.net Spotify songs page (all-time totals, validated against live Spotify page counts for Yellow, Sparks, The Scientist).
**Save counts:** Fetched directly from each radio playlist's Spotify page.
