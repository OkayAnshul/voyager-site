# Voyager — website

The public marketing + docs site for **Voyager**, a private, on-device location timeline for Android.
This repo is intentionally **public** and contains **no app source code** — only the static website
(HTML/CSS + screenshots). The Voyager app source is kept in a separate, private repository.

**Live site:** `https://<your-username>.github.io/voyager-site/` (update this once Pages is enabled).

## Pages
- `index.html` — landing page (positioning, the three jobs, the moat, screenshots)
- `features.html` — full feature overview
- `development.html` — the development story & process
- `privacy.html` — the privacy policy (this is the URL to give Google Play)

## Deploying (one-time setup)
1. Create a **public** GitHub repo named `voyager-site` and push this folder to `main`.
2. In the repo, go to **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. The included workflow (`.github/workflows/pages.yml`) deploys on every push to `main`.
4. Your site will be live at `https://<your-username>.github.io/voyager-site/`.
   The privacy policy URL for the Play Console is `…/voyager-site/privacy.html`.

Optionally add a custom domain in **Settings → Pages**.

## Notes
- Fully static and self-contained (only a Google Fonts stylesheet is loaded).
- Update the “Get it on Google Play” links in `index.html` once the app is published.

© 2026 Anshul (Cosmic Laboratory). Site content all rights reserved.
