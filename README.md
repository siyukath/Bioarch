# BioArch

Static marketing site for BioArch · 拜驰生物医药 — cross-border biotech advisory.

## Structure

```
index.html       — page markup
css/styles.css   — all styles
js/main.js       — i18n, navigation, interactions
vercel.json      — Vercel static deployment config
```

## Local preview

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Deploy on Vercel

1. Import the GitHub repo in Vercel
2. Framework preset: **Other** (static site)
3. Build command: leave empty
4. Output directory: `.` (root)

Vercel will serve `index.html` automatically.
