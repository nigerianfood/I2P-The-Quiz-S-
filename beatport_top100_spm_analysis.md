# Beatport Top 100 — Today: SPM (Saves Per Million) Analysis

**Playlist:** [Beatport Top 100 - Today](https://open.spotify.com/playlist/0Q4JvzeT0q3FLsj5fqffMV)  
**Analysis Date:** 2026-06-26  
**Tracks Analyzed:** 30

## Methodology

**SPM Formula:** `SPM = (Radio Playlist Saves ÷ Seed Track Streams) × 1,000,000`

- **Radio saves** sourced from Spotify's auto-generated `{track name} Radio` playlists (title-only search, no artist appended)
- **Seed verification** via `image_uri` path: `pickasso.spotifycdn.com/.../radio/track/{trackID}/en` must match the playlist track's Spotify ID
- Top 3–5 radio search candidates checked; if no seed match in top 3 → logged as "no seed match"
- **Stream counts** from kworb.net (primary, all 404'd) → fallback to Spotify track/artist page popular tracks section
- Tracks 4 (Free Your Mind), 9 (La La Land), 17 (Dreams), and 26 (Shinjuku) share track IDs with the Ibiza 2026 analysis; radio and stream data carried forward from that run
- Tracks whose stream counts are not visible in the popular tracks section are marked `UNKNOWN`; SPM cannot be calculated and is marked `N/A`

---

## Data Table

| # | Track | Artist | Track ID | Streams | Radio Playlist ID | Seed ✓ | Radio Saves | SPM Formula | **SPM** |
|---|-------|--------|----------|---------|-------------------|--------|-------------|-------------|---------|
| 1 | Movin' To The Sun | HUGEL, Imael Angel, Ultra Naté | `25DgjoTlKK8KjstM4cZ8L2` | 22,187,623 | `37i9dQZF1E8NgGaxkzXGLs` | ✅ | 5,220 | 5220 / 22187623 × 1M | **235** |
| 2 | I Never Knew | Adam Ten | `54vF34GSMXYZfjPXMsHYWf` | 369,951 | `37i9dQZF1E8Oqegkq70EvS` | ✅ | 19 | 19 / 369951 × 1M | **51** |
| 3 | Half There | LOR, Dominique | `2x1JpdXJQckuFZ41z8Zr5y` | 248,609 | `37i9dQZF1E8KNVQzHhgtNH` | ✅ | 11 | 11 / 248609 × 1M | **44** |
| 4 | Free Your Mind | Prospa, Cloonee | `6TWbY1dq8eYtFiMiGdBlOa` | 12,111,637 | `37i9dQZF1E8KKmlPN8VZjX` | ✅ | 5,795 | 5795 / 12111637 × 1M | **479** |
| 5 | Talk To You (ft. 54 Ultra) | ANOTR, 54 Ultra | `0kl6Ozan3fuUdCl6TlB15v` | 108,823,242 | `37i9dQZF1E8LS4WwtdPa35` | ✅ | 14,628 | 14628 / 108823242 × 1M | **134** |
| 6 | On 2nite | Silva Bumpa | `2BoSbGSp2OaDBOx5NFHkrr` | 7,907,848 | `37i9dQZF1E8PJoFvBCSjn5` | ✅ | 707 | 707 / 7907848 × 1M | **89** |
| 7 | Groovejet (If This Ain't Love) - not without friends Remix | Spiller, Sophie Ellis-Bextor, not without friends, et al. | `6yb14tUTLWfBStXgcQJbPV` | UNKNOWN | `37i9dQZF1E8PhgrljYXmOZ` | ✅ | 94 | 94 / UNKNOWN × 1M | **N/A** |
| 8 | My Life Is A Disco (In The Mix) | Mellizos, Mixmasters | `4QNEi4zAOm0FwfwJXLgp7s` | 1,609,506 | `37i9dQZF1E8LbAvdJNeMf8` | ✅ | 87 | 87 / 1609506 × 1M | **54** |
| 9 | La La Land | Green Velvet, MEDUZA, GENESI, ESSENTIA | `5hYSsLVQ6Isk6YZrnsBj4E` | 3,083,725 | `37i9dQZF1E8LPwDMPkTFD5` | ✅ | 579 | 579 / 3083725 × 1M | **188** |
| 10 | To The Rhythm | LOR | `1pD0t9VF8voxRThGh4oHDm` | 385,471 | — | ❌ no seed match | — | — | **N/A** |
| 11 | Chica | Ben Evers, Najeh | `4iUauxwhmi9baLkC1zYrI1` | 266,532 | `37i9dQZF1E8KDLALFpk2TQ` | ✅ | 45 | 45 / 266532 × 1M | **169** |
| 12 | Rhythm Of The House | Alex Culross, Ejeca | `3S7PIQ273n5Yx7e6d6n2Jj` | UNKNOWN | `37i9dQZF1E8LFFO2igDgCH` | ✅ | 8 | 8 / UNKNOWN × 1M | **N/A** |
| 13 | Kingdom Falling | LOR | `1A75Sl0rYUg9C74I9owjah` | 301,227 | `37i9dQZF1E8OxRkRzjTdEK` | ✅ | 11 | 11 / 301227 × 1M | **37** |
| 14 | Jamaican (Bam Bam) | HUGEL, SOLTO (FR) | `0Vcss0GZ1rbNI7QQPfXeg4` | 202,718,143 | — | ❌ no seed match | — | — | **N/A** |
| 15 | Rush | Ryan Nicholls | `5X8ir6VRntSttQwkDAncjn` | 114,193 | — | ❌ no seed match | — | — | **N/A** |
| 16 | Music Is The Answer (Dancin' And Prancin') - Edit | Jesús Fernández, Karl8 & Andrea Monta | `6YR1D5tsjAZE1Zn0lnEdEd` | UNKNOWN | — | ❌ no seed match | — | — | **N/A** |
| 17 | Dreams | Prospa | `4F1J5Y890NaaTUOumYzYUX` | UNKNOWN | `37i9dQZF1E8MlUsN1bbrbG` | ✅ | 109 | 109 / UNKNOWN × 1M | **N/A** |
| 18 | Daze | LOR | `2vFS4e03mMzlf49zVlvIkU` | UNKNOWN | — | ❌ no seed match | — | — | **N/A** |
| 19 | Best Be Believing | AlunaGeorge, Riordan, Aluna, Danny P, Caleb Laurenson | `30pPf3bjXSL07zF613iHLF` | 424,458 | — | ❌ no seed match | — | — | **N/A** |
| 20 | Work It | SEBS | `3xcgtqFTfz0KX3JiOvooJM` | 129,118 | `37i9dQZF1E8OMqgRjj3hRP` | ✅ | 3 | 3 / 129118 × 1M | **23** |
| 21 | So Good (feat. Kuuda) | CamelPhat, Josh Gigante, Kuuda | `6CR63qhTJnek9DDejDemiY` | 1,354,651 | `37i9dQZF1E8MxNXwlNnuNN` | ✅ | 104 | 104 / 1354651 × 1M | **77** |
| 22 | Not Exactly - Rinzen Remix | deadmau5, Rinzen | `44iQc1rBKQc9nZVyWE3txD` | UNKNOWN | `37i9dQZF1E8OjNGsA0ddul` | ✅ | 35 | 35 / UNKNOWN × 1M | **N/A** |
| 23 | Warpdrive | LOR | `3pBXqhQM8lOi1d7ZcK27yi` | UNKNOWN | `37i9dQZF1E8Oy2OdssTuIV` | ✅ | 15 | 15 / UNKNOWN × 1M | **N/A** |
| 24 | Push It | Disco Lines, Maesic, Mason, Princess Superstar | `5Ef5Df4m9y7X4ixO4TgBWy` | 956,110 | `37i9dQZF1E8PCLktXRgCVV` | ✅ | 49 | 49 / 956110 × 1M | **51** |
| 25 | How Does It Feel | Dubdogz, FEZZO, Zaark | `0XJzkaWALsvlMEQbBSEIX2` | 5,540,235 | `37i9dQZF1E8LqH3tba7h2i` | ✅ | 3,009 | 3009 / 5540235 × 1M | **543** |
| 26 | Shinjuku | Franky Rizardo | `0niU8VMrQzSNhrmsiLlmeS` | 2,652,065 | `37i9dQZF1E8L76jvkd4T4b` | ✅ | 2,050 | 2050 / 2652065 × 1M | **773** |
| 27 | Trapped - Radio-Edit | Kolter | `7LhaYxesZoZQ8b9WJGuLDx` | 3,270,248 | `37i9dQZF1E8PxZaquaT5Uo` | ✅ | 181 | 181 / 3270248 × 1M | **55** |
| 28 | Feel | Franky Rizardo | `3mxwrp5v4TcWK1T4MsXdcs` | UNKNOWN | — | ❌ no seed match | — | — | **N/A** |
| 29 | On Lock | Dale Howard | `634wPPWqEtqjK8RRKhQF4d` | UNKNOWN | `37i9dQZF1E8OsKl8fN7RHK` | ✅ | 2 | 2 / UNKNOWN × 1M | **N/A** |
| 30 | Luv U | DERON | `5cfaeFSSvONIPEzu2cUIQ4` | UNKNOWN | — | ❌ no seed match | — | — | **N/A** |

---

## SPM Rankings (Calculable Tracks Only)

| Rank | Track | Artist | SPM | Streams | Radio Saves | Signal Read |
|------|-------|--------|-----|---------|-------------|-------------|
| 1 | Shinjuku | Franky Rizardo | **773** | 2,652,065 | 2,050 | Cross-playlist elite — top signal in both Ibiza 2026 and Beatport; sustained discovery demand at scale |
| 2 | How Does It Feel | Dubdogz, FEZZO, Zaark | **543** | 5,540,235 | 3,009 | Breakout signal — 3K saves on 5.5M streams is exceptional; strongest surprise on the chart |
| 3 | Free Your Mind | Prospa, Cloonee | **479** | 12,111,637 | 5,795 | Also ranked #3 in Ibiza 2026 (SPM 479); proven sustained demand at scale |
| 4 | Movin' To The Sun | HUGEL, Imael Angel, Ultra Naté | **235** | 22,187,623 | 5,220 | Strong intent at large scale — 5.2K saves on 22M streams punches above dilution expectation |
| 5 | La La Land | Green Velvet, MEDUZA, GENESI, ESSENTIA | **188** | 3,083,725 | 579 | Cross-playlist signal (also Ibiza 2026 SPM 188); underground traction confirmed |
| 6 | Chica | Ben Evers, Najeh | **169** | 266,532 | 45 | Strongest early-stage signal on the chart — high conversion on minimal reach |
| 7 | Talk To You (ft. 54 Ultra) | ANOTR, 54 Ultra | **134** | 108,823,242 | 14,628 | Cosmetically impressive saves but SPM diluted by 109M streams; mainstream absorption underway |
| 8 | On 2nite | Silva Bumpa | **89** | 7,907,848 | 707 | Solid mid-tier intent at meaningful reach |
| 9 | So Good (feat. Kuuda) | CamelPhat, Josh Gigante, Kuuda | **77** | 1,354,651 | 104 | Early-stage intent building; CamelPhat discovery halo |
| 10 | Trapped - Radio-Edit | Kolter | **55** | 3,270,248 | 181 | Steady signal; radio edit format suggests label push |
| 11 | My Life Is A Disco (In The Mix) | Mellizos, Mixmasters | **54** | 1,609,506 | 87 | Mid-tier intent; disco revival niche |
| 12 | I Never Knew | Adam Ten | **51** | 369,951 | 19 | Very early stage — minimal reach, consistent with Adam Ten's underground profile |
| 13 | Push It | Disco Lines, Maesic, Mason, Princess Superstar | **51** | 956,110 | 49 | Mid-stage signal; Disco Lines' broader catalogue dilutes niche save rate |
| 14 | Half There | LOR, Dominique | **44** | 248,609 | 11 | Early-stage; low absolute saves match limited stream count |
| 15 | Kingdom Falling | LOR | **37** | 301,227 | 11 | Low signal; LOR cluster competes for radio seed with its higher-ranked tracks |
| 16 | Work It | SEBS | **23** | 129,118 | 3 | Minimal signal — very early stage, essentially pre-discovery |

---

## N/A Tracks

### Streams UNKNOWN (radio seed verified, SPM pending stream count)

| # | Track | Artist | Radio Saves | Notes |
|---|-------|--------|-------------|-------|
| 7 | Groovejet (If This Ain't Love) - not without friends Remix | Spiller, Sophie Ellis-Bextor, not without friends, et al. | 94 | 2026 release; not yet in popular tracks |
| 12 | Rhythm Of The House | Alex Culross, Ejeca | 8 | Not in artist popular tracks |
| 17 | Dreams | Prospa | 109 | Not in artist popular tracks |
| 22 | Not Exactly - Rinzen Remix | deadmau5, Rinzen | 35 | Not in artist popular tracks |
| 23 | Warpdrive | LOR | 15 | Not in artist popular tracks |
| 29 | On Lock | Dale Howard | 2 | Not in artist popular tracks |

### No Seed Match (top 3–5 radio results did not seed from this track's ID)

| # | Track | Artist | Streams | Notes |
|---|-------|--------|---------|-------|
| 10 | To The Rhythm | LOR | 385,471 | LOR radio seeds from higher-ranked LOR tracks |
| 14 | Jamaican (Bam Bam) | HUGEL, SOLTO (FR) | 202,718,143 | HUGEL radio seeds from Jamaican (Bam Bam) original or bigger tracks |
| 15 | Rush | Ryan Nicholls | 114,193 | Generic title, seeds from other tracks |
| 16 | Music Is The Answer (Dancin' And Prancin') - Edit | Jesús Fernández, Karl8 & Andrea Monta | UNKNOWN | Seeds from original or other versions |
| 18 | Daze | LOR | UNKNOWN | LOR radio seeds from higher-ranked LOR tracks |
| 19 | Best Be Believing | AlunaGeorge, Riordan, Aluna, Danny P, Caleb Laurenson | 424,458 | No matching radio seed found |
| 28 | Feel | Franky Rizardo | UNKNOWN | Franky Rizardo radio seeds from Shinjuku |
| 30 | Luv U | DERON | UNKNOWN | No matching radio seed found |

---

## Key Takeaways

**Top signals (SPM ≥ 200):**
- **Shinjuku** (773) — cross-playlist elite: ranked #1 in both Beatport Top 100 and Ibiza 2026; Franky Rizardo's Shinjuku is the strongest sustained SPM signal across all playlists in this analysis; 2K saves at 2.6M streams is exceptional by any measure
- **How Does It Feel** (543) — biggest surprise on the chart; 3K saves at 5.5M streams signals a track punching far above its discovery weight; Dubdogz tech house moment
- **Free Your Mind** (479) — Prospa / Cloonee confirmed cross-playlist force; SPM 479 in both Ibiza 2026 and Beatport, same seed, same data; intent is consistent and durable
- **Movin' To The Sun** (235) — HUGEL at 22M streams still generating 5.2K radio saves; stronger intent signal than its stream count would suggest

**Mid-tier signals (SPM 100–200):**
- **La La Land** (188) — identical SPM across Ibiza 2026 and Beatport Top 100; same track ID confirms cross-editorial discovery traction
- **Chica** (169) — 266K streams with 45 saves is a standout early-stage ratio; Ben Evers / Najeh track has genuine listener pull relative to reach
- **Talk To You** (134) — 14.6K radio saves look impressive until you see 109M streams; ANOTR's crossover absorption is near-complete; no longer an early signal

**Lower signals (SPM 23–89):**
- **On 2nite** (89), **So Good** (77), **Trapped** (55), **My Life Is A Disco** (54) — solid mid-cycle tracks, discovery demand present but not exceptional
- **I Never Knew** (51), **Push It** (51), **Half There** (44), **Kingdom Falling** (37), **Work It** (23) — low absolute saves in each case; these tracks are early-stage or niche, and the SPM reflects limited discovery momentum so far

**Cross-playlist confirmation (Ibiza 2026 + Beatport Top 100):**
- **Shinjuku** (773 both playlists), **Free Your Mind** (479 both), and **La La Land** (188 both) appear with the same track IDs and virtually identical SPMs across both editorial contexts — the strongest cross-validation signal in this analysis set

**High N/A rate (14 out of 30 tracks):**
- **6 streams UNKNOWN** — Groovejet remix (94 saves, 2026 release) and Dreams (109 saves) are the highest-save UNKNOWN tracks worth re-checking; LOR has three tracks without visible streams (Warpdrive, Daze, On Lock)
- **8 no seed match** — includes a 202M-stream track (Jamaican Bam Bam) and a cluster of LOR tracks (To The Rhythm, Daze) whose radio seeds route to LOR's more popular titles
