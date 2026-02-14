# Pig Roundup (GitHub Pages)

This repo is ready to deploy as a GitHub Pages site.

## Deploy Steps

1. Push this repo to GitHub.
2. In GitHub, open **Settings > Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Push to the `main` branch (or run the workflow manually in **Actions**).

Your site will be published at:

- `https://<your-username>.github.io/<your-repo>/`

## Local Preview

Run from the repo root:

```bash
python3 -m http.server 8000
```

Then open:

- `http://localhost:8000`
