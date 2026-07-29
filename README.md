# Shared Grounds and Sons — Website

Simple static landing page for Shared Grounds and Sons (Tampa Bay barrel-aged coffee).

## Structure

- `index.html` — the whole page (who we are, our story, products, contact)
- `style.css` — all styling
- `images/` — hero and section photos

No build step, no dependencies. Just static HTML/CSS.

## Local preview

Open `index.html` directly in a browser, or serve it locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying with GitHub Pages

1. Push this repo to GitHub (already done if you're reading this from the repo).
2. In the repo on GitHub: **Settings → Pages → Source** → select the `main` branch, `/ (root)` folder → Save.
3. GitHub will publish the site at `https://<username>.github.io/<repo-name>/`.
4. To use `sharedgroundsandsons.com`: in Settings → Pages, add the custom domain, then add a `CNAME` record at your domain registrar pointing to `<username>.github.io`.

## Editing content

Everything is in `index.html` — sections are clearly marked (`Hero`, `Who We Are`, `Our Story`, `Products`, `Contact`). Prices and product descriptions live in the `#products` section.
