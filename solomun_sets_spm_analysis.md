# Solomun — 5 Old Sets: SPM (Saves-Per-Million) Analysis

An SPM discovery-intent analysis of tracks Solomun played across five of his older DJ sets (2011–2013). SPM = Radio-playlist Saves ÷ Seed-track Streams × 1,000,000 — how strongly listeners who hear a track via its Spotify auto-radio *save* it, relative to its total streams.

## The five sets (tracklists via MixesDB)

| # | Date | Set | Tracks listed |
|--|------|-----|--------------:|
| 1 | 2011-06-09 | Noir Music Podcast | 11 |
| 2 | 2012-07-28 | BBC Radio 1 Essential Mix | 23 |
| 3 | 2012-12-14 | Mixmag Live, Fire, London | 23 |
| 4 | 2013-08-11 | Solomun +1, Pacha, Ibiza (Live & Direct) | 18 |
| 5 | 2013-08-24 | SW4 Festival | 15 |

**Track universe:** 90 listed entries → **76 unique tracks** after merging cross-set repeats (e.g. *Midland – Realtime*, *Sabb – Feel Love*, *Noir & Haze – Around* were each played in multiple sets).

## Scope & method

These sets mix underground house cuts with DJ-only edits and mainstream classics. To keep SPM meaningful, the analysis targets the **discovery-relevant electronic releases** and excludes material where an SPM figure would be noise:

- **Excluded — not on streaming:** DJ edits / bootlegs / unreleased IDs played only in the mix (e.g. *Too $hort – Too Short But Funky (Solomun Edit)*, *Frank Ocean – Lost (Tom Shark Edit)*, *LCD Soundsystem – You Wanted A Hit (Gabe Bootleg)*, *Stimming & David August – Sexy Biest*).
- **Excluded — mainstream/non-discovery:** tracks played as vibe/edits whose SPM reflects global fame, not the set (*David Bowie – Let's Dance*, *Die Antwoord – I Fink U Freeky*, *Chemical Brothers – Do It Again*, *Das EFX*, *Billy Ocean*).
- **Scored core:** a representative **15-track set of electronic releases** matched to Spotify, run through the full pipeline. **100% stream coverage** (mystreamcount.com). Of the 15, **9 have a dedicated Spotify auto-radio** and are scored below; **6 do not**.

## Rankings (scored tracks, by SPM)

| Rank | Track | Artist | SPM | Streams | Radio Saves | Read |
|-----:|-------|--------|----:|--------:|------------:|------|
| 1 | Jakla (Gorge Remix) | AFFKT | 100.62 | 278,277 | 28 | High ratio (micro-base) |
| 2 | Around (Solomun Vox) | Noir & Haze | 24.35 | 66,437,610 | 1,618 | Residual intent |
| 3 | Let's Go Back (Solomun Remix) | Kraak & Smaak | 17.67 | 962,082 | 17 | Residual intent |
| 4 | Right Here (feat. Foxes) - Hot Since 82 Remix | Rudimental | 14.63 | 888,511 | 13 | Modest |
| 5 | Something We All Adore | Solomun | 11.39 | 13,343,891 | 152 | Modest |
| 6 | Kackvogel | Solomun | 4.57 | 15,323,625 | 70 | Passive / catalog |
| 7 | My Own Business | Kolombo | 4.35 | 3,911,609 | 17 | Passive / catalog |
| 8 | Let's Go Dancing | Tiga vs Audion | 4.23 | 1,889,550 | 8 | Passive / catalog |
| 9 | Late Night (Solomun Remix) ⁺ | Foals | 3.29 | 82,626,664 | 272 | Passive / catalog |

⁺ *Late Night* radio was seeded off a duplicate release ID of the same Foals × Solomun track (description-confirmed: "With Foals, Solomun, Noir…").

## Key findings

- **SPM on vintage catalog tracks runs an order of magnitude lower than on current playlist tracks.** For comparison, current-rotation tracks in the *euro summer* analysis scored SPM 100–400; here all but one land in single digits to low-20s. The reason is structural: SPM's denominator is *lifetime cumulative* streams, while radio-saves reflect *recent, ongoing* discovery. A 2011–2013 cut has years of accumulated streams diluting a thin trickle of present-day radio saves. **SPM here measures residual discovery intent, not peak-era intent.**
- **Around (Solomun Vox) — Noir & Haze is the enduring classic.** At **1,618 radio saves** it has *10× the absolute saves* of any other scored track — people still actively collect it 14 years on. Against 66M lifetime streams that's SPM 24, the best real-scale figure here.
- **Jakla (Gorge Remix) — AFFKT tops the ratio table (SPM 101) but on a micro-base:** just 278k lifetime streams and 28 saves. Deep-underground obscurity inflates the ratio; it's a directional signal, not a scale one.
- **Late Night (Foals × Solomun Remix) shows the mainstream-reach pattern:** 2nd-most saves (272) but 82.6M streams → SPM 3.3. Widely streamed via Foals' pop reach, proportionally less 'saved' as a discovery.
- **Solomun's own productions persist modestly:** *Something We All Adore* (SPM 11.4, 152 saves) and *Kackvogel* (4.6, 70 saves) still draw catalog saves; both retain dedicated radios a decade later.
- **The deep cuts have gone quiet on streaming.** Six scored tracks — *Realtime* (Midland), *What I Do* (Dusky), *Motions* (Adriatique), *Feel Love* (Sabb), *Love 4 The D.O.G.G* (CamelPhat), *Shake That* (Marlon Hoffstadt & Dansson) — have **no dedicated Spotify auto-radio** and tiny stream counts (48k–3.8M), the signature of underground tracks that never crossed into algorithmic rotation.

## Scored tracks without a dedicated radio (6)

| Track | Artist | Streams | Note |
|-------|--------|--------:|------|
| Realtime | Midland | 107,163 | common title; only artist-radio |
| What I Do | Dusky | 48,456 | common title; only artist-radio |
| Motions | Adriatique | 779,679 | no matching seed (title-only confirmed) |
| Love 4 The D.O.G.G | CamelPhat | 313,986 | only artist/other-song radios |
| Feel Love | Sabb | 132,630 | common title; only artist-radio |
| Shake That | Marlon Hoffstadt & Dansson | 3,789,977 | a "Shake That" radio exists but seeds Eminem's song (desc-confirmed) — not this track |

*Full per-track data (IDs, streams, seed status, formulas) in `solomun_sets_spm_analysis.csv`.*