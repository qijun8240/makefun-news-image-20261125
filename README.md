# World news of 25 November 2026, in one image

Entry for the make.fun bounty
[Sum up 25 November's world news in one image](https://make.fun/bounty/news-image-20261125)
($100, 50 prizes).

`main.ts` (Node 22, standard library only) copies the pre-rendered
`entry.png` beside it to `/output/entry.png`, after checking it is a
PNG of at most 1 MiB and 1024×1024 pixels. `render.py` draws the
image with PIL: a newspaper front page with the day's nine biggest
stories, from the Strait of Hormuz tanker mines to the COP31 talks
ending without a deal.

Run it:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
