# SPM Analysis — This Is BLOND:ISH
**Playlist:** This Is BLOND:ISH (`37i9dQZF1DZ06evO3SHkVW`)
**Playlist Saves:** 9,188
**Tracks Analyzed:** 30
**Tracks Scored:** 20
**Date:** 2026-06-28 (stream gaps for tracks 19 and 27 closed 2026-07-06 via mystreamcount API)

---

## Methodology

**SPM (Saves Per Million)** = Radio Playlist Saves ÷ Seed Track Streams × 1,000,000

For each track, I searched Spotify for its title-only Radio playlist (e.g., "It Starts Now Radio"), verified the seed track via the `image_uri` path (`/radio/track/{trackID}/en`), fetched the radio playlist's save count, and fetched the track's total stream count from kworb's Spotify songs page.

**Key methodology note:** All searches use title-only queries (no artist name appended). Including the artist name suppresses auto-generated radio playlists from appearing in results. This was confirmed by systematically retrying all originally "no seed match" tracks with pure title-only queries — 11 additional seeds were found this way.

**Scale context:** BLOND:ISH is a deep underground artist. Tracks range from 327K streams (Lovers On The Dancefloor) to 152M streams (Never Walk Alone). SPM values are structurally higher than catalog artists like Coldplay because denominators are orders of magnitude smaller. Scores here should be read within the underground electronic context.

---

## SPM Rankings

| Rank | Track | Artist | SPM | Streams | Radio Saves | Signal Read |
|------|-------|--------|-----|---------|-------------|-------------|
| 1 | It Starts Now | BLOND:ISH | 139 | 5,646,913 | 785 | Strongest discovery signal in set |
| 2 | Lovers On The Dancefloor | BLOND:ISH | 119 | 326,633 | 39 | Extreme ratio on ultra-low stream base |
| 3 | In Da Jungle | BLOND:ISH | 78 | 499,479 | 39 | Very high ratio on micro-stream base |
| 4 | Don't Cha | BLOND:ISH | 62 | 2,541,901 | 158 | Strong signal on small-to-mid catalog track |
| 5 | Natural Blues | BLOND:ISH | 51 | 8,543,954 | 439 | Active underground discovery engine |
| 6 | nothin lasts 4ever | BLOND:ISH | 45 | 950,294 | 43 | High ratio on micro-stream base |
| 7 | Wizard of Love - Radio Edit | BLOND:ISH | 36 | 31,037,235 | 1,122 | Highest absolute saves in set |
| 8 | Call My Name | BLOND:ISH | 33 | 7,694,437 | 253 | Solid mid-catalog discovery |
| 9 | Es un secreto | BLOND:ISH | 32 | 14,277,382 | 450 | Strong underground discovery signal |
| 10 | Never Walk Alone | BLOND:ISH | 26 | 152,117,095 | 4,014 | Highest absolute saves; diluted by massive stream count |
| 11 | Kimbe (feat. Tay Iwar) | BLOND:ISH | 21 | 1,272,477 | 27 | Small but coherent signal |
| 12 | Fortnight (feat. Post Malone) - BLOND:ISH Remix | BLOND:ISH | 20 | 42,411,567 | 830 | Cross-fandom streams compress ratio |
| 13 | Self Love | BLOND:ISH | 14 | 13,557,786 | 194 | Moderate catalog engagement |
| 14 | Higher - Notre Dame Remix | BLOND:ISH | 12 | 4,554,339 | 54 | Low but present signal |
| 15 | Sorry (with Madonna) - Eran Hersh and Darmon Remix | BLOND:ISH | 11 | 1,285,049 | 14 | Minimal active discovery |
| 16 | Shout It Out | BLOND:ISH | 10 | 7,344,656 | 75 | Modest catalog activity |
| 17 | Garden Of 3Den - Edit | BLOND:ISH | 8 | 4,740,264 | 39 | Low catalog signal |
| 18 | Can't Let You Go | BLOND:ISH | 6 | 6,182,001 | 37 | Weak signal |
| 19 | Different Way - ARTBAT Remix | BLOND:ISH | 5 | 6,590,324 | 35 | Near-floor signal |
| 20 | Sorry (with Madonna) | BLOND:ISH | <1 | 53,769,883 | 2 | Effectively zero discovery intent |

---

## Key Findings

**It Starts Now leads at SPM 139 — by far the strongest discovery signal in the set.** On 5.6M streams, it pulls 785 radio saves: one save per every 7,193 streams. For an underground track, this is an extraordinary listener intent signal.

**Lovers On The Dancefloor (SPM 119) has an extreme ratio, but the base is very small.** Only 327K lifetime streams and 39 radio saves — the ratio is striking but fragile. A small numerator and small denominator can produce a high quotient that doesn't tell you much about catalog weight.

