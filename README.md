# Resume Site

A standalone GitHub Pages resume site.

## Local preview

Open `index.html` directly in your browser, or run a static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Publish on GitHub Pages

1. Push this repository to GitHub (public repo).
2. In repository settings, enable Pages with:
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`
3. Your site URL will be:
   - `https://<your-username>.github.io/<repo-name>/`
