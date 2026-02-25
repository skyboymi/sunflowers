# Hugo Blog

This repository is configured for deploying Hugo to GitHub Pages via GitHub Actions.
Current theme: `hugo-theme-dream` (`themes/dream`).

## Local preview

```powershell
hugo server -D
```

## Build

```powershell
hugo --gc --minify
```

## Publish

1. Push to `main`.
2. In GitHub repository settings:
   - `Settings` -> `Pages`
   - `Source` = `GitHub Actions`
3. Wait for `.github/workflows/hugo.yml` to finish.

## Theme config

- Main config: `hugo.toml`
- Dream docs: `https://hugo-theme-dream.g1en.site/`

