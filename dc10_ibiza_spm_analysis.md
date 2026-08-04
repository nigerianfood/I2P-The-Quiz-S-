# DC10 IBIZA — Official Playlist 2026: SPM (Saves-Per-Million) Analysis

**Playlist:** [DC10 IBIZA Official Playlist 2026](https://open.spotify.com/playlist/4c6FAwRlvdJxCvR75QoBHE) · `4c6FAwRlvdJxCvR75QoBHE`
**Tracks analysed:** 30 (29 on Spotify + 1 not available) · **Scored:** 24 · **Without a dedicated radio:** 5 · **Not on Spotify:** 1
**Metric:** `SPM = Radio-playlist Saves ÷ Seed-track Streams × 1,000,000`
**Seed rule:** each winning radio's artwork was confirmed to point at `/radio/track/{our-track-id}/en` (title-only search, no artist appended). Stream totals via mystreamcount (as of 2026-08-02); radio saves via each radio's Spotify page.

SPM is a **listener-intent** signal: it isolates how strongly a track drives *active discovery* (people saving its auto-generated radio) relative to raw popularity. A high SPM means a track punches far above its stream weight as a "take me deeper" trigger.

---

## Rankings by SPM (higher = stronger discovery pull per stream)

| # | Track | Artist | Streams | Radio saves | SPM |
|---:|---|---|---:|---:|---:|
| — | **Asa** ⚠️ | Âme | 1,485 | 332 | **223,569** |
| 1 | Raw | Hardt Antoine | 297,960 | 120 | 402.7 |
| 2 | Science Fiction | Brunello | 1,690,014 | 546 | 323.1 |
| 3 | Positive | Jamback | 23,183,443 | 3,715 | 160.2 |
| 4 | Baby Run | Jimi Jules | 975,630 | 142 | 145.6 |
| 5 | Too Much Pressure | MAXI MERAKI, Derun, The Anahit | 235,527 | 34 | 144.4 |
| 6 | Drums Are Dangerous | Eden Burns, Christopher Tubbs | 99,519 | 11 | 110.5 |
| 7 | UH HUH | Luch | 612,697 | 56 | 91.4 |
| 8 | Free Your Mind | Prospa, Cloonee, Sybil | 90,664,358 | 8,150 | 89.9 |
| 9 | Blue Zone | Thimble | 97,958 | 8 | 81.7 |
| 10 | Mobile Groove | Michael Bibi | 392,117 | 30 | 76.5 |
| 11 | Trippy Yeah | Jimi Jules, Black Coffee | 14,317,787 | 1,016 | 71.0 |
| 12 | Profil (Josh Baker Remix) | Bonafique, Yuvèe, Josh Baker | 550,941 | 39 | 70.8 |
| 13 | Can't Decide | Max Dean, Luke Dean, Locky | 76,615,633 | 4,253 | 55.5 |
| 14 | Baby | Prospa, Murda Beatz | 20,574,722 | 910 | 44.2 |
| 15 | Reveries | Mind Against | 1,113,785 | 48 | 43.1 |
| 16 | Dirty Cash (Money Talks) | PAWSA, The Adventures Of Stevie V | 259,720,468 | 10,969 | 42.2 |
| 17 | Don't Stop | Prospa | 37,494,561 | 1,313 | 35.0 |
| 18 | Luxo | Trikk | 1,050,777 | 33 | 31.4 |
| 19 | Crazy For It | Rampa, Adam Port, &ME, Boys Noize, Vinson, Keinemusik | 53,752,502 | 1,283 | 23.9 |
| 20 | Leave A Message | Josh Baker, Poppy Wright, Trick Shady | 10,138,504 | 237 | 23.4 |
| 21 | Talk To You (ft. 54 Ultra) † | ANOTR, 54 Ultra | 167,601,442 | 3,388 | 20.2 |
| 22 | AYEEE | MPINTA | 266,634 | 2 | 7.5 |
| 23 | Sound of You | ANOTR, TEED | 5,868,721 | 36 | 6.1 |

⚠️ **Asa (Âme)** is listed out of rank as an anomaly — see below.
† **Talk To You** seeds a duplicate release ID of the same song; the seed was confirmed by radio description in the earlier euro-summer run (`DUP_SEED`).

---

## Key findings

- **Âme — "Asa" is the anomaly of the playlist.** Its seed-verified radio has **332 saves against only 1,485 streams** — a fresh 2026 release (stream total dated 2026-08-02) that almost nobody has streamed yet, but whose radio is already being actively saved. Mathematically this yields an SPM of ~223,600, which is a *denominator artifact* (tiny stream base), so it is not comparable to the rest of the field. Directionally, though, it is the single **purest pre-discovery signal** on the list: a brand-new cut being bookmarked as a doorway before it has any popularity. Watch this one.

- **Ignoring the Asa outlier, the genuine discovery leaders are the mid-tier club records, not the hits.** Hardt Antoine's **"Raw" (403)** and Brunello's **"Science Fiction" (323)** top the field: modest stream counts (~300k / ~1.7M) but disproportionately saved radios. These are the tracks doing the "gateway" work — people hear them in the set and immediately want more of that lane.

- **The famous names underperform on intent.** The playlist's biggest streamers convert *poorly* into discovery: Dirty Cash (260M streams → SPM 42), Talk To You (168M → 20), Crazy For It (54M → 24), Sound of You (5.9M → 6). They're recognised sing-along/peak-time records, so listeners already "have" them — the radio adds little. High streams, low intent.

- **Jamback — "Positive" (SPM 160) is the standout that scales.** Unlike Raw/Science Fiction, it carries *both* real popularity (23M streams) **and** a heavily-saved radio (3,715). It's the rare track that's simultaneously a hit and a discovery engine — the best "safe bet" signal in the set.

- **Absolute radio-save volume ≠ intent.** Free Your Mind (8,150 saves) and Dirty Cash (10,969 saves) have the most total radio-followers, but because their seed tracks are already massive, their *per-stream* pull is middling (90 and 42). SPM correctly separates "big because the song is big" from "big because the song makes people dig."

- **Tiny-but-mighty cluster.** Drums Are Dangerous (SPM 111 off 11 saves) and Blue Zone (82 off 8 saves) show the same pattern as Asa in miniature — very small, very fresh underground cuts whose few listeners are highly intent-driven. Fragile numbers, but genuine.

---

## Tracks without a dedicated radio (5)

These titles are real and on Spotify, but Spotify did **not** generate an auto-radio seeded by *our* specific track ID — usually because the title collides with a far more popular namesake that owns the radio, or the release is too new/niche to have one. No SPM can be computed.

| # | Track | Artist | Why |
|---:|---|---|---|
| 14 | Awake | ALADAG | Common one-word title; radios seed other "Awake" releases |
| 16 | Sing It Back | Hardt Antoine | Radio owned by the classic Moloko "Sing It Back" and its remixes |
| 18 | Odyssey | Ede | Common title; radios seed other "Odyssey" tracks |
| 21 | Home | Solomun | Extremely common title; no radio seeded by this Solomun release |
| 30 | NO MORE | MPINTA | No auto-radio seeded by this release ID |

## Not available on Spotify (1)

| # | Track | Artist |
|---:|---|---|
| 7 | Max (Tripolism Remix) | Kenton Slash Demon, Tripolism |

---

## Method notes

- **Title-only radio search.** Every radio was found with the query `"{Exact Title} Radio playlist"` — the artist name is never appended (doing so suppresses Spotify's auto-radio and returns artist-radios instead).
- **Seed verification.** A result only counts when its artwork URL is `…/radio/track/{our-track-id}/en`. Where the top result seeded a *different* release of the same song (Talk To You), it was accepted only after confirming the radio's description names the correct artist — flagged `DUP_SEED`.
- **Data currency.** Streams are cumulative totals from mystreamcount (2026-08-02). Radio saves are live counts from each radio's public Spotify page and drift over time.
- **Outlier handling.** Asa is reported but excluded from ranked comparison because its sub-2k stream denominator makes SPM non-comparable.

*Companion data: `dc10_ibiza_spm_analysis.csv`.*
