# pkl-package-template

A [Pkl](https://pkl-lang.org) package template for whatever you want.

## Development

This project uses [Mise](https://mise.jdx.dev) to handle dependencies. To install all dependencies, run `mise install`, followed by `pnpm i`.

## Published Packages

The included GitHub Action runs `release-please` to manage versions and automatically creates a release with Pkl artifacts on merge to main. You can use these artifacts in any Pkl project with the URL `https://pkg.pkl-lang.org/github.com/<username>/<repo>/<pkg-name>@<version>`.
