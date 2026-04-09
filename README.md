# Personal Website

Static site intended for **GitHub Pages** + a custom domain (domain purchased from Squarespace).

## Local preview

You can open `index.html` in your browser, or run a tiny local server:

```bash
python3 -m http.server 5173
```

Then visit `http://localhost:5173`.

## Deploy

This repo includes a GitHub Actions workflow that deploys the contents of the repository to GitHub Pages on every push to `main`.
