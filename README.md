# Fact check

This GitHub repo contains MD files from our factchecking efforts taken from various sources

One of our goals is to be certified by [IFCN](https://ifcncodeofprinciples.poynter.org/signatories)

## Prerequisites

-   [git](https://git-scm.com/) - version control system
-   [node.js 18+](https://nodejs.org/en) - (to maintain this codebase)
-   [VSCode](https://nodejs.org/en) - should be installed on your machine to maintain this effort
-   [pip](https://www.odoo.com/forum/help-1/how-to-install-pip-in-python-3-on-ubuntu-18-04-167715) - to compile documentation `sudo apt install python3-pip`

## Installing toolset

The toolset is part of this repo and uses `npm` as a package management

### Installing prerequisites

```bash
npm i
```

## Documentation

[docs](./docs/) is the repository of docs now.

mkdocs tool used to convert md files to HTML and deploy to the website

In order to compile it locally you will need

```sh
npm run docs
```

It will run `mkdocs` in strict mode and will fail if the will be broken links

Documents in this repository are not published outside of GitHub

The most important about Documents is [Publishing](./docs/content/general/Document_Publishing.md)
