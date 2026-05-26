# Yi Dong Personal Website

Source for [https://dydx404.github.io](https://dydx404.github.io), a minimalist engineering portfolio built with plain Jekyll and GitHub Pages.

## Editing Guide

- `_config.yml`: site title, description, author details, and navigation.
- `_layouts/default.html`: shared page shell, navigation bar, and footer.
- `index.md`: homepage sections.
- `projects.md`: project cards and repository links.
- `cv.md`: CV-style page.
- `contact.md`: contact links and availability.
- `assets/css/style.css`: visual design.
- `assets/img/`: profile and project placeholder images.

The current content highlights Yi Dong's Imperial EIE background, FPGA/SoC projects, embedded Linux and systems programming work, and contact information.

## Local Development

GitHub Pages can build this repository directly. If you have Ruby and Jekyll installed locally, run:

```bash
bundle exec jekyll serve
```

This repository does not require Node.js, React, Tailwind, Bootstrap, or a custom build pipeline.

## GitHub Pages Deployment

The repository name should be:

```text
dydx404.github.io
```

GitHub Pages serves the site at:

```text
https://dydx404.github.io
```

If Pages is not enabled automatically:

1. Open the repository settings on GitHub.
2. Go to **Pages**.
3. Select **Deploy from a branch**.
4. Choose branch `main` and folder `/`.
