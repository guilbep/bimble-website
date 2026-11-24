# bimble-website

The landing page of [Bimble](https://github.com/guilbep/bimble), for **bimble.ch**.

The site is one file, `index.html` (styles, script and screenshots are inside it).
The app itself lives in [guilbep/bimble](https://github.com/guilbep/bimble).

## Deploy

Every push to `main` publishes `index.html` to GitHub Pages (`.github/workflows/pages.yml`).
Pull requests only run the check.

One-time setup, in the repository settings:

1. **Settings → Pages → Source**: GitHub Actions.
2. **Settings → Pages → Custom domain**: `bimble.ch`, then tick *Enforce HTTPS* once the certificate is issued.
3. DNS for `bimble.ch` (zone at Infomaniak), as in the
   [GitHub Pages documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site):
   - apex `A`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - apex `AAAA`: `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153`
   - `www` `CNAME`: `guilbep.github.io.`

## Screenshots

Taken from the web UI at 1440 × 874, saved as WebP at 1280 × 777 and embedded in `index.html`.
