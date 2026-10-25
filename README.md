# Yousif Ahmed — AI Engineer

An interactive CV, built as a single self-contained HTML file.

**Live:** https://yousif99u1234-hue.github.io/yousif-ahmed/

## About the build

One file, no dependencies, no build step, no network calls. Open `index.html` in any
browser — including offline — and it runs.

- **Scroll-driven storytelling** — sealed doors that draw back as each project enters
  the viewport, driven by `requestAnimationFrame` against scroll position
- **Original artwork** — every illustration is hand-authored SVG line art, drawn for
  this page and inheriting `currentColor` so it re-inks itself with the theme
- **Ambient canvas** — drifting embers rendered to a DPR-aware `<canvas>`, paused when
  the tab is hidden
- **Theme-aware** — a Lumos/Nox toggle; the palette is defined entirely as custom
  properties, and every text pair clears WCAG AA contrast in both themes
- **Embedded typography** — KoShareb Display subset to WOFF2 (117 KB → 39 KB) and
  inlined as a data URI, so the page carries its own type
- **Accessible** — respects `prefers-reduced-motion`, visible focus states, labelled
  SVG, and no horizontal overflow from 360 px up
- **Print stylesheet** — strips every effect into a clean, plain, one-column CV

## Other pages

- **Finance Ops Ledger Review** (sample report, fictional test data): https://yousif99u1234-hue.github.io/yousif-ahmed/finance-ops-report/

## Contact

- yousif99u1234@gmail.com
- +964 783 013 4104
