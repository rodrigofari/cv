# João Farinha — CV

Personal CV website. Built as a single-page site with a one-click **Download CV (PDF)** button so recruiters can grab a printable copy of the résumé.

**Live page:** open `index.html` (or deploy this repo with GitHub Pages — Settings → Pages → Deploy from `main` / root).

## Stack

- Plain HTML + CSS — no build step, no dependencies
- Google Fonts (Inter + JetBrains Mono)
- The original CV is included at `assets/joao-farinha-cv.pdf` and served via the download button

## Structure

```
.
├── index.html              # main page
├── styles.css              # design system + responsive layout
└── assets/
    └── joao-farinha-cv.pdf # the downloadable résumé
```

## Updating the CV

1. Replace `assets/joao-farinha-cv.pdf` with the new version (keep the same filename).
2. Edit the relevant section in `index.html` so the web copy matches.
3. Commit & push — GitHub Pages will redeploy automatically.

## Deploy to GitHub Pages

1. Push to `main`.
2. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `/ (root)`**.
3. Visit `https://rodrigofari.github.io/cv/`.

## Contact

- ✉️ rodrifarinha@gmail.com
- 🔗 [linkedin.com/in/joaorodrigofarinha](https://linkedin.com/in/joaorodrigofarinha)
