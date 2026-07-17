# Gunnar Schuster Website Redesign

Static, responsive website prototype for Gunnar Schuster's Bitcoin and crypto education platform.

## Open in VS Code

1. Download or clone this repository.
2. In VS Code, choose **File → Open Folder** and select this folder.
3. Open the integrated terminal.
4. Run:

```bash
npm run dev
```

5. Open `http://localhost:8765`.

If Node.js is unavailable, use Python:

```bash
python -m http.server 8765
```

## Push to GitHub

```bash
git init
git add .
git commit -m "Initial Gunnar Schuster website redesign"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

## Deploy with GitHub Pages

This repository includes a GitHub Actions workflow.

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **GitHub Actions**.
4. Push to `main`, or manually run the Pages workflow.

Your site will be available at:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

## Important before a real launch

- Gunnar must approve every first-person statement.
- Replace placeholder/repeated videos with the final curated videos.
- Connect newsletter, checkout, contact, analytics and consent systems.
- Review tax and financial content professionally.
- Replace automatic translation with reviewed `/en/` pages.
- Update canonical URLs, `robots.txt` and `sitemap.xml` for the final domain.
- Complete legal, privacy and security review.

## Architecture

- `index.html` — homepage
- `styles.css` — shared visual system
- `app.js` — navigation, animations, filters and language control
- `tool-styles.css` — tool interface styles
- `tool-suite.js` — calculators, CoinGecko requests, local storage, FIFO and CSV logic
- `ratgeber.html` — content hub
- `tools.html` — tools hub
- `kurse.html` — courses
- `ueber.html` — About page

This is a review build, not a certified financial, tax or legal product.
