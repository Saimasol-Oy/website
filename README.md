# Pusa landing page

A responsive, single-page landing page for a Finnish software studio.

## Run locally

No build tools are required. Open `index.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Customize

Everything is contained in `index.html`: page content, styling, favicon, and the small scroll animation. Search for `PUSA`, `hello@pusa.fi`, and `Pusa Oy` to replace the draft company details.

The typefaces are loaded from Google Fonts. You can replace the font link or self-host the files later.

## Put it on GitHub

1. Create a new empty repository on GitHub.
2. Extract this ZIP and open a terminal in the extracted folder.
3. Run:

```bash
git init
git add .
git commit -m "Initial landing page"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

You can host it free with GitHub Pages: in the repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

