# MatrixRainFall

A single-file, WebGL2-rendered digital rain effect in the style of *The Matrix*.

**Live demo:** https://majormokoto.github.io/MatrixRainFall/

No build step, no dependencies — `index.html` is the entire app. Open it in any
browser with WebGL2 support, or just visit the link above.

## Features

- GPU-instanced rendering (WebGL2) for smooth performance at high density
- Adjustable speed, font size, density, burst frequency, and trail length
- Character sets matching the film: half-width katakana, digits, symbols, and
  lowercase Latin letters — each toggleable independently
- **Residuals** — hidden character names from the trilogy occasionally spelled
  out in the rain during a burst
- **Deja Vu** — an ASCII-art cat that occasionally appears in the rain, in one
  of three variants, then fades back into the code
- **Effects per burst** — controls how many Residuals words and/or the cat
  compete for a slot in a given burst
- Light/dark theme variants, pause/resume ("Take the Red/Blue Pill"), and an
  idle-dim state

## Controls

All controls live in the side panel:

| Control | What it does |
|---|---|
| Speed | How fast columns fall |
| Font size | Glyph size (also scales column/row spacing proportionally) |
| Density | Percentage of columns actively falling at any time |
| Trail length | Scales the random trail-length range up or down |
| Burst | How often a burst (extra flood drops + Residuals/Deja Vu) fires |
| Effects per burst | How many Residuals words / the cat can appear per burst |
| Residuals / Deja Vu | Independent on/off toggles for each easter egg |
| Characters | Toggle katakana, digits, symbols, and letters independently |

Press the pill button to pause/resume.

## Running locally

Just open `index.html` in a browser — no server or build tooling required.
