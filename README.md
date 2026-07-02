# Clipline Docs

Documentation for Clipline, built with Docusaurus and deployed to GitHub Pages.

## Local development

```bash
npm install
npm start
```

## Build

```bash
npm run build
```

## Docs

- `docs/clipline-cloud/railway.mdx` covers the easiest Railway deployment path.
- `docs/clipline-cloud/self-hosting.mdx` covers the public Clipline Cloud self-hosting path.

## GitHub Pages

The site is configured for:

```text
https://dain98.github.io/clipline-docs/
```

GitHub Pages needs to be set to **Settings > Pages > Build and deployment > Source > GitHub Actions**. After that, pushes to `main` deploy through `.github/workflows/deploy.yml`.
