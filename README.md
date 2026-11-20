# DT Mini Browser – Project Website

Modern, SEO-optimized promotional website for **DT Mini Browser**.

## Contents

- `index.html` – English version
- `de/index.html` – German version
- `og-image.jpg` – Open Graph / Discord / Twitter preview image
- `robots.txt` + `sitemap.xml`

## Features of this site

- Full Open Graph + Twitter Card meta tags (great Discord embeds)
- `hreflang` for EN/DE
- JSON-LD structured data (`SoftwareApplication`)
- Clear and prominent warning: **no public servers**
- Responsive, modern dark design
- Semantic HTML, good heading structure
- Canonical URLs ready for GitHub Pages

## Deploy

Recommended: GitHub Pages from the `docs/` folder or a dedicated `gh-pages` branch / separate repo.

Example (if this folder is the root of a repo):

```bash
# Just push the contents of this folder to the gh-pages branch
# or enable GitHub Pages on the main branch with /docs root
```

Remember to update the absolute URLs in the meta tags and sitemap if you use a different domain.

## Project links

- Android Client: https://github.com/danltech/dt-mini-browser-android
- Rendering Server: https://github.com/danltech/dt-mini-browser-server
