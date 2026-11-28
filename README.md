# Shyam P S — Portfolio + Password-Protected Dashboard

## Structure
- `index.html` — Clean static public portfolio (zero admin buttons or XML export/import).
- `admin.html` — Password-protected WordPress-style dashboard (`/admin` or `/admin.html`, default password: `shyam2027`).
- `data/site-data.json` — Live portfolio content loaded by the website.
- `vercel.json` — Clean URL routing (`/admin`).

## How Automatic Live Publishing Works
1. Upload all files in this ZIP to your GitHub repository connected to Vercel (replacing old files).
2. Open `https://your-site.vercel.app/admin` and log in (`shyam2027`).
3. Under **Profile & Settings**, enter your GitHub username, repo name, and Personal Access Token once.
4. From then on, whenever you add a project, image, or tutorial and click **Save & Publish Changes**, it commits straight to GitHub and Vercel automatically updates the live website.
