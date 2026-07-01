# SPM Analysis — Italo Disco
**Playlist:** Italo Disco (`37i9dQZF1DX3jWba5xiDhV`) — "When the dancefloor calls your name, that's amore."
**Playlist Saves:** 412,569
**Tracks Analyzed:** 30
**Tracks Scored:** 25
**Date:** 2026-07-01

---

## Methodology

**SPM (Saves Per Million)** = Radio Playlist Saves ÷ Seed Track Streams × 1,000,000

For each track, I searched Spotify for its title-only Radio playlist (e.g., "Tarzan Boy Radio"), verified the seed track via the `image_uri` path (`/radio/track/{trackID}/en`), fetched the radio playlist's save count from its Spotify page, and fetched the track's total stream count from its Spotify track page (kworb per-artist pages as fallback when the track page hides the count).

**Methodology notes:**
- All searches use title-only queries — no artist names. Artist names suppress auto-generated radio playlists from results.
- For generic titles, appending the full version qualifier (e.g., "Faces Prod. by Roberto Ferrante 2020 Remaster Radio") retrieves the exact radio when the plain title fails. This recovered track 12.
- This is a multi-artist editorial playlist, so stream counts came directly from Spotify track pages rather than one artist's kworb page. 25/30 tracks scored — the highest hit rate of any playlist analyzed so far, because these catalog classics almost all seed radio playlists that rank at or near the top of search.

**Scale context:** Italo disco is a catalog/nostalgia genre with a very active DJ and crate-digger discovery culture. Stream bases range from 1.2M (Dirty Talk) to 318M (Tarzan Boy). SPM values in the 60–120 range here are common — structurally higher than mainstream pop because listeners who find these tracks are disproportionately intentional diggers rather than passive algorithmic listeners.

---

## SPM Rankings

| Rank | Track | Artist | SPM | Streams | Radio Saves | Signal Read |
|------|-------|--------|-----|---------|-------------|-------------|
| 1 | She Can't Love You | Chemise | 123 | 23,721,369 | 2,921 | Strongest discovery signal in set |
| 2 | I Need You Tonight | Punkin Machine | 122 | 17,520,159 | 2,129 | Modern italo revival flagship |
| 3 | The Glow of Love | Change, Luther Vandross | 118 | 4,633,428 | 547 | High intent on boogie crossover |
| 4 | Mediterranea - Dumar Remix | Giuni Russo, Dumar | 105 | 2,012,697 | 211 | Strong ratio on remix catalog |
| 5 | Problèmes d'Amour - Original | Alexander Robotnick | 96 | 1,659,877 | 159 | Crate-digger cult classic |
| 6 | Tutto va bene quando facciamo l'amore | Alex Rossi, Jo Wedin | 92 | 12,266,966 | 1,125 | Modern nu-italo with real pull |
| 7 | Okay Okay | Pino D'Angiò | 85 | 40,137,294 | 3,427 | High saves at real scale |
| 8 | Hypnotic Tango - Original 12" Version | My Mine | 85 | 16,422,181 | 1,399 | Genre cornerstone, active discovery |
| 9 | Disco Sole | Nu Genea | 84 | 13,457,307 | 1,135 | Nu Genea discovery engine |
| 10 | Dirty Talk | Klein & M.B.O. | 74 | 1,151,422 | 85 | High ratio on micro base |
| 11 | Ma quale idea | Pino D'Angiò | 72 | 105,495,945 | 7,644 | Second-most saves in set at 105M scale |
| 12 | Faces - 2020 Remaster | Clio, Roberto Ferrante | 68 | 8,377,974 | 573 | Reissue with genuine digger intent |
| 13 | Two of Hearts | Stacey Q | 67 | 88,397,943 | 5,957 | Big catalog, big intent |
| 14 | Everybody Everybody | Black Box | 60 | 54,367,920 | 3,235 | Strong house-crossover signal |
| 15 | Happy Song (Clap Your Hands) (Remix) | Babys Gang | 58 | 2,496,712 | 146 | Solid niche signal |
| 16 | Onenon | Nu Genea, Tom Misch | 50 | 1,651,693 | 82 | New release, early discovery |
| 17 | I Like Chopin | Gazebo | 38 | 71,969,232 | 2,716 | Passive catalog at scale |
| 18 | Tarzan Boy | Baltimora | 34 | 318,185,459 | 10,830 | Most saves in set; ratio diluted by 318M streams |
| 19 | Ride on Time | Black Box | 27 | 129,140,700 | 3,461 | Mainstream catalog behavior |
| 20 | Splendida giornata | Vasco Rossi | 17 | 16,872,176 | 280 | Rock catalog, not italo discovery |
| 21 | Ti Sento | Matia Bazar | 16 | 44,771,512 | 708 | Passive nostalgia streams |
| 22 | Happy Children | P. Lion | 12 | 24,957,296 | 304 | Low intent despite genre status |
| 23 | Dolce Vita | Ryan Paris | 9 | 31,302,181 | 292 | Passive catalog play |
| 24 | Vamos a la Playa | Righeira | 8 | 59,161,884 | 478 | Novelty-hit passive streaming |
| 25 | Don't Cry Tonight | Savage | 7 | 13,361,731 | 100 | Weakest signal in set |