**In Da Jungle (SPM 78) is the clearest micro-catalog discovery signal.** 499K streams and 39 saves. This is structurally similar to Lovers On The Dancefloor: the absolute numbers are small, but the intent ratio is genuinely elevated on a verified seed.

**Don't Cha (SPM 62) is a meaningful surprise.** 158 saves on 2.5M streams is a real signal — not micro-catalog noise. This track is pulling discovery-intent listeners at a rate that implies active underground circulation.

**Natural Blues (SPM 51) remains the most structurally reliable data point at scale.** 8.5M streams with 439 saves — meaningful on both axes. The BLOND:ISH take on the Moby catalog has consistent organic discovery activity.

**nothin lasts 4ever (SPM 45) is a standout in the micro-catalog tier.** 950K streams and 43 saves. The ratio is high because the base is tiny, but the saves count is real. Listeners who find this track through radio are saving it at nearly the same rate as In Da Jungle.

**Wizard of Love - Radio Edit has the most absolute radio saves in the set (1,122) but ranks 7th at SPM 36.** The 31M stream denominator compresses the ratio. Still a strong catalog performer by any measure.

**Es un secreto (SPM 32) has surprisingly strong discovery activity.** 450 saves on 14.3M streams — the third-highest absolute save count in the set. For a non-English language track on an underground artist, this is a notable signal.

**Never Walk Alone (SPM 26) has the highest absolute radio saves of any track (4,014), but its 152M streams push it down the SPM rankings.** The saves are real — it is the most-saved radio in the set — but the massive denominator (driven by the track's breakthrough scale) dilutes the ratio.

**Kimbe feat. Tay Iwar (SPM 21) is a quiet positive signal.** 27 saves on 1.3M streams — small both ways, but the ratio holds. Coherent discovery intent from a niche catalog track.

**Fortnight BLOND:ISH Remix (SPM 20) has 830 absolute saves but ranks 11th.** Its 42.4M streams are largely driven by Taylor Swift fans discovering the remix, not BLOND:ISH discovery-intent listeners — which structurally suppresses the SPM despite healthy raw numbers.

**Self Love (SPM 14) and Higher - Notre Dame Remix (SPM 12) are catalog fillers.** Modest signals, not active discovery engines.

**Shout It Out (SPM 10), Can't Let You Go (SPM 6), and Different Way - ARTBAT Remix (SPM 5) are near-floor.** Verified radio playlists exist and are seeded correctly, but listener intent is minimal.

**Sorry (with Madonna) BLOND:ISH original version (SPM <1) is effectively zero.** The radio playlist exists and seeds to the correct BLOND:ISH track version, but with only 2 saves on 53.8M streams, there is no discovery intent signal. This may reflect that the radio algorithm draws listeners from the massive Madonna stream base who are not BLOND:ISH discovery-seekers.

**Call My Name and Garden Of 3Den - Edit are now scored** (stream counts recovered via the mystreamcount API on 2026-07-06). Call My Name lands at SPM 33 — the "meaningful signal if confirmed" hypothesis held: 253 saves on 7.7M streams is solid mid-catalog discovery. Garden Of 3Den - Edit comes in at SPM 8, low catalog activity.

---

## Tracks Without Radio Seed Data (10 tracks)

These tracks had no matching Spotify radio playlist in the top 5 results, the verified seed track ID did not match the playlist version, or the version type does not generate its own radio:

| # | Track | Reason |
|---|-------|--------|
| 3 | Sete | Radio playlist seeds to different track version (`6YvEIuaWAkuLZMI1a2Qy9x`), not playlist version |
| 10 | The Cure | "The Cure" band radio results dominate search |
| 15 | Remember Me | No seed match in top 5 results |
| 16 | Hold Tight (feat. Darla Jade) - Extended Mix | Extended Mix version does not seed radio |
| 18 | Tra Tra | No seed match in top 5 results |
| 20 | No One | "No One" (Alicia Keys) radio results dominate search |
| 23 | Waves (feat. Grace Tither) | No seed match in top 5 results |
| 24 | GOAT | No seed match in top 5 results |
| 28 | Voyeur - Jay Shepheard & Martin Dawson Remix | Remix version does not seed radio in top 5 |
| 29 | Heartbreaker | No seed match in top 5 results |

---

## Raw Data Reference

See `blondish_this_is_spm_analysis.csv` for full worksheet.

**Stream sources:** kworb.net Spotify songs page (all-time totals for BLOND:ISH artist ID `6zsJjoCtL1WByG0VsuFWzR`); mystreamcount.com API for tracks 19 and 27 (fetched 2026-07-06).
**Save counts:** Fetched directly from each radio playlist's Spotify page.
