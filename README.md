# Sudhanshu Saini — Profile Page

A single-page profile site sharing career details — About, Experience, Projects, Open Source, Skills, Education, and Contact. Built with plain HTML + CSS + vanilla JS, no frameworks or build step — deploy it anywhere static hosting works.

## Sections

- **Hero** — role text, quick stats, contact buttons
- **About** — summary + quick info (location, email, phone, links)
- **Experience** — timeline (Servosys Solutions, Hashstudioz Technologies)
- **Professional Projects** — Fuel Management, SpaSalon, E-Parking
- **Open Source** — links to GitHub repos (linkedin, workforce-os, linkedin-clone)
- **Skills** — animated progress bars grouped by category
- **Education** — Galgotias University
- **Contact** — email, phone, LinkedIn, GitHub

## Deploy on GitHub Pages

1. Create a GitHub repo (e.g. `sudhanshu-profile`).
2. Upload these files (or push):
   ```
   git init
   git add .
   git commit -m "Initial profile page"
   git branch -M main
   git remote add origin https://github.com/<username>/<repo>.git
   git push -u origin main
   ```
3. Repo → **Settings** → **Pages**.
4. Under *Branch*, select `main` and folder `/ (root)`, then **Save**.
5. Your site is live at `https://<username>.github.io/<repo>/`.

> Tip: name the repo `<username>.github.io` to get `https://<username>.github.io` directly.

## Open locally

Just double-click `index.html`, or run `python -m http.server` in this folder and visit `http://localhost:8000`.

## Edit

Open `index.html` and update text in the sections. All content lives in that one file:

- Experience details and dates → `#experience`
- Skills percentages → the `data-w` values in `#skills`
- Social links → the `href` values in hero, about, and `#contact`