---

## Key Findings

**She Can't Love You (Chemise) leads at SPM 123.** 2,921 saves on 23.7M streams. This 1982 boogie record is a canonical DJ edit-culture track (the Purple Disco Machine edit keeps it circulating), and the radio playlist pulls listeners at nearly one save per 8,100 streams — the clearest discovery engine in the set.

**I Need You Tonight (Punkin Machine, SPM 122) is the modern italo revival flagship.** 2,129 saves on 17.5M streams for a contemporary production proves the italo pipeline isn't just nostalgia — new tracks in the idiom generate the same discovery intent as the classics.

**The Glow of Love (SPM 118) shows remarkable intent on a small base.** The Change/Luther Vandross boogie classic — the record Modjo sampled for "Lady" — pulls 547 saves on just 4.6M streams for this version.

**The top 10 is dominated by digger records, not hits.** Chemise, Punkin Machine, Alexander Robotnick (SPM 96), Klein & M.B.O. (SPM 74), My Mine (SPM 85) — these are cult 12"s with modest stream counts and outsized save ratios. Meanwhile the genre's biggest mainstream hits sit at the bottom: Tarzan Boy (SPM 34 on 318M streams), Ride on Time (SPM 27), Vamos a la Playa (SPM 8), Dolce Vita (SPM 9). The pattern is textbook: passive nostalgia streaming suppresses SPM; crate-digger catalogs inflate it.

**Pino D'Angiò is the strongest artist across the set.** Both entries land high: Ma quale idea (SPM 72 with 7,644 saves — the second-highest absolute save count in the set, on 105M streams) and Okay Okay (SPM 85, 3,427 saves). His TikTok-era revival translated into genuine catalog discovery, not just viral plays.

**Nu Genea's three entries chart the lifecycle of discovery.** Disco Sole (SPM 84) is the established discovery engine, Onenon with Tom Misch (SPM 50) is the new release building momentum, and Marechià — their biggest track at 45.7M streams — couldn't be scored because the radio seeds a different version than the playlist's single edit.

**Tarzan Boy has the most absolute radio saves ever measured in these analyses (10,830) yet ranks 18th at SPM 34.** The 318M stream denominator absorbs it. Same story as Coldplay: massive catalogs generate huge raw saves but low per-stream intent.

**The bottom five (Splendida giornata, Ti Sento, Happy Children, Dolce Vita, Vamos a la Playa, Don't Cry Tonight) are all passive nostalgia plays** — streamed heavily in Italy and on throwback playlists but generating almost no radio-save intent.

---

## Tracks Without Radio Seed Data (5 tracks)

| # | Track | Reason |
|---|-------|--------|
| 8 | Self Control (Raf) | Laura Branigan and cover versions dominate all 5 results |
| 20 | Call Me (Ivana Spagna) | Blondie and other "Call Me" versions dominate results |
| 22 | Reset | Generic title — artist radios (Travis Scott etc.) dominate results |
| 24 | Marechià | Radio playlist seeds a different track version (`3NYm3ZimuJNb0Z0px5OEwO`), not the playlist version |
| 26 | Burn It! | Burn It! Radio seeds a different track (`0XHSwT15ALpe58lcehwlP6`) |

---

## Raw Data Reference

See `italo_disco_spm_analysis.csv` for full worksheet.

**Stream source:** Spotify track pages (play counts server-rendered); kworb.net per-artist songs pages as fallback (Vasco Rossi, Nu Genea).
**Save counts:** Fetched directly from each radio playlist's Spotify page.
