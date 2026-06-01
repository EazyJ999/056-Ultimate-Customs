# 056Customs.co.za

A clean, responsive landing page for Ultimate Customs 056.

## About

This repository contains a single-page static website for an automotive workshop offering spray painting, panel beating, car servicing, repairs, parts sourcing, and customer quote requests.

## Features

- Responsive hero section with strong brand positioning
- Service overview cards and trusted brand list
- Quote request form with vehicle details and contact preference
- WhatsApp quick contact and direct email support
- GitHub Pages deployment via Actions

## Deployment

The site is published with GitHub Pages using the workflow in `.github/workflows/jekyll-gh-pages.yml`. The workflow prepares a `_site` artifact and deploys the static files to GitHub Pages.

### Custom domain

This repo is configured to serve from the custom domain `056customs.co.za` via the `CNAME` file.

To complete the setup, add DNS records for your domain:

- `A` records pointing to:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- If you want `www.056customs.co.za` as well, add a `CNAME` record for `www` pointing to `056customs.co.za`.

Then enable GitHub Pages for this repository in the repo Settings and confirm the custom domain is listed as `056customs.co.za`.

## Local development

Install dependencies with `npm install`, then use `npm run dev` to preview the site locally. Use `npm run build` to build a production-ready static site and `npm run preview` to preview the build output.

## Editing

- Update content in `index.html`
- Maintain the `CNAME` file for custom domain support
- Push changes to `main` to trigger the Pages workflow

