# 💀 DOOMSCROLLING

> *The endless descent. Measured in pixels.*
<p align="center"><img src="doomguy.png" width="80" alt="Doomguy"/></p>


A browser-based pixel art experience that turns your mindless scrolling into a game. Doomguy runs. You scroll. There is no end.

---

## 🎮 Features

- **Infinite scroll** — page extends forever, there is no bottom
- **Pixel counter** — tracks every downward pixel (upward scrolling doesn't count)
- **Active timer** — only ticks while you're actually scrolling
- **Screen counter** — how many viewport-heights you've fallen
- **Sprite animation** — Doomguy animates on scroll, holds last frame when idle
- **Tiled background** — classic Doom-style stone wall, parallax scrolling
- **Milestone flashes** — achievements at 500px, 2K, 5K, 10K, 50K, 100K
- **E1M1 soundtrack** — *At Doom's Gate* loops forever, mutable
- **Share to X/Twitter** — posts your pixel count, time, and site link
- **Fully responsive** — desktop and mobile

---

## 🚀 Deploy

```bash
git clone https://github.com/znatgost/doomscrolling
open index.html
```

GitHub Pages: push `index.html` as `index.html` to `gh-pages` branch.

All assets (sprites, background tile, audio) are embedded as base64 — one file, works offline, zero dependencies.

---

## 🗂 Structure

```
index.html   # entire project — self-contained
README.md
```

---

## 🕹 Controls

| Action | Effect |
|---|---|
| Scroll down | Doomguy runs, pixels counted |
| Stop scrolling | Timer pauses, frame holds |
| Click SHARE | Posts your score to X |
| Click MUTE / PLAY | Toggle E1M1 |

---

## 🧱 Tech

- Vanilla HTML / CSS / JS — zero frameworks, zero build step
- Canvas 2D for tiled background with parallax
- Base64-embedded assets for single-file portability
- Sprite animation via `scroll` event + frame throttle (80ms)
- Infinite page extension via `scrollHeight` detection

---

## 🔗 Links

- **Live:** [znatgost.github.io/doomscrolling](https://znatgost.github.io/doomscrolling/)
- **Author:** [@znatgost](https://twitter.com/znatgost)

---

*Doom assets © id Software. This is a fan project.*
