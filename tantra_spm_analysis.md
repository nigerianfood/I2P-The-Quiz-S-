# Tantra — SPM (Saves Per Million) Analysis

**Playlist:** [Tantra](https://open.spotify.com/playlist/37i9dQZF1DWSlskcBvOTt0)  
**Analysis Date:** 2026-06-26  
**Tracks Analyzed:** 30

## Methodology

**SPM Formula:** `SPM = (Radio Playlist Saves ÷ Seed Track Streams) × 1,000,000`

- **Radio saves** sourced from Spotify's auto-generated `{track name} Radio` playlists (title-only search, no artist appended)
- **Seed verification** via `image_uri` path: `pickasso.spotifycdn.com/.../radio/track/{trackID}/en` must match the playlist track's Spotify ID
- Top 3 radio search candidates checked; if no seed match in top 3 → logged as "no seed match"
- **Stream counts** from kworb.net (primary, all 404'd) → fallback to Spotify track/artist page popular tracks section
- Tracks whose stream counts are not visible in the popular tracks section are marked `UNKNOWN`; SPM cannot be calculated and is marked `N/A`

---

## Data Table

| # | Track | Artist | Track ID | Streams | Radio Playlist ID | Seed ✓ | Radio Saves | SPM Formula | **SPM** |
|---|-------|--------|----------|---------|-------------------|--------|-------------|-------------|---------|
| 1 | Sunset In Pretoria | Shimza, Demayä | `03vLVYmqX7k3gKm3kOQIai` | UNKNOWN | `37i9dQZF1E8PulEQyioPkL` | ✅ | 17 | 17 / UNKNOWN × 1M | **N/A** |
| 2 | The Only One - Radio Edit | Bedouin, Luch, Karl Williams | `3eEdbkAYt1mYKDoHYzc4Ig` | 318,617 | `37i9dQZF1E8N0sK31U9oke` | ✅ | 47 | 47 / 318617 × 1M | **148** |
| 3 | EVERYTHING IN ITS RIGHT PLACE | LE YORA, SOMMA, JEWELS, YUMA, MAGNUS | `03p9MCjq5ld1kRmqCGNXgs` | 2,799,984 | `37i9dQZF1E8PexTDB6KGti` | ✅ | 555 | 555 / 2799984 × 1M | **198** |
| 4 | Chasing Fire | IDRIS | `67iuYoqmDfJ5BqNiL4WWyi` | UNKNOWN | — | ❌ no seed match | — | — | **N/A** |
| 5 | Be The One | Adam Port, SG Lewis, Keinemusik | `4gDKviRLkpZowZhcnRPqqE` | 8,355,383 | `37i9dQZF1E8Lta6jwdlt5N` | ✅ | 253 | 253 / 8355383 × 1M | **30** |
| 6 | Macho | DESIREE, Emmanuel Jal | `1lfrEfIqFx5uUrJInBub0n` | UNKNOWN | `37i9dQZF1E8Nuo93SrfLFi` | ✅ | 8 | 8 / UNKNOWN × 1M | **N/A** |
| 7 | Allo | Alex Wann, JUNO (DE) | `0KulM7tmm7fqNUORBooiXg` | UNKNOWN | `37i9dQZF1E8MTn08nFcwFA` | ✅ | 14 | 14 / UNKNOWN × 1M | **N/A** |
| 8 | Shine A Light | Kitty Amor | `7yPLswWaozPXqZCcz0Dcp9` | 58,332 | — | ❌ no seed match | — | — | **N/A** |
| 9 | Te Doy La Libertad | MESTIZA | `5ODIUPpNdmVZRjTMHa0Vjp` | UNKNOWN | `37i9dQZF1E8Ldwa5PWftUz` | ✅ | 33 | 33 / UNKNOWN × 1M | **N/A** |
| 10 | Attract | Ajna, Samm | `4ykK6tNnlu2fAAWPCxzvFc` | UNKNOWN | `37i9dQZF1E8KWSrb12wREc` | ✅ | 16 | 16 / UNKNOWN × 1M | **N/A** |
| 11 | I Know Who I Be | Davido, JAZZWRLD, GL_Ceejay | `1TglprKNjHw9rmTNgVZpUu` | UNKNOWN | — | ❌ no seed match | — | — | **N/A** |
| 12 | Repeat | Vanco, DEELA | `5s8W9kVGieuKlxDsECr7aP` | 375,883 | — | ❌ no seed match | — | — | **N/A** |
| 13 | I AM | OMAH LAY | `1iDNf6nP0BCXilLVVptflh` | 18,719,497 | — | ❌ no seed match | — | — | **N/A** |
| 14 | Champagne | Francis Mercier, MASSALA, LexBlaze | `7dfiOtJr96c3VGUI0JdnJE` | UNKNOWN | — | ❌ no seed match | — | — | **N/A** |
| 15 | Cola (ARTBAT Remix) | CamelPhat, Elderbrook, ARTBAT | `58caScGqKTQIDDJQ7QnJU8` | 7,273,468 | — | ❌ no seed match | — | — | **N/A** |
| 16 | FOCUS | Dr. Chaii, KARABA, Emily Apollo, KMNI | `3WfWhh0UEe9AaLdUDqv70P` | UNKNOWN | — | ❌ no seed match | — | — | **N/A** |
| 17 | SARU | Sara Costa | `2iKf7dqfmgp1cIoZOrroCw` | UNKNOWN | `37i9dQZF1E8O2awHSW1SaP` | ✅ | 2 | 2 / UNKNOWN × 1M | **N/A** |
| 18 | Dum Tak | Juany Bravo, NODUS, Murmusica | `1yXPwKVe5Yvw9FUBjHIu07` | 148,782 | `37i9dQZF1E8N5SHiFfCH7c` | ✅ | 14 | 14 / 148782 × 1M | **94** |
| 19 | Close 2 U | Paperwater | `4KR4fvzuBru2PNqqhAZGk0` | UNKNOWN | `37i9dQZF1E8P69MeiCwNLg` | ✅ | 8 | 8 / UNKNOWN × 1M | **N/A** |
| 20 | Mindgames | Yamil, Clemente, Groove Shack, Pieces Of Life | `29nPx72E4v4mGiTgv5PzxZ` | UNKNOWN | `37i9dQZF1E8NVsjwqn5b2w` | ✅ | 2 | 2 / UNKNOWN × 1M | **N/A** |
| 21 | Yivule | CIZA | `783s9jQYL85ipURwgyIB6I` | UNKNOWN | `37i9dQZF1E8Pvk4Vrap5pr` | ✅ | 20 | 20 / UNKNOWN × 1M | **N/A** |
| 22 | Reina de la Pista | Miluhska | `5ZmOi8QTdksIUcyjvwYQGx` | UNKNOWN | `37i9dQZF1E8LeDjO9ulCvo` | ✅ | 28 | 28 / UNKNOWN × 1M | **N/A** |
| 23 | Where Do We Go (Peggy Gou Remix) | Ayra Starr, Peggy Gou | `7icTQjIbMxfkOU71InqarB` | UNKNOWN | — | ❌ no seed match | — | — | **N/A** |
| 24 | Wo´s Patric?!? | DJ Koze | `0SbwJZ37eiEaWIxIP7dS8c` | 99,846 | `37i9dQZF1E8P0kvX6V7Vv8` | ✅ | 12 | 12 / 99846 × 1M | **120** |
| 25 | Chor | Indo Warehouse, Rashmeet Kaur, Kahani, Kunal Merchant | `7maiSgBL2JC4icWRAemLHZ` | UNKNOWN | — | ❌ no seed match | — | — | **N/A** |
| 26 | Let's Get Down | Yulia Niko, Supafly | `5jEgK8fb8NT3DlFqG7dqRx` | UNKNOWN | `37i9dQZF1E8PAuhwAeQt7Y` | ✅ | 2 | 2 / UNKNOWN × 1M | **N/A** |
| 27 | Mean 2 Me | Skyla Tylaa, Kitty Amor, Ruger | `6IMJPS60S4PuO4dsyGSaDc` | 773,304 | — | ❌ no seed match | — | — | **N/A** |
| 28 | A Feeling I Miss (SAMA Remix) | Cassian, Matt Ryder, SAMA (US) | `50xyYrPZV6rs5pmAIozDMt` | UNKNOWN | `37i9dQZF1E8NQKzGH6lRxG` | ✅ | 19 | 19 / UNKNOWN × 1M | **N/A** |
| 29 | Move | Adam Port, Stryv, Keinemusik, Orso, Malachiii | `1BJJbSX6muJVF2AK7uH1x4` | 895,330,788 | `37i9dQZF1E8NtjM3tRpfk8` | ✅ | 41,269 | 41269 / 895330788 × 1M | **46** |
| 30 | Sunrise (Adam Ten Remix) | Shouse, Adam Ten | `4CrKKZuQtC5GgCSBRl1zpk` | 7,151,315 | — | ❌ no seed match | — | — | **N/A** |

---

## SPM Rankings (Calculable Tracks Only)

| Rank | Track | Artist | SPM | Streams | Radio Saves | Signal Read |
|------|-------|--------|-----|---------|-------------|-------------|
| 1 | EVERYTHING IN ITS RIGHT PLACE | LE YORA, SOMMA, JEWELS, YUMA, MAGNUS | **198** | 2,799,984 | 555 | 🔥 Strong intent — meaningful reach, high save rate |
| 2 | The Only One - Radio Edit | Bedouin, Luch, Karl Williams | **148** | 318,617 | 47 | Strong early signal — minimal reach, high conversion |
| 3 | Wo´s Patric?!? | DJ Koze | **120** | 99,846 | 12 | Hyper-niche, intent-rich audience |
| 4 | Dum Tak | Juany Bravo, NODUS, Murmusica | **94** | 148,782 | 14 | Early-stage intent |
| 5 | Move | Adam Port, Stryv, Keinemusik, Orso, Malachiii | **46** | 895,330,788 | 41,269 | Diluted by 895M streams — mainstream absorption |
| 6 | Be The One | Adam Port, SG Lewis, Keinemusik | **30** | 8,355,383 | 253 | Established track — low relative intent |

---

## N/A Tracks

### Streams UNKNOWN (radio seed verified, SPM pending stream count)

| # | Track | Artist | Radio Saves | Notes |
|---|-------|--------|-------------|-------|
| 1 | Sunset In Pretoria | Shimza, Demayä | 17 | Not in artist popular tracks |
| 6 | Macho | DESIREE, Emmanuel Jal | 8 | Not in artist popular tracks |
| 7 | Allo | Alex Wann, JUNO (DE) | 14 | Not in artist popular tracks |
| 9 | Te Doy La Libertad | MESTIZA | 33 | Not in artist popular tracks |
| 10 | Attract | Ajna, Samm | 16 | Not in artist popular tracks |
| 17 | SARU | Sara Costa | 2 | Not in artist popular tracks |
| 19 | Close 2 U | Paperwater | 8 | Not in artist popular tracks |
| 20 | Mindgames | Yamil, Clemente, Groove Shack, Pieces Of Life | 2 | Not in artist popular tracks |
| 21 | Yivule | CIZA | 20 | Not in artist popular tracks |
| 22 | Reina de la Pista | Miluhska | 28 | Not in artist popular tracks |
| 26 | Let's Get Down | Yulia Niko, Supafly | 2 | Not in artist popular tracks |
| 28 | A Feeling I Miss (SAMA Remix) | Cassian, Matt Ryder, SAMA (US) | 19 | Not in artist popular tracks |

### No Seed Match (top 3 radio results did not seed from this track's ID)

| # | Track | Artist | Streams | Notes |
|---|-------|--------|---------|-------|
| 4 | Chasing Fire | IDRIS | UNKNOWN | Generic title, seeds from other tracks |
| 8 | Shine A Light | Kitty Amor | 58,332 | No matching radio seed found |
| 11 | I Know Who I Be | Davido, JAZZWRLD, GL_Ceejay | UNKNOWN | Davido radio seeds from bigger tracks |
| 12 | Repeat | Vanco, DEELA | 375,883 | Generic title, seeds from other tracks |
| 13 | I AM | OMAH LAY | 18,719,497 | OMAH LAY radio seeds from bigger tracks |
| 14 | Champagne | Francis Mercier, MASSALA, LexBlaze | UNKNOWN | Generic title |
| 15 | Cola (ARTBAT Remix) | CamelPhat, Elderbrook, ARTBAT | 7,273,468 | CamelPhat radio seeds from Cola original |
| 16 | FOCUS | Dr. Chaii, KARABA, Emily Apollo, KMNI | UNKNOWN | No matching radio seed found |
| 23 | Where Do We Go (Peggy Gou Remix) | Ayra Starr, Peggy Gou | UNKNOWN | Ayra Starr radio seeds from bigger tracks |
| 25 | Chor | Indo Warehouse, Rashmeet Kaur, Kahani, Kunal Merchant | UNKNOWN | No matching radio seed found |
| 27 | Mean 2 Me | Skyla Tylaa, Kitty Amor, Ruger | 773,304 | No matching radio seed found |
| 30 | Sunrise (Adam Ten Remix) | Shouse, Adam Ten | 7,151,315 | Shouse radio seeds from bigger tracks |

---

## Key Takeaways

**Top signals (SPM ≥ 100):**
- **EVERYTHING IN ITS RIGHT PLACE** (198) — 2.8M streams with 555 radio saves; strongest discovery pull in the playlist, genuine underground momentum building
- **The Only One - Radio Edit** (148) — only 318K streams; absolute saves are small (47) but the rate per listener is high — earliest-stage signal on the playlist
- **Wo´s Patric?!?** (120) — near-zero reach (99K streams), 12 saves signals a hyper-niche but intent-rich audience; DJ Koze underground discovery track

**Mid-tier signals (SPM 40–100):**
- **Dum Tak** (94) — similar profile to Wo´s Patric?!?, early-stage club track gaining traction
- **Move** (46) — 895M streams means the 41,269 radio saves are cosmetically impressive but SPM is diluted; no longer an early-signal name; included here for completeness

**Established / low relative intent:**
- **Be The One** (30) — expected for a well-known crossover track at 8.3M streams

**High N/A rate (24 out of 30 tracks):**
- **12 streams UNKNOWN** — this playlist skews very new/niche; most of these tracks will become calculable once they cross ~500K streams; Te Doy La Libertad (33 saves), Reina de la Pista (28 saves), and Attract (16 saves) are worth re-checking
- **12 no seed match** — several established artists (Davido, OMAH LAY, CamelPhat, Shouse, Ayra Starr) whose radio playlists seed from their bigger catalogue tracks rather than the featured collab; Cola (ARTBAT Remix) and Sunrise (Adam Ten Remix) both have 7M+ streams but cannot be scored
