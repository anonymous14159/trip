# GitHub Pages Deployment

This directory is already structured as a GitHub Pages static site.

Required entry point:
- `index.html`

Static assets:
- `static/css/index.css`
- `static/videos/*.mp4`

Deployment options:
1. Push this folder as the root of a GitHub repository and enable GitHub Pages for the `main` branch root.
2. Or place this folder under a repository root and publish from GitHub Actions or from a `docs/` folder after copying its contents there.

Notes:
- All asset paths are relative, so the site works on GitHub Pages without local server-side routing.
- `.nojekyll` is included to ensure GitHub Pages serves the site as plain static files.
