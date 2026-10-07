# Build verification — Sunnyth GitHub profile

Snapshot date: **06 Oct 2026**.

## Checked

- Five live SVG assets are XML-valid.
- No JavaScript or `foreignObject` is used.
- Live SVGs use CSS entrances with `animation-fill-mode: both` and include `prefers-reduced-motion: reduce` handling.
- SMIL timelines are authored from `0s`; the ID pendulum uses a 0s-start additive motion layer so the drop/settle and gentle swing can coexist.
- All `<image>` hrefs are `data:` URIs; no external image/font/network request is referenced by the SVGs.
- The supplied `id.png` and `right_pointing.png` bytes were embedded unchanged; their SHA-256 hashes were checked against the uploaded originals.
- Inter Display Bold and Noto Sans Mono are embedded as base64 WOFF2 payloads in every live SVG.
- Five relative README image references are present and end in `?v=1`.
- The supplied tracking/query-string suffixes were removed from the project/social links.
- No contribution-city section is present.
- Static, animation-removed renders were generated for all five SVGs.
- Sampled frame renders were generated for all five SVGs at **0s, 2s, 5s, 9s, and 13s** from the authored animation timelines.
- The README preview was rendered using normal `<img>` elements.
- All five assets were also raster-rendered at **390px** width for a mobile-width sanity check.
- GitHub repo URLs were checked live during build: DoratriX, LeakLock, and Currency Converter. Current public repo snapshots used in the README are dated 06 Oct 2026: 30/8/6 commits respectively, with 0 stars and 0 forks shown at verification time.

## Upload set

Required for the profile README:

1. `README.md`
2. `assets/hero.svg`
3. `assets/about-life.svg`
4. `assets/stack.svg`
5. `assets/id-dashboard.svg`
6. `assets/connect.svg`
7. `LICENSES.md`

Optional convenience file:

- `preview.html`

The WOFF2 files are already embedded inside the SVGs, so the separate `fonts/*.woff2` files are **not required** for GitHub rendering.
