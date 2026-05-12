# UBT Institute Website

Single-page website for the UBT Institute, built as a static site in one file: `index.html`.

## Stack

- Tailwind CSS (CDN)
- Lucide Icons (CDN)
- MathJax (LaTeX rendering)

## Features

- Dark scientific visual style
- EN/CZ language switch (no page reload)
- Responsive layout for desktop and mobile
- Research sections and publication placeholder

## Local preview

Open `index.html` directly in your browser, or run a simple static server:

```bash
python3 -m http.server 8080
```

Then visit:

- http://localhost:8080/

## Deployment

This repository is intended for GitHub Pages style static hosting.

## Notes

- Publication button is intentionally disabled until the paper is submitted.
- Update organization/contact links directly in `index.html` as needed.
