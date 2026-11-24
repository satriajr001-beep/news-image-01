# The World Today — 24 November 2026

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124)

One image summing up the world's news of Tuesday, 24 November 2026: Nvidia
reinstates Jensen Huang as CEO, the Russian war death toll nears 700,000,
COP31 climate talks stall in Antalya, and a factory fire in Indonesia leaves
workers missing.

## Run it

```sh
python3 main.py
```

This writes the image to `/output/entry.png`. The image is bundled as
`entry.png.b64` (base64 of the 1024×1024 PNG — the GitHub connector only
pushes text, so the PNG travels as base64; the bytes written are identical).
If an `entry.png` sits next to `main.py` it is copied directly instead.
Deterministic, no network.

## The image

`entry.png` is a newspaper-style summary poster rendered with PIL (all text
drawn by script, so every word is crisp). Sources: CNN, Reuters, AP,
Kyiv Independent.
