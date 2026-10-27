# RYK!LE Official Artist Site — bilingual starter

A responsive, single-page artist website for GitHub Pages. It includes Japanese/English switching, original lightweight canvas motion, scroll reveals, and reduced-motion accessibility support. It uses no external JavaScript libraries or image assets.

## Before publishing
- Replace the SoundCloud and Instagram homepage links in `index.html` with RYK!LE's actual artist profile URLs.
- Verify all biography copy, track titles, and public-release status. The listed works are provisional examples.
- Replace `EST. 20XX` with a real date or remove it.

## Publish on GitHub Pages
1. Create a **public** repository named `rykile.github.io` at https://github.com/new
2. Upload `index.html` and `README.md` to the repository root and commit.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. After deployment, visit https://rykile.github.io/ (first publication may take a few minutes).

No build step is needed. The animation is drawn with the browser canvas API and respects `prefers-reduced-motion`.
