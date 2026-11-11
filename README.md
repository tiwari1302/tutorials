# Tutorials

A single page that links to each tutorial. The tutorials themselves stay in their own repositories.

https://tiwari1302.github.io/tutorials/

## Add a tutorial

1. Publish the tutorial from its own repository with GitHub Pages.
2. Append one object to `catalog.json` with `title`, `description`, and `url`.
3. Commit and push `main`.

`index.html` only renders `catalog.json`. Do not copy tutorial source into this repository.

## Pages

GitHub Pages deploys from the `main` branch, folder `/` (root). The empty `.nojekyll` file tells Pages to serve the files as-is.
