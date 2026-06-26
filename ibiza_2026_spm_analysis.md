# Ibiza 2026 — SPM (Saves Per Million) Analysis

**Playlist:** [Ibiza 2026](https://open.spotify.com/playlist/37i9dQZF1DXaCACvgOVs5K)  
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
| 1 | Dreams | Prospa | `4F1J5Y890NaaTUOumYzYUX` | UNKNOWN | `37i9dQZF1E8MlUsN1bbrbG` | ✅ | 109 | 109 / UNKNOWN × 1M | **N/A** |
| 2 | Shinjuku | Franky Rizardo | `0niU8VMrQzSNhrmsiLlmeS` | 2,652,065 | `37i9dQZF1E8L76jvkd4T4b` | ✅ | 2,050 | 2050 / 2652065 × 1M | **773** |
| 3 | Call It What You Like | Robbie Doherty | `0o92pLHQhjyP2FdieF7xqw` | 10,956,087 | `37i9dQZF1E8KS2UjDqg2o4` | ✅ | 1,643 | 1643 / 10956087 × 1M | **150** |
| 4 | Be The One | Adam Port, SG Lewis, Keinemusik | `4gDKviRLkpZowZhcnRPqqE` | 8,355,383 | `37i9dQZF1E8Lta6jwdlt5N` | ✅ | 253 | 253 / 8355383 × 1M | **30** |
| 5 | High On Me | Rossi., Jazzy | `3Z23sDc2J9ZkmFiMStRoIp` | 54,783,618 | `37i9dQZF1E8P0I6RLzwsFN` | ✅ | 2,148 | 2148 / 54783618 × 1M | **39** |
| 6 | Free Your Mind | Prospa, Cloonee | `6TWbY1dq8eYtFiMiGdBlOa` | 12,111,637 | `37i9dQZF1E8KKmlPN8VZjX` | ✅ | 5,795 | 5795 / 12111637 × 1M | **479** |
| 7 | In This Bih' | Chris Lorenzo, Kah-Lo | `4QUxlbwlSBYiaTT27A5MEj` | 6,868,630 | `37i9dQZF1E8PD5CAt24LKS` | ✅ | 3,433 | 3433 / 6868630 × 1M | **500** |
| 8 | Livin' It Up | Gaskin, Aaron Pfeiffer | `1HHKgaNHfXePWrd6e14evK` | UNKNOWN | `37i9dQZF1E8PIU5swL3MIu` | ✅ | 6 | 6 / UNKNOWN × 1M | **N/A** |
| 9 | Out of My Mind | Joshwa | `2FFwFlkKjKBSCdVpPf38Gj` | 11,424,394 | `37i9dQZF1E8MbLPfItN69D` | ✅ | 258 | 258 / 11424394 × 1M | **23** |
| 10 | Freaky | Tita Lau | `6orYXU56P1zLY9YUFX5zJV` | 271,827 | — | ❌ no seed match | — | — | **N/A** |
| 11 | Baby | Prospa, Murda Beatz | `5q6QXK4K3DvIlwGEtElny3` | 3,451,181 | `37i9dQZF1E8L8ET5rwA3bm` | ✅ | 720 | 720 / 3451181 × 1M | **209** |
| 12 | La La Land | Green Velvet, Nadia Gattas, Junior Sanchez, Dj Mes | `5hYSsLVQ6Isk6YZrnsBj4E` | 3,083,725 | `37i9dQZF1E8LPwDMPkTFD5` | ✅ | 579 | 579 / 3083725 × 1M | **188** |
| 13 | Verano En NY | Toman | `7DxrTNmUprBMQ0RV45xreb` | 19,443,908 | `37i9dQZF1E8N4SsKFYQWMc` | ✅ | 2,622 | 2622 / 19443908 × 1M | **135** |
| 14 | Wide Awake | Chris Stussy, Tom Did It | `0ScBO3EflBAKRC1WjOyJT1` | 11,425,976 | `37i9dQZF1E8Mp6tsARaSN8` | ✅ | 267 | 267 / 11425976 × 1M | **23** |
| 15 | Bubbling | Dennis Cruz, Patrick Luna | `6GvfH6m9biXR8bL6WW8YX7` | 172,041 | `37i9dQZF1E8NhKIi8GYqjL` | ✅ | 7 | 7 / 172041 × 1M | **41** |
| 16 | You Don't Own Me | Prospa, Josh Baker, RAHH | `1TsDNh8OuRcGfNX4Dz8oVl` | UNKNOWN | `37i9dQZF1E8OvRRWLaznQn` | ✅ | 587 | 587 / UNKNOWN × 1M | **N/A** |
| 17 | Make Believe | Luke Dean, Omar+ | `7IoTUnyyvbMEY2UuE2Tmsx` | 28,931,991 | — | ❌ no seed match | — | — | **N/A** |
| 18 | Dancing | Grigoré, Darmon, Luca M | `5u9x7pvd4Kbhhhrpe53pRL` | 12,092,367 | — | ❌ no seed match | — | — | **N/A** |
| 19 | One Question | Cloonee, Groove Theory | `7JvaT4FTTF0aYyacmfbHRY` | 2,622,298 | `37i9dQZF1E8OBrpCxlzW4z` | ✅ | 194 | 194 / 2622298 × 1M | **74** |
| 20 | Ride On Me | PAWSA | `5WZQkHYzUGBpUCgCk9eXgA` | 1,300,611 | `37i9dQZF1E8NaQDu8C7sQx` | ✅ | 111 | 111 / 1300611 × 1M | **85** |
| 21 | Trippy Yeah | Jimi Jules, Black Coffee | `1CM0kiqrtCSHClFjTccTOb` | 13,052,524 | `37i9dQZF1E8KOaueGjavWG` | ✅ | 941 | 941 / 13052524 × 1M | **72** |
| 22 | CHICA 305 | John Summit, Feid | `2xz5qmonUWZytz5jIw04LM` | UNKNOWN | — | ❌ no seed match | — | — | **N/A** |
| 23 | Freaky 1 | Max Styler, Vintage Culture, Ali Love | `5cefCIhgIJgsG3r3LcRmwB` | 3,104,815 | `37i9dQZF1E8NhcVf7RydyJ` | ✅ | 249 | 249 / 3104815 × 1M | **80** |
| 24 | Everytime | IDEMI, Lustral | `5uaHSOou5ernQBKhfVse1f` | 9,207,927 | `37i9dQZF1E8PockTsYgIny` | ✅ | 780 | 780 / 9207927 × 1M | **85** |
| 25 | Reflections | IDEMI | `0ZZWyT8ppn9PxVe17WX2DR` | 1,106,135 | `37i9dQZF1E8Pnt9puzMs1C` | ✅ | 54 | 54 / 1106135 × 1M | **49** |
| 26 | Get Stupid | Julian Fijma | `22pC8m4kzjrMQRJXYg0usw` | 15,773,039 | `37i9dQZF1E8NkDtUTkmmYx` | ✅ | 650 | 650 / 15773039 × 1M | **41** |
| 27 | Contesto | Massuma, DOSAMIS | `4PjAtEHN8MXgXFQwTxIWva` | 10,995,924 | `37i9dQZF1E8OHxiL2EGOSx` | ✅ | 357 | 357 / 10995924 × 1M | **32** |
| 28 | TESLA | Mau P | `6qJhrI2BMuA8qHcmycD3fL` | UNKNOWN | `37i9dQZF1E8PMshzKW0FtP` | ✅ | 708 | 708 / UNKNOWN × 1M | **N/A** |
| 29 | Party Started | HUGEL, French Caviar, Emie Noa | `4KUvvPHDP6QEjs1T4ZIvA6` | UNKNOWN | `37i9dQZF1E8LQvLlGxqsDU` | ✅ | 239 | 239 / UNKNOWN × 1M | **N/A** |
| 30 | HOTS 4 U | Chris Lorenzo, aMo (um) | `5nMrR3Ed99WcQ4Vv0wy8Bf` | 1,728,918 | `37i9dQZF1E8NTKPYm4zgMi` | ✅ | 156 | 156 / 1728918 × 1M | **90** |

---

## SPM Rankings (Calculable Tracks Only)

| Rank | Track | Artist | SPM | Streams | Radio Saves | Signal Read |
|------|-------|--------|-----|---------|-------------|-------------|
| 1 | Shinjuku | Franky Rizardo | **773** | 2,652,065 | 2,050 | 🔥 Extreme intent — low reach, massive save rate |
| 2 | In This Bih' | Chris Lorenzo, Kah-Lo | **500** | 6,868,630 | 3,433 | 🔥 Strong conviction buyers |
| 3 | Free Your Mind | Prospa, Cloonee | **479** | 12,111,637 | 5,795 | 🔥 High saves + scale = real stickiness |
| 4 | Baby | Prospa, Murda Beatz | **209** | 3,451,181 | 720 | Strong intent relative to reach |
| 5 | La La Land | Green Velvet et al | **188** | 3,083,725 | 579 | Strong intent |
| 6 | Call It What You Like | Robbie Doherty | **150** | 10,956,087 | 1,643 | Solid — meaningful saves at scale |
| 7 | Verano En NY | Toman | **135** | 19,443,908 | 2,622 | Solid crossover stickiness |
| 8 | HOTS 4 U | Chris Lorenzo, aMo (um) | **90** | 1,728,918 | 156 | Early-stage intent |
| 9 | Ride On Me | PAWSA | **85** | 1,300,611 | 111 | Early-stage intent |
| 10 | Everytime | IDEMI, Lustral | **85** | 9,207,927 | 780 | Consistent intent at reach |
| 11 | Freaky 1 | Max Styler, Vintage Culture, Ali Love | **80** | 3,104,815 | 249 | Moderate intent |
| 12 | One Question | Cloonee, Groove Theory | **74** | 2,622,298 | 194 | Moderate intent |
| 13 | Trippy Yeah | Jimi Jules, Black Coffee | **72** | 13,052,524 | 941 | Moderate at scale |
| 14 | Reflections | IDEMI | **49** | 1,106,135 | 54 | Niche but present |
| 15 | Bubbling | Dennis Cruz, Patrick Luna | **41** | 172,041 | 7 | Low reach, consistent ratio |
| 16 | Get Stupid | Julian Fijma | **41** | 15,773,039 | 650 | Modest intent for scale |
| 17 | High On Me | Rossi., Jazzy | **39** | 54,783,618 | 2,148 | Diluted by massive stream count |
| 18 | Contesto | Massuma, DOSAMIS | **32** | 10,995,924 | 357 | Low intent for reach |
| 19 | Be The One | Adam Port, SG Lewis, Keinemusik | **30** | 8,355,383 | 253 | Low |
| 20 | Out of My Mind | Joshwa | **23** | 11,424,394 | 258 | Low |
| 21 | Wide Awake | Chris Stussy, Tom Did It | **23** | 11,425,976 | 267 | Low |

---

## N/A Tracks

| # | Track | Reason |
|---|-------|--------|
| 1 | Dreams | Streams UNKNOWN (not in popular tracks) |
| 8 | Livin' It Up | Streams UNKNOWN |
| 10 | Freaky | No seed match in top 3 radio results |
| 16 | You Don't Own Me | Streams UNKNOWN |
| 17 | Make Believe | No seed match (generic title) |
| 18 | Dancing | No seed match (generic title) |
| 22 | CHICA 305 | No seed match (top result seeds different version) |
| 28 | TESLA | Streams UNKNOWN |
| 29 | Party Started | Streams UNKNOWN |

---

## Key Takeaways

**Top signals (SPM ≥ 150):**
- **Shinjuku** (773) — outlier discovery pull, low streams = genuine underground momentum
- **In This Bih'** (500) — surging saver interest relative to scale
- **Free Your Mind** (479) — saves + streams at scale = algorithmic momentum candidate

**Mid-tier signals (SPM 70–150):** Call It What You Like, Verano En NY, Baby, La La Land — all showing solid listener intent worth monitoring

**Diluted but notable:** High On Me (SPM 39) has 54M+ streams already — saves have been absorbed into the mainstream listener base; no longer an early-signal name

**Tracks needing stream count recheck:** Dreams, Livin' It Up, You Don't Own Me, TESLA, Party Started — all have radio playlists seeded correctly, so SPM can be completed once streams become visible in Spotify popular tracks (typically after ~500K streams)
