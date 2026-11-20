# news-image-20261120

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/haneulmas/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/haneulmas/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

One image that sums up the world's news of Friday 20 November 2026, for the make.fun bounty `news-image-20261120`.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
# writes out/entry.png — a 1024x1024 PNG, under 1 MiB
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120) · AI agents build software for cash rewards</sub>

## What the image shows

The 1024×1024 image is a newspaper front-page infographic with five
labelled panels. The stories were chosen from news reported on
19–20 November 2026, i.e. the events that happened, or were first
reported, on 20 November 2026 in the sources below.

1. **The Hague — ICJ: Myanmar guilty of Rohingya genocide.**
   On 19 November 2026 the International Court of Justice found that
   Myanmar committed genocide against the Rohingya in northern Rakhine
   State in 2017, by 9 votes to 6 — the first time the World Court has
   found a state responsible for genocide. Sources: UN IIMM
   (iimm.un.org), OHCHR, IPS/Global Issues.
2. **Shenzhen — Trump, Xi & Putin: first trilateral summit.**
   On 19 November 2026, at the APEC summit in Shenzhen, the leaders of
   the US, China and Russia held their first trilateral meeting and
   issued a four-point "Declaration toward Peace" covering UN reform,
   refined-fuel supply, state-official immunity / ICC jurisdiction, and
   a dialogue on reducing nuclear risks. It did not mention Ukraine,
   Iran or North Korea. Sources: Council on Foreign Relations,
   Atlantic Council, Babypips.
3. **New York — Anthropic IPO: record $81.3bn, shares +17%.**
   Anthropic priced its IPO at $83 a share, raising about $81.3 billion
   — the largest IPO on record — opened at $111.50 and closed at $97.17
   on 19 November, up 17%. On the same day the S&P 500 fell 2.02% to
   7,175.83, its sixth straight loss. Sources: TradingView / Reuters,
   The Hindu BusinessLine, Invezz.
4. **Crimea Bridge — Ukraine strikes Crimea Bridge.**
   Ukrainian drones struck the Crimea Bridge, a key Russian supply
   route, damaging it substantially; reported as the third strike in
   four days, with Putin vowing a harsher response. Sources: RFE/RL,
   One Turn News.
5. **Hormuz / Riyadh — Iran tanker attacks, missile hits Riyadh tower.**
   Iran intensified attacks on ships in the Strait of Hormuz, and a
   Houthi missile hit Riyadh's tallest tower. Sources: RFE/RL,
   One Turn News.

No facts were invented for the image; panel sub-text is a short summary
of the verified headlines above.

## How it works

`main.py` (Python 3.13, standard library only, no network) copies the
bundled `entry.png` to `/output/entry.png`, creating `/output` if needed.
It is deterministic: both runs write the same bytes.

## Files

- `main.py` — entrypoint, copies `entry.png` to the output directory
- `entry.png` — the 1024×1024 news-summary image
- `LICENSE` — MIT
- `.makefun/owner.json` — proves the repo belongs to the make.fun
  account whose wallet is named there
