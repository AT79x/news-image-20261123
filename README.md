[![news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/at79x/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/at79x/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123)

# news-image-20261123 — The World in One Day

A program that draws one image summing up the world news of **Monday 23
November 2026**, as an entry for the [make.fun bounty "Sum up 23
November's world news in one image"](https://make.fun/bounty/news-image-20261123).

`main.py` (Python 3, standard library only, no network) draws the image
from scratch and writes it to `$MAKEFUN_OUTPUT_DIR/entry.png`. Two runs
produce byte-identical output.

The dark world map look AT chose for the 20/21 November entries: a dark
ocean map with sage-teal continents and seven numbered markers, one HERO
story below it (COP31 ends without a deal, on a dark navy panel with a
gold frame) and a numbered grid of six story cards, each with its own
accent colour, a small hand-drawn illustration band, a region tag and a
source line.

## The seven stories (all verified against Reuters / AP / BBC and others, 23 Nov 2026)

1. **Antalya — COP31 ends without a deal.** Two days of overtime, no
   agreement; the EU and about 130 parties reject a text with no fossil
   fuels in it.
2. **Benghazi — Russian warship sinks.** Corvette Merkury goes down at
   the naval base; a suspected Ukrainian sea drone is blamed.
3. **Dymer — strike kills 10; boy, 7, pulled alive.** Russian strike
   hits flats north of Kyiv; rescuers pull a 7-year-old from the rubble.
4. **Washington — Democrats win biggest House win since 1992.** At
   least 258 seats after a North Carolina recount flip.
5. **Tokyo — Nikkei dives 5%.** AI sell-off spreads across Asia; Hong
   Kong hits a 19-month low.
6. **Strait of Hormuz — tankers ablaze.** Two tankers hit mines and
   catch fire; Trump threatens to sink Iranian vessels.
7. **Seoul — exports top $1 trillion.** AI chip demand drives a record
   year; fourth economy ever to pass $1tn.

See [NEWS.md](NEWS.md) for the sources behind each story.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Output: `out/entry.png` — 1024x1024 PNG, about 31 KB.
