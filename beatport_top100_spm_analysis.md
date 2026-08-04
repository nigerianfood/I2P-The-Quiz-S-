# SPM Analysis — Beatport Top 100 - Today
**Playlist:** Beatport Top 100 - Today (`0Q4JvzeT0q3FLsj5fqffMV`), owned by Symphoria
**Playlist Saves:** 20,280
**Tracks Analyzed:** 30 (rolling chart — tracklist changes daily)
**Tracks Scored:** 29
**Analysis Date:** 2026-07-02 (refresh of 2026-06-26 snapshot; stream gaps closed 2026-07-06 via mystreamcount API)

---

## Methodology

**SPM (Saves Per Million)** = Radio Playlist Saves ÷ Seed Track Streams × 1,000,000

For each track: title-only radio search (no artist name), seed verification via the `image_uri` path (`/radio/track/{trackID}/en`), save count from the radio playlist's Spotify page, stream count from the track's Spotify page — with the mystreamcount.com API (`POST /api/track/{id}/streams`) for tracks too new to appear in their artist's top-10 popular-tracks module.

**Methodology notes:**
- This is a rolling "today" chart; this refresh replaces the 2026-06-26 snapshot (preserved in git history).
- Two seeds were recovered from prior-run verified radio IDs (Movin' To The Sun, Chica) — radio seeds are stable once created; prior verified IDs are a legitimate recovery path when search's 5-result cap buries them.
- The seven previously "stream data unavailable" tracks were all resolved via the mystreamcount API (fetched 2026-07-06; saves are from 2026-07-02, so those seven SPMs mix dates by 4 days — a small conservative bias since streams grew in the interim).

**Scale context:** Current club records mid-promotion. Stream bases move fast — see the Shinjuku/Free Your Mind dilution finding — so SPM values here are snapshots of a moving target.

---

## SPM Rankings

| Rank | Track | Artist | SPM | Streams | Radio Saves | Signal Read |
|------|-------|--------|-----|---------|-------------|-------------|
| 1 | How Does It Feel | Dubdogz, FEZZO, Zaark | 536 | 5,957,183 | 3,193 | Extreme discovery heat — highest SPM measured |
| 2 | Movin' To The Sun | HUGEL, Imael Angel, Ultra Naté | 247 | 26,960,483 | 6,649 | Sustained heat at scale |
| 3 | La La Land | Green Velvet, MEDUZA, GENESI | 184 | 3,480,000 | 639 | High intent on rising record |
| 4 | Gotta Be Cool | Rafael | 176 | 141,817 | 25 | Fastest early-cycle ratio in set |
| 5 | Chica | Ben Evers, Najeh | 158 | 354,690 | 56 | Strong early-cycle ratio |
| 6 | Jamaican (Bam Bam) | HUGEL, SOLTO (FR) | 147 | 211,492,794 | 31,029 | Massive saves at massive scale |
| 7 | Talk To You (ft. 54 Ultra) | ANOTR, 54 Ultra | 130 | 115,577,820 | 15,018 | Club anthem with mass discovery pull |
| 8 | Shinjuku | Franky Rizardo | 118 | 18,278,222 | 2,151 | Diluting fast — was SPM 773 on June 26 |
| 9 | Warpdrive | LOR | 117 | 128,695 | 15 | Strong early ratio — LOR's best signal |
| 10 | Groovejet - not without friends Remix | Spiller, Sophie Ellis-Bextor | 114 | 844,687 | 96 | Classic-rework discovery signal |
| 11 | Free Your Mind | Prospa, Cloonee | 105 | 58,624,398 | 6,148 | Diluting — was SPM 479 on June 26 |
| 12 | On 2nite | Silva Bumpa | 92 | 9,980,839 | 923 | Healthy UKG crossover signal |
| 13 | On Lock | Dale Howard | 90 | 44,330 | 4 | Micro-base, ratio only indicative |
| 14 | So Good (feat. Kuuda) | CamelPhat, Josh Gigante, Kuuda | 81 | 1,488,598 | 121 | Solid early signal |
| 15 | Suavecito | Malo | 81 | 38,517,244 | 3,121 | 1972 catalog record riding the chart |
| 16 | Not Exactly - Rinzen Remix | deadmau5, Rinzen | 80 | 621,597 | 50 | Healthy remix discovery |
| 17 | Music Is The Answer - Edit | Jesús Fernández, Karl8 & Andrea Monta | 70 | 228,366 | 16 | Early, small but positive |
| 18 | I Never Knew | Adam Ten | 70 | 444,066 | 31 | Growing — was SPM 51 on June 26 |
| 19 | Trapped - Radio-Edit | Kolter | 66 | 4,102,127 | 269 | Steady minimal-house signal |
| 20 | Rhythm Of The House | Alex Culross, Ejeca | 62 | 400,820 | 25 | Early positive |
| 21 | My Life Is A Disco (In The Mix) | Mellizos, Mixmasters | 55 | 1,774,158 | 97 | Moderate |
| 22 | Push It | Disco Lines, Maesic, Mason | 51 | 1,263,109 | 64 | Moderate |
| 23 | Blow Your Mind | HILLS, ESSE | 46 | 64,681 | 3 | Micro-base early positive |
| 24 | Half There | LOR, Dominique | 44 | 249,809 | 11 | Weak-to-moderate |
| 25 | Kingdom Falling | LOR | 36 | 301,937 | 11 | Weak |
| 26 | Dreams | Prospa | 33 | 4,942,554 | 164 | Streams outpacing saves — early dilution |
| 27 | Can't Say Nah (feat. Benni Ola) | Odd Mob, Walker & Royce | 25 | 314,325 | 8 | Weak |
| 28 | Work It | SEBS | 21 | 282,332 | 6 | Weak |
| 29 | Shine | HUGEL, David Guetta, French Montana | 9 | 4,009,763 | 36 | Weakest — pop-fed streams, no discovery |

---

## Key Findings

**How Does It Feel (Dubdogz/FEZZO/Zaark) holds the highest SPM ever measured across all analyses: 536.** 3,193 saves on 6M streams. It was 543 on June 26; the ratio is essentially unchanged — saves compounding as fast as streams. This is what a record breaking out through active discovery (not playlist placement) looks like.

**The week-over-week comparison identifies which records are being force-fed by playlisting:**
- **Shinjuku: SPM 773 → 118.** Streams grew ~7x in six days while saves grew 5%. Editorial/algorithmic placement, not discovery.
- **Free Your Mind: 479 → 105.** Same pattern: streams ~5x, saves +6%.
- **How Does It Feel: 543 → 536.** Organic heat.
- **Movin' To The Sun: 235 → 247.** Saves outpacing streams — accelerating.

**The recovered stream data rewrote the top 10.** Gotta Be Cool (Rafael) enters at #4 (SPM 176 — 25 saves on just 142K streams) and Warpdrive (LOR) at #9 (SPM 117). Both were previously "stream data unavailable"; both turn out to be among the hottest early-cycle ratios in the set. LOR now spans the whole spectrum in one playlist: Warpdrive 117, Half There 44, Kingdom Falling 36.

**Shine (HUGEL/Guetta/French Montana) is the set's weakest signal (SPM 9)** — 4M streams driven by the pop-star billing, only 36 radio saves. The same HUGEL who tops the absolute-saves table with Jamaican (Bam Bam)'s 31,029 saves (a then-record, since eclipsed by Everybody Wants To Rule The World's 84,186). Star power fills streams; it doesn't create discovery intent.

**Dreams (Prospa) at SPM 33 confirms the dilution watch was right:** its saves grew 109 → 164 while streams hit 4.9M — the streams are outrunning the intent, mirroring its label-mate Free Your Mind.

**Jamaican (Bam Bam), Talk To You, and Suavecito** hold their reads from the main snapshot: mass-scale discovery pull for the first two, and genuinely healthy intent on a 53-year-old catalog record for the third.

---

## Tracks Without Radio Seed Data (1 track)

| # | Track | Reason |
|---|-------|--------|
| 10 | To The Rhythm (LOR) | No seed match in top 5 results (also unseeded on June 26) |

---

## Raw Data Reference

See `beatport_top100_spm_analysis.csv` for full worksheet.

**Stream sources:** Spotify track pages; mystreamcount.com API for tracks 9, 15, 23, 26, 27, 28, 29 (fetched 2026-07-06).
**Save counts:** Fetched directly from each radio playlist's Spotify page (2026-07-02).
**Prior snapshot:** 2026-06-26 data preserved in git history.
