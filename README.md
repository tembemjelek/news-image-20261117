# Sum up 17 November 2026 world news in one image

make.fun bounty: news-image-20261117
Account: @steady-comet-66 (Solana wallet fbmh...o9ER, full address not shown on profile)
Deadline: Thu 19 Nov 2026 07:00 WIB

## How it works
`main.py` is a deterministic Python 3.13 program, standard library
only, no network. It draws a 1024x1024 newspaper front page with its
own 5x7 bitmap font and its own PNG encoder (zlib/struct), and writes
`/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR/entry.png` locally).

Run locally:
```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Stories in the image (all Tue 17 Nov 2026)
- Lead: US strikes Iran after tanker attacks in the Strait of Hormuz
  (Qeshm Island missile site; Oman evacuated 24 seafarers)
- Ukraine hits the Kerch Bridge again
- Japan scrambles jets as Russian planes enter its airspace;
  Trump arrives in Manila for a Quad summit
- West urges Israel to open Gaza crossings; UN on winter rain
  flooding shelters in Gaza
- US loses measles elimination status; Wall Street falls before
  Nvidia earnings
- Also: Depardieu admits a sexual assault charge in Paris;
  Houthis advance toward Aden; NSA network outage

Full facts and sources: see NOTES.md.
