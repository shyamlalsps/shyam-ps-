# Shyam P S Portfolio — GitHub + Vercel Auto-Update Package

## How Push-to-Live Works
1. Upload the extracted files from this ZIP into your **GitHub repository** (root folder).
2. Make sure your GitHub repository is connected to **Vercel**.
3. Whenever you push a new update to GitHub:
   - The included GitHub Action (`.github/workflows/verify-push.yml`) runs a quick check on the push.
   - **Vercel** automatically detects the GitHub push, builds, and updates your live website URL—no manual HTML export needed.

## Folder Structure
- `index.html` — Your portfolio web app (optimized images, lazy loading, and fast UI).
- `assets/` — Drop compressed images (`.webp` or `.jpg`) here for fast CDN delivery.
- `vercel.json` — Caching & clean URL rules for Vercel.
- `.github/workflows/verify-push.yml` — Automated push verification workflow.
