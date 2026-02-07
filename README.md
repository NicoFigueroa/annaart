# Ceramic Artist Site (Hugo)

This repository is a Hugo site intended for quick iteration with a ceramic artist. The structure is minimal and intentionally easy to customize.

## Quick start

1. Install Hugo (standard version is fine).
2. Run the dev server:

```bash
hugo server -D
```

The site will be available at http://localhost:1313.

## Key files

- `hugo.toml`: Site settings and editable artist info.
- `content/_index.md`: Homepage copy and hero settings.
- `content/work/`: Portfolio items.
- `layouts/`: Templates.
- `static/css/style.css`: Styles.
- `static/img/`: Image assets (replace placeholders).

## GitHub Pages

A GitHub Actions workflow is included at `.github/workflows/hugo.yml`. Once enabled in the repo settings, pushes to `main` will build and deploy automatically.
