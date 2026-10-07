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
- Five relative README image references are present with cache-busting suffixes.
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

## Latest revision

- The hero now cycles through four roles: Product Builder, Full Stack Developer, AI/ML Engineer, and Student.
- Reduced motion disables both CSS entrances and SMIL animations.
- XML parsing, unique SVG IDs, embedded-only image references, SMIL key-time ordering, README image paths, and upload ZIP contents were checked after this revision.
- Timed raster frames and the mobile-width visual check were not rerun after the latest edits. This environment has no SVG rasterizer or active display, so the earlier render notes above describe the prior revision.
- The About + Life panel was redesigned again to separate its process diagram and capability list from the three interest slides. Its latest SVG parses, carousel timing is valid, it contains no portrait image, and the matching file in the upload ZIP was verified.
- The three interest progress bars now use matching 12-second CSS timelines; reduced motion leaves a static first-segment indicator. The SVG parses and the upload ZIP contains the updated slide.
- The Stack slide now contains 36 image marks for the listed technologies (including SQL and SQLite in the Database group) (Simple Icons vectors, an official VS Code mark, or purpose-drawn concept glyphs). It parses with unique IDs and no external asset references; the icon sources are documented in `LICENSES.md`.
- The Projects slide and its standalone repository links were removed; the ID dashboard and Connect slides are numbered **03** and **04**.
