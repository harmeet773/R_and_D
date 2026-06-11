# R_and_D

This repository contains a lightweight GitHub Pages site for sharing research and development notes, experiments, and reference material. It is designed to be simple to publish and easy to extend as new pages are added.

## What this site includes
- A home page for the project overview
- A sample page to demonstrate the default layout
- An About page to describe the purpose of the site

## Local preview
From the repository root, run:

```sh
cd R_and_D
bundle install
bundle exec jekyll serve
```

Then open the local preview URL shown by Jekyll, usually http://localhost:4000/R_and_D/.

## Deployment
The GitHub Pages workflow is configured in .github/workflows/pages.yml, so changes pushed to the main branch will be published automatically.

## Project structure
- index.html — main landing page
- sample.html — example content page
- about.html — project overview and team information
- _layouts/default.html — shared page layout
- _config.yml — site title and GitHub Pages settings
