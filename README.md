# mohitvachhani.github.io

Personal portfolio. A single static page with no build step or runtime dependencies.

- `site/index.html` contains the page, including all styles, scripts and project data.
- `site/` also holds the favicons and is deployed as-is to GitHub Pages by `.github/workflows/pages.yml` on every push to `main`.

## Local preview

```bash
python3 -m http.server -d site 8000
```

Then open http://localhost:8000.
