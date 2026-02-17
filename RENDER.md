# Deploying to Render (Static Site)

This repository now contains a `public/` folder with the static site files (index.html, style.css, script.js).

To deploy on Render (recommended: Static Site):

1. On Render, click "New" → "Static Site".
2. Choose GitHub and select this repository `qburm/Test-Quinten-PRIV` (or paste the public repo URL).
3. Branch: `main`.
4. Build Command: leave empty.
5. Publish Directory: `public`.
6. Auto-Deploy: enable (recommended).
7. Create the site — Render will build and provide a URL.

Notes:
- The `_redirects` file ensures client-side routing works for single-page apps (optional here).
- If Render still does not see the repo, reconnect GitHub credentials in Render and give Render access to this repository.
