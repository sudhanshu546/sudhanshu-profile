# Sudhanshu Saini — Portfolio

Single-page Java Backend Engineer portfolio — Experience, Featured Project, Skills, Projects, GitHub, Education, and Contact. Built with plain HTML + CSS + vanilla JS, no frameworks or build step — deploy it anywhere static hosting works.

## Sections

- **Hero** — role, tech focus, proof points, contact info, CTAs
- **Professional Experience** — timeline (Servosys Solutions, Hashstudioz Technologies)
- **Featured Engineering Project** — Workforce OS (flagship)
- **Technical Skills** — icon tiles grouped by engineering area
- **Professional Projects** — Fuel Management, SpaSalon, E-Parking
- **Featured Engineering Projects** — GitHub repos (linkedin, linkedin-clone)
- **Education** — Galgotias University
- **Contact** — email, phone, LinkedIn, GitHub, resume download

## Deploy on GitHub Pages

1. Create a GitHub repo (e.g. `sudhanshu-profile`).
2. Push these files:
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

All content lives in `index.html`:

- Experience details and dates → `#experience`
- Skills tiles → the icon tiles in `#skills`
- Featured project → `#featured`
- GitHub links → `#github`
- Social links → hero details and `#contact`