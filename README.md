# Clipline

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

- `docs/desktop/` covers the Clipline Windows app.
- `docs/reference/` covers compatibility, privacy, troubleshooting, and shortcuts.
- `docs/clipline-cloud/` covers Railway and self-hosted Clipline Cloud deployments.
- `docs/developers/` covers source builds and docs-site maintenance.

## GitHub Pages

The site is configured for:

```text
https://dain98.github.io/clipline-docs/
```

GitHub Pages needs to be set to **Settings > Pages > Build and deployment > Source > GitHub Actions**. After that, pushes to `main` deploy through `.github/workflows/deploy.yml`.
