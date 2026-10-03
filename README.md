# franksbrushhog.com — preview site

One-page static site for **Frank's Brush Hog, Excavating & Clearing** (Lamoni, IA).
Plain HTML/CSS, no build step. Served by GitHub Pages from `main` (root).

- `index.html` – page, meta/OG tags, LocalBusiness JSON-LD
- `assets/styles.css` – styles (self-hosted Barlow fonts in `assets/fonts/`, OFL)
- `assets/img/` – WebP images

Before going live on franksbrushhog.com: remove the `<meta name="robots" content="noindex">` line in `index.html`.

Images in `assets/img/` are AI-generated illustrations (Grok Imagine), not photos of Frank's own jobs.

## Service-area map data

The faint map inside the "Where Frank works" radar is drawn from public-domain U.S. Census Bureau data:
2023 cartographic boundary files (counties, states, 1:500k), 2023 TIGER/Line primary & secondary roads
for Iowa and Missouri (I-35, US-69, IA-2), and town points from the 2023 Census Gazetteer.
Projected locally around Lamoni (40.6228, -93.9341) at 7.2 SVG units per mile, clipped to the 25-mile radar circle.
