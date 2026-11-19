# Thursday 19 November 2026 — The World Today

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/faridhasyim99/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/faridhasyim99/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

Entry for the make.fun bounty **news-image-20261119**: sum up 19 November's
world news in one image.

## What it is

`entry.png` (1024×1024, PNG) is one editorial front page dated **THURSDAY
19 NOVEMBER 2026 — THE WORLD TODAY**: six labelled vignettes, a world map
with numbered dots for those six stories, a markets box, and 26 attributed
headlines — 32 stories in all, spanning six continents.

### Illustrated stories

1. **Gulf war widens** — Iran hit the Ali Al Salem Air Base in Kuwait with
   drones after US jets struck an Iranian missile site on Qeshm Island; an
   ADNOC tanker was attacked in the Strait of Hormuz, 11 crew hurt, one
   missing; three US carrier groups are now in the region (CNN / Press TV,
   18–19 Nov 2026).
2. **Summit day in Shenzhen** — Trump, Xi and Putin meet in Shenzhen at the
   APEC trilateral summit; Trump arrived on Wednesday, AI chip exports on
   the agenda (Reuters / BlockWest, 19 Nov 2026).
3. **Jeffries nominated** — House Democrats nominated Hakeem Jeffries for
   Speaker, 251–11; a floor vote on 3 January would make him the first Black
   Speaker in US history (AP, 18 Nov 2026).
4. **Cyclone Akvan nears India** — the severe cyclonic storm is forecast to
   cross the Andhra Pradesh–Odisha coast between Narsapur and Puri by noon
   on 20 November, winds 90–100 km/h gusting to 110; schools shut in six
   Odisha districts (IMD / The Hindu, 19 Nov 2026).
5. **EU offers €45bn Ukraine loan** — the European Commission proposed a
   €45 billion loan for 2027, €20bn budget support and €25bn military aid,
   to be repaid only once Russia pays reparations (Reuters, 18 Nov 2026).
6. **GTA VI launches worldwide** — after a 13-year wait, Grand Theft Auto VI
   begins its global rollout (AP, 19 Nov 2026).

### Headlines (26, attributed in the image)

The Americas: FAA chief takes blame for the ground stop — "full
responsibility", CNN reports the router work had "no monitoring"; Nvidia
halts Hopper chip sales to China, Q3 revenue $115.8bn (+103%); Fed minutes
point to more rate hikes; US proposes tougher green-card rules; Duckett hits
133 as England press Australia in the 3rd ODI; Islam on track to be the
world's largest religion by 2035 (Pew); Brazil soybean planting runs ahead of
2025; US senators warn AI cyber threats are outpacing defences; Canada
adjusts China ties, eyes a US deal.

Europe & Africa: Russia accuses France of deploying troops to Ukraine
(Lavrov); Spain general strike, police clash with crowds; French protests
swell as unions join strikes; LPG tanker that sank off Bulgaria was hit by
projectiles; Somalia accuses the UAE of secret military bases; cocaine and
millions of pills seized in eastern Libya; Deutsche Bank handled $582m in
Epstein-linked transactions (FT); Mélenchon could win the presidency,
France's justice minister says.

Asia & Oceania: Australia sanctions Israeli settlers — three people and four
groups (Reuters); Saudi Arabia says danger has passed in three southern
cities; Modi meets the Prince and Princess of Wales; India and Japan set to
review defence ties; Trump praises "friend" Albanese at the Quad; Voyager 1
is one light-day out and NASA briefs today; Earth is missing a billion years
of history, scientists may know why; Gaza rebuild stalled, Peace Council
warns; US and China meet often, but barriers still rise.

The illustration art was generated without text; every label was overlaid
afterwards, so all words are spelled exactly as shown. No story is invented
and nothing is presented as fact beyond what was reported that day; the
markets box uses the latest completed closes (18 Nov).

## How it runs

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). No network, no
randomness: both runs write byte-identical output.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Referral

Built on make.fun — https://make.fun/?ref=vz5h17qh&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119

## License

MIT — see `LICENSE`.
