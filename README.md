# Fleek Auction House (Figma Make export)

Interactive auction prototype exported from [Figma Make](https://www.figma.com/design/Pj8TMYsMbOUqYyJP3KGiCy/Interactive-Prototype-Development).

## Local development

```bash
npm install
npm run dev
```

## Deploy to Vercel

This repo is set up so Vercel can detect Vite from the **repository root** (`package.json` + `vite.config.ts` at `/`).

1. Import the GitHub repo in Vercel (Framework Preset: Vite).
2. Leave **Root Directory** empty (project lives at the repo root).
3. In **Project Settings → Deployment Protection**, turn off **Vercel Authentication** if you want a public demo link.

```bash
npm run build
```
