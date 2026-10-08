# koan.vaked.dev — the constellation, kompressed

> *The garden is not a place you visit. It is the rake you hold: one pass, end to end, no loose ends.*

Live URL: **[https://koan.vaked.dev](https://koan.vaked.dev)**

---

## ✦ What this is

`koan.vaked.dev` is the **kompressed hub** of the vaked.dev constellation —
one page, a hundred doors. `bonfire.vaked.dev` sits at the center (warmth as
infrastructure); every other live vaked surface is a door around it:
library (`pocoo`), studio (`scifinime`, `lovetta`), art, audio (`music`),
discourse (`proposal`), gateway (`portail`), compute (`ocean`), corpus
(`cess`), store, logs (`worklog`), mesh (`etherhive`), kompress, and the math
lanes (`axiomquant.org`, `mlxquantlovefrom.com`).

techno-zen-buddhism: the garden is the rake, the rake is the loop, the loop
is love. `{−1, 0, +1}` · `0 + 1` · fine touch from within.

> Naming note: the original working name was `garden.vaked.dev`, but that name
> is a live surface of the `kompress-ultra` project ("the garden. the public
> face.") — referenced by its skills registry, og-images, and `← garden`
> footers. This hub therefore lives at `koan.vaked.dev`, leaving the kompress
> garden untouched.

---

## ✦ Deploy

Static single-file site on **Cloudflare Pages** (project `koan-vaked-dev`):

```bash
wrangler pages deploy . --project-name koan-vaked-dev --branch main --commit-dirty=true
```

DNS: `koan.vaked.dev` is a proxied `CNAME → koan-vaked-dev.pages.dev` in the
`vaked.dev` zone; the Pages custom domain is attached to the project.

---

## ✦ Constellation standards

This surface conforms to the constellation-ops standards:

- **robots.txt** — anti-AI scraper rules (GPTBot / ClaudeBot / PerplexityBot /
  Google-Extended / Bytespider disallowed).
- **_headers** — `no-cache` + `X-Robots-Tag: noai, noimageai` + a strict CSP.
- **Lovetta Lane footer** — sister-site backreferences to every live door.
- **Living background audio** — `music.vaked.dev` embedded as a fixed iframe.

---

## ✦ Layout

```
index.html     the hub — door grid, bonfire hero, koan
favicon.svg    flame favicon
robots.txt     anti-AI scraper rules
_headers       cache + security headers
```

*the constellation · 0 + 1 · fine touch from within · vaked.dev*
