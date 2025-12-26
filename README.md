# Ellsworth-Wellness — Website (Starter)

This repository contains a simple static website starter for Ellsworth Wellness.

## What’s included
- `index.html` — single-page layout with hero, services, about, and contact
- `assets/css/styles.css` — responsive styles
- A contact form wired to Formspree (replace `{YOUR_FORMSPREE_ID}`)

## Quick local preview
1. Clone the repo.
2. Serve locally (example using Python)
   - `python -m http.server 8000` (then open http://localhost:8000)

## Customization
- Replace site text in `index.html`.
- Replace brand color in `assets/css/styles.css` (CSS variable `--brand`).
- Replace the contact form `action` URL with your Formspree form endpoint or your own backend.
- Add images in `assets/images/` and reference them in the HTML.

## Deploy
- GitHub Pages: push to `main` (or `gh-pages`) and enable Pages in repository settings; set the site source to the branch root.
- Vercel/Netlify: connect the repo and deploy; they’ll pick up the static site automatically.

## Next steps I can help with
- Add a blog (Markdown or headless CMS)
- Switch to Next.js or another framework for dynamic pages
- Add booking integration (Calendly, Acuity)
- Implement SEO meta tags, sitemap, and analytics
- Create a custom domain and automatic HTTPS
