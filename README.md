# Minimal Mathematics Researcher Website

A one-page, dependency-free academic website designed for GitHub Pages.

## Personalize it

Open `index.html` and replace the clearly marked placeholders:

- Name, KAIST affiliation, email, and office information as needed
- Publication entries (an example is included as an HTML comment)
- Talks, posters, and upcoming research travel
- Google Scholar, arXiv, and GitHub text with real links

## Preview locally

No installation or build is needed. Open `index.html` directly, or run a local
web server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a GitHub repository and upload this folder's contents.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Push to the `main` branch. The included workflow publishes the site.

If the repository is named `<username>.github.io`, the site will appear at
`https://<username>.github.io/`. Otherwise it will appear at
`https://<username>.github.io/<repository-name>/`.

## Why GitHub Pages

This site is fully static and has no server-side features. GitHub Pages is free,
requires no framework, and keeps the source and deployment together. Vercel would
work too, but adds no meaningful benefit for this version.

