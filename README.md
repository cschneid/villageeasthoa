# Village East HOA Website

Static website for the Village East HOA in Fort Collins, CO. Built with [Eleventy](https://www.11ty.dev/).

## Setup

```bash
nvm use          # uses Node version from .nvmrc
npm install      # install dependencies
```

## Development

```bash
npm run serve    # local dev server with hot reload at http://localhost:8080
```

## Build

```bash
npm run build    # builds to _site/
```

## Structure

- `src/` — source content (Markdown + Nunjucks templates)
- `src/_includes/layout.njk` — shared page layout (nav, header, footer)
- `src/_data/site.json` — site metadata (title, contact info, board members)
- `src/static/` — PDFs, images, CSS (copied as-is to build output)
- `_site/` — build output (gitignored)

## Adding Content

Edit Markdown files in `src/`. Add PDFs to `src/static/pdfs/`. Push to deploy.
