# MTX Gov Child Welfare

Product-focused landing page prototype for the MTX child welfare product suite.

## Positioning

The site presents MTX Gov Child Welfare as a reusable, modular product foundation rather than a collection of implementation services. It distinguishes the two confirmed implementation contexts from recommended product and agency performance measures.

## Local preview

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173` from this directory.

## Publishing

The repository is configured for GitHub Pages through the workflow in `.github/workflows/pages.yml`.

For a new repository, enable Pages once in **Settings → Pages** and select **GitHub Actions** as the source. Then open **Actions → Deploy static site to Pages** and run the workflow. Later pushes to `main` deploy automatically.
