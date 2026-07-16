# Tinta

Tailwind CSS palette generator + WCAG contrast lab. One hex in, a 12-stop scale (25-950) out,
with perceptual OKLab spacing, live WCAG 2.1 contrast checking, real design previews,
and exports to Tailwind v4 `@theme`, v3 config, JSON, and SVG.

**Single static file - no build, no dependencies.** 

## Deploy

- **GitHub Pages:** push this repo, then Settings -> Pages -> Deploy from branch (main, root).
- **Netlify / Cloudflare Pages:** drag-and-drop the folder.

## Analytics (optional)

Create a free [GoatCounter](https://www.goatcounter.com) site, then in `index.html`
replace `YOURCODE` in the commented script at the bottom and un-comment it.
Custom events already wired: `copy-export-*`, `download-svg`, `shuffle-*`, `add-palette`.

## Credits

Perceptual spacing built on the [OKLab color space](https://bottosson.github.io/posts/oklab/) by Bjorn Ottosson.
Contrast thresholds per WCAG 2.1 (SC 1.4.3, 1.4.6, 1.4.11).
