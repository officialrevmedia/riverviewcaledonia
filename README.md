# Riverview Caledonia — Deployment Package

**File:** `index.html` and supporting assets
**Built:** April 2026
**Stack:** Single-file HTML/CSS/JS (no build step)

## What's in this folder

| File | What it does |
|---|---|
| `index.html` | The entire site — HTML, CSS, embedded JS, images all in one file (~8 MB) |
| `CNAME` | Tells GitHub Pages your custom domain |
| `robots.txt` | Search engine crawl rules |
| `sitemap.xml` | Helps Google index your pages |
| `404.html` | Branded "page not found" page |
| `.nojekyll` | Skips GitHub Pages' Jekyll processing (faster, cleaner deploy) |
| `favicon.ico` | Browser tab icon (legacy `.ico` format) |
| `favicon-16.png` / `favicon-32.png` | Modern browser tab icons |
| `apple-touch-icon.png` | iPhone/iPad home screen icon |
| `og-image.jpg` | The image that shows when someone shares the link on Facebook, LinkedIn, WhatsApp, etc. |
| `humans.txt` | Optional credits file |

## Before you deploy — a 30-second checklist

1. **Form endpoint:** Open `index.html`, search for `formspree.io/f/REPLACE_WITH_YOUR_FORM_ID`, replace with your real Formspree form URL.
2. **Domain:** If you're using a domain other than `riverviewcaledonia.ca`, see the "Custom Domain" section in `DEPLOY-GUIDE.md`.
3. **Test locally:** Open `index.html` in a browser to confirm everything renders before pushing.

That's it. Follow `DEPLOY-GUIDE.md` for the step-by-step.
