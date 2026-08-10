# Sheikh Aiman — Portfolio

This is a lightweight, responsive portfolio website built with HTML, CSS, and vanilla JavaScript.

Quick edits:
- Update contact links in `index.html` (email, GitHub, LinkedIn).
- Replace the Bugatti demo `Live Demo` link with your hosted demo URL.
- Add project images to `assets/images/` and reference them from project cards.

To preview locally:

```bash
# Open the folder in VS Code and use Live Server, or
# open index.html directly in your browser
# on Windows (PowerShell)
start index.html

# or using a simple Python HTTP server (recommended to mimic hosting):
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

License: Personal portfolio. Replace content with your own before publishing.

## Deploying

GitHub Pages:

1. Push this repo to GitHub.
2. Enable GitHub Pages from the `gh-pages` branch (the workflow `/.github/workflows/deploy-gh-pages.yml` will publish the repo root).

Netlify:

1. Connect your repo to Netlify and set the project root as the publish directory.
2. `netlify.toml` is included for basic redirects.

If you want, I can add a `sitemap.xml` and `robots.txt` next.
