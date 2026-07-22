# spacedatalab.org

Source for the [SpaceDataLab](https://spacedatalab.org) website — a static landing
page served by GitHub Pages from this repository's `main` branch.

## Structure

- `index.html` — the landing page (self-contained; inline CSS, no build step).
- `404.html` — custom not-found page.
- `favicon.svg` — site icon.
- `CNAME` — custom apex domain (`spacedatalab.org`).
- `.nojekyll` — serve files as-is, skipping Jekyll processing.
- `robots.txt` / `sitemap.xml` — indexing hints.

## Local preview

Open `index.html` directly, or serve the folder:

```sh
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy

Any push to `main` publishes automatically via GitHub Pages. No build is required —
the site is plain HTML/CSS.
