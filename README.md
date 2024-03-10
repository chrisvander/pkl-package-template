# pkl-package-template

A [Pkl](https://pkl-lang.org) package template for whatever you want.

## Usage

- Click "Use this template" to create a new repository from this template. Name your repository however you want; typical convention would be to start it with `pkl-` and end it with the project this package is configuring.
- Change `<your-user>` and `<your-package>` in the `src/PklProject` file to your GitHub username and package name, respectively.
- Write whatever Pkl modules you want in the `src/` directory.
- Commit changes with a "feat: initial commit" message, which will trigger the GitHub Action to build and publish your package.

## Development

This project uses [Mise](https://mise.jdx.dev) to handle dependencies. To install all dependencies, run `mise install`, followed by `pnpm i`. The `pnpm` command installs commitlint and husky to enforce conventional commit messages, which is used by `release-please` when publishing new versions of your package.

## Published Packages

The included GitHub Action runs `release-please` to manage versions and automatically creates a release with Pkl artifacts on merge to main. You can use these artifacts in any Pkl project with the URL `https://pkg.pkl-lang.org/github.com/<username>/<repo>/<pkg-name>@<version>`.
