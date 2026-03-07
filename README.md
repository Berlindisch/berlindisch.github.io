# Berlindisch

Website for the Berlindisch Collective — a food & logistics venture studio rooted in Berlin.

Built with [Eleventy](https://www.11ty.dev/) as a simple static site.

## Setup

```sh
npm install
```

## Development

```sh
npm run serve
```

Opens a local dev server at `http://localhost:8080` with live reload.

## Build

```sh
npm run build
```

Output goes to `_site/`.

## Deployment

The site auto-deploys to GitHub Pages via the workflow in `.github/workflows/deploy.yml` on every push to `main`.

## Editing

All page content lives in `src/` as `.njk` (Nunjucks) templates. Design tokens and styles are in `src/css/style.css`. Site metadata (title, nav links) is in `src/_data/site.json`.
