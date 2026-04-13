# Ayush Tiwari Portfolio

Dynamic React/Vite portfolio for Ayush Tiwari, built around editorial design, case studies, source backlinks, local work files and minimal motion.

## Run locally

```bash
npm install
npm run dev
```

Open `http://127.0.0.1:5173/`.

## Production build

```bash
npm run build
npm run preview
```

## Content model

Portfolio content lives in `src/portfolioData.js`:

- Case studies
- Public backlinks
- Local work files
- Metrics and capability stack

Work samples copied from Google Drive live in `public/assets/work/` so they are included in the production build.

## GitHub Pages

The workflow in `.github/workflows/deploy.yml` builds the app and publishes `dist/` to GitHub Pages when changes are pushed to `main`.

Before deployment, enable GitHub Pages with GitHub Actions as the source in the repository settings.
