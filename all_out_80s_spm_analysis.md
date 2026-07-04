# SPM Analysis — All Out 80s
**Playlist:** All Out 80s (`37i9dQZF1DX4UtSsGT1Sbe`) — "The biggest songs of the 1980s. Cover: Madonna"
**Playlist Saves:** 11,989,137 (largest playlist analyzed to date)
**Tracks Analyzed:** 30
**Tracks Scored:** 24
**Date:** 2026-07-04

---

## Methodology

**SPM (Saves Per Million)** = Radio Playlist Saves ÷ Seed Track Streams × 1,000,000

For each track: title-only radio search (no artist name), seed verification via the `image_uri` path (`/radio/track/{trackID}/en`), save count from the radio playlist's Spotify page, stream count from the track's Spotify page (kworb per-artist page as fallback where the track page hides the count — Michael Jackson tracks).

**Methodology notes:**
- Every one of the 6 unscored tracks failed for the same reason: **version/remaster ID mismatch**. The playlist carries a specific release ID (e.g. Material Girl 2024 Remaster, Eyes Without A Face Remastered 1999) while the auto-generated radios seed different release IDs of the same song. This is the dominant failure mode for legacy catalog playlists, unlike title conflicts (BLOND:ISH) or too-new releases (Beatport).
- Remaster-qualified radios DO exist and match when the playlist uses the canonical popular version: Sweet Dreams 2005 Remaster, I Want to Know What Love Is 1999 Remaster, and Smooth Operator Single Version all matched exactly.

**Scale context:** These are the biggest catalog records on Spotify — 17 of 24 scored tracks have over 1 billion streams. Denominators this large compress SPM into single and low-double digits; the meaningful signal here is in the absolute save counts and the relative ordering, not the raw SPM values (compare an underground artist like BLOND:ISH where SPM 100+ is achievable on small bases).

---

## SPM Rankings

| Rank | Track | Artist | SPM | Streams | Radio Saves | Signal Read |
|------|-------|--------|-----|---------|-------------|-------------|
| 1 | Smooth Operator (Single Version) | Sade | 43 | 909,750,221 | 38,959 | Strongest per-stream intent in set |
| 2 | Everybody Wants To Rule The World | Tears For Fears | 32 | 2,597,673,466 | 84,186 | All-time absolute saves record |
| 3 | Human Nature | Michael Jackson | 25 | 488,403,360 | 12,242 | Deep-cut discovery on MJ's catalog |
| 4 | Forever Young | Alphaville | 23 | 1,292,517,573 | 29,316 | Strong nostalgia-to-discovery pipeline |
| 5 | Maneater | Daryl Hall & John Oates | 21 | 1,155,750,982 | 24,473 | Elevated intent |
| 6 | Could You Be Loved | Bob Marley & The Wailers | 20 | 1,475,909,153 | 29,543 | Elevated intent |
| 7 | Total Eclipse of the Heart | Bonnie Tyler | 19 | 1,171,825,094 | 22,686 | Solid |
| 8 | Heaven | Bryan Adams | 19 | 1,101,103,270 | 20,902 | Solid |
| 9 | I Want to Know What Love Is | Foreigner | 19 | 1,437,450,639 | 26,987 | Solid |
| 10 | The Winner Takes It All | ABBA | 18 | 904,192,586 | 16,666 | Solid |
| 11 | Down Under | Men At Work | 16 | 1,331,079,019 | 21,476 | Mid |
| 12 | Take on Me | a-ha | 16 | 2,826,679,881 | 44,256 | Massive saves, diluted by 2.8B streams |
| 13 | Africa | TOTO | 15 | 2,661,640,807 | 40,449 | Massive saves, diluted by 2.7B streams |
| 14 | I Wanna Dance with Somebody | Whitney Houston | 14 | 1,711,832,366 | 24,196 | Mid |
| 15 | Sweet Dreams (Are Made of This) | Eurythmics | 14 | 2,000,219,680 | 27,509 | Mid |
| 16 | Summer Of '69 | Bryan Adams | 12 | 1,706,923,272 | 20,932 | Mid |
| 17 | Back In Black | AC/DC | 12 | 2,206,353,367 | 25,522 | Mid |
| 18 | P.Y.T. (Pretty Young Thing) | Michael Jackson | 10 | 680,004,269 | 6,863 | Low |
| 19 | Dancing In the Dark | Bruce Springsteen | 10 | 1,252,258,505 | 12,251 | Low |
| 20 | Uptown Girl | Billy Joel | 8 | 1,435,279,903 | 12,135 | Low |
| 21 | Like a Prayer | Madonna | 8 | 832,418,252 | 6,782 | Low |
| 22 | Born in the U.S.A. | Bruce Springsteen | 8 | 623,905,388 | 4,876 | Low |
| 23 | Billie Jean | Michael Jackson | 5 | 2,995,940,617 | 15,883 | Passive mega-catalog |
| 24 | Thriller | Michael Jackson | 3 | 979,785,733 | 2,860 | Weakest signal in set |

