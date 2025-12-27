# Ellsworth-Wellness — Jekyll site (editable)

This repo uses Jekyll so site content is plain Markdown and easy to edit in the GitHub web editor.

How to edit
- Go to the GitHub repo page, open the file you want (for example `about.md`) and click the pencil icon to edit in the browser, then commit the change.
- Add images to `assets/images/` and reference them in Markdown: `![alt text](/assets/images/name.jpg)`

Preview locally (optional)
1. Install Ruby and Jekyll (only if you want to build locally).
2. Run `bundle exec jekyll serve` and open http://localhost:4000

Deploy with GitHub Pages
- On GitHub, go to Settings → Pages and set the site source to the branch root (e.g. `website-starter` branch, folder `/`).
- GitHub Pages will build the Jekyll site automatically.

Notes
- Replace the Formspree placeholder in `contact.md` with your real Formspree ID or backend URL.
- If you prefer a richer admin UI later, we can add Netlify CMS or a small headless CMS that writes directly to GitHub.
