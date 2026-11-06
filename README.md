# Personal academic website (Quarto)

Source for Amadeo Ramirez's academic site: `index.qmd` (Home), `research.qmd`
(Research & Projects), `cv.qmd` (CV). Built with [Quarto](https://quarto.org).

## Preview locally

    quarto preview

## Publish (GitHub Pages, /docs on main)

    quarto render          # writes the site to docs/
    git add . && git commit -m "Update site"
    git push

In the repository's Settings -> Pages, choose "Deploy from a branch", branch `main`,
folder `/docs`. A repository named `<username>.github.io` is served at
`https://<username>.github.io`.