---

## Key Findings

**Everybody Wants To Rule The World set the all-time absolute-saves record: 84,186** — nearly triple the previous record (Jamaican Bam Bam, 31,029) and 2.7x anything else in this playlist. Even against 2.6B streams it ranks 2nd at SPM 32. The Tears For Fears revival (synthwave adjacency, film/TV syncs, TikTok) is generating genuine radio-seeded discovery at a scale no other track measured comes close to.

**Smooth Operator leads on ratio at SPM 43.** 38,959 saves against "only" 910M streams. Sade's catalog has a distinctive quality: it's a discovery destination — listeners who arrive save and dig deeper — rather than passive background nostalgia. This is the quiet-luxury version of the digger effect seen in the Italo Disco analysis.

**Michael Jackson's four entries chart exactly how SPM separates catalog weight from discovery intent.** Human Nature — the connoisseur's deep cut — leads at SPM 25. The three global mega-hits are at the bottom: P.Y.T. (10), Billie Jean (5, despite 15,883 saves), and Thriller (3, the weakest signal in the entire set). The bigger the hit, the more passive its stream base.

**Four tracks topped 38K saves — all-time top-4 absolute save counts:** Everybody Wants To Rule The World (84,186), Take on Me (44,256), Africa (40,449), Smooth Operator (38,959). Before this playlist, the record was 31,029. The 80s canon radios are the most-saved radios on Spotify among everything measured — but the billion-scale denominators keep SPM modest for all but Sade.

**Whitney, Eurythmics, AC/DC, Bryan Adams sit mid-table (SPM 12–14)** — huge save counts fully absorbed by 1.7–2.8B stream bases. Textbook mainstream-catalog behavior, consistent with Coldplay.

**The 6 unscored tracks are a systematic finding, not noise.** La Isla Bonita, Heaven Is A Place On Earth, Beat It, Eyes Without A Face, Material Girl, and Holiday all failed because the playlist's release ID differs from what the radios seed (remasters/reissues). Madonna alone accounts for 3 of 6 — her catalog's 2024 remaster campaign replaced playlist IDs while the radios still seed the older release IDs.

---

## Tracks Without Radio Seed Data (6 tracks)

All version/remaster ID mismatches:

| # | Track | Reason |
|---|-------|--------|
| 1 | La Isla Bonita (Madonna) | Five radios exist; all seed other release IDs |
| 3 | Heaven Is A Place On Earth (Belinda Carlisle) | Radios seed other versions |
| 8 | Beat It (Michael Jackson) | Radios seed other Beat It versions |
| 9 | Eyes Without A Face - Remastered 1999 (Billy Idol) | No radio for the 1999 remaster ID |
| 11 | Material Girl - 2024 Remaster (Madonna) | Radios seed the original version |
| 14 | Holiday (Madonna) | Holiday radios seed other same-titled tracks |

---

## Raw Data Reference

See `all_out_80s_spm_analysis.csv` for full worksheet.

**Stream source:** Spotify track pages; kworb.net Michael Jackson songs page (`3fMbdgg4jU18AjLCKBhRSm`) for Thriller, Human Nature, P.Y.T.
**Save counts:** Fetched directly from each radio playlist's Spotify page.
