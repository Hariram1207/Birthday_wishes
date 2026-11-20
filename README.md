# For Samantha — Birthday Surprise

A mobile-first, single-page birthday surprise website. It uses CSS animations and lightweight JavaScript; no personal photos or external image assets are required.

## Preview locally
Open `index.html` in a browser, or run a local static server:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deploy with GitHub Pages
1. Create a new **public** GitHub repository (for example `samantha-birthday-surprise`).
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main**, folder **/(root)**, then **Save**.
6. Wait for the Pages deployment to finish. Your site URL will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/samantha-birthday-surprise/`

## Customize
Edit the birthday message and signature in `index.html`. The page is intentionally designed for portrait mobile screens and adapts to larger screens without switching to a desktop layout.

## Notes
- The sound button creates simple original tones using the browser Web Audio API; it does not stream copyrighted music.
- Google Fonts are loaded online. If unavailable, fallback fonts are used.
- No tracking, analytics, backend, or form data collection.
