# Yi Dong Personal Website

This repository contains the source for [https://dydx404.github.io](https://dydx404.github.io), a minimalist academic-engineering portfolio built with GitHub Pages and Jekyll.

## Structure

```text
.
|-- _config.yml
|-- _layouts/
|   `-- default.html
|-- index.md
|-- projects.md
|-- cv.md
|-- contact.md
|-- assets/
|   |-- css/
|   |   `-- style.css
|   `-- img/
|       |-- profile-placeholder.png
|       `-- project-placeholder.png
`-- README.md
```

## Editing

- Edit `index.md` for the homepage.
- Edit `projects.md` for project cards and repository links.
- Edit `cv.md` for CV-style content.
- Edit `contact.md` for email, LinkedIn, and availability details.
- Edit `assets/css/style.css` for typography, spacing, and colors.

## Deploying With GitHub Pages

For a user site, the repository must be named:

```text
dydx404.github.io
```

Push the repository to GitHub under the `dydx404` account. GitHub Pages will serve the site at:

```text
https://dydx404.github.io
```

If Pages is not enabled automatically, open the repository settings on GitHub, go to **Pages**, and select:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/`

No Node.js or custom build pipeline is required.
