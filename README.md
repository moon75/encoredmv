# Encore DMV — Landing Page Mockup

Single-page nightlife/club landing page design mockup for client review.
All content (photos, copy) is placeholder/dummy — for evaluating layout, tone, and design direction only.

## Run locally

```
npm install
npm run dev
```

Opens at `http://localhost:5173`.

## Deploy to Netlify

1. Push this repo to GitHub.
2. In Netlify: **Add new site → Import an existing project → Deploy with GitHub**, pick this repo.
3. Build settings: build command `npm run build`, publish directory `dist`.
4. Deploy.

The whole page is a single self-contained `index.html` (fonts and styles inlined) — Vite is only used to serve it locally with hot-reload during development.
