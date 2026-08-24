# kevingraham.info

Personal site. Single static page, no build step.

- `index.html` — the whole site (inline CSS, inline SVG)
- `og-image.png` — social share card (1200x630)
- `Kevin-Graham-Resume.pdf` — linked from the hero (**not yet added**)
- `CNAME` — custom domain for GitHub Pages
- `.nojekyll` — skip Jekyll processing

## Deploy

Pushing to `main` publishes via GitHub Pages (Settings -> Pages -> Source: `main` / root).

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000
