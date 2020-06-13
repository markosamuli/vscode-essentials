# README

## Install

Install extensions from a local package:

```bash
npm run install-extension
```

Install extensions from the marketplace

```bash
code --install-extension markosamuli.vscode-essentials
```

## General extensions

| Extension            | Description
|----------------------|-------------
| [EditorConfig]       | Override user/workspace settings with settings found in `.editorconfig` file.
| [Code Spell Checker] | Help with catching common spelling errors while keeping the number of false positives low.
| [TODO Highlight]     | Highlight TODO, FIXME and other annotations within your code.

[EditorConfig]: https://marketplace.visualstudio.com/items?itemName=editorconfig.editorconfig
[Code Spell Checker]: https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker
[TODO Highlight]: https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight

## Git

| Extension | Description
|-----------|-------------
| [GitLens] | Supercharge the Git capabilities.

[GitLens]: https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens

## Node.js

| Extension | Description
|-----------|--------------
| [npm]     | Run npm scripts defined in `package.json` and validate installed modules against the dependencies.

[npm]: https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script

## Programming Languages

| Extension             | Description
|-----------------------|-------------
| [DotENV]              | Environment variables syntax highlighting in `.env` files.
| [Jinja]               | Jinja template language support.
| [Markdown linting]    | Apply standards and consistency for Markdown files.
| [Markdown All in One] | Keyboard shortcuts, table of contents, auto preview and more.
| [YAML]                | Provides comprehensive YAML Language support.
| [Better TOML]         | TOML file support.
| [XML Tools]           | XML Formatting, XQuery, and XPath Tools for Visual Studio Code.
| [Go]                  | Rich Go language support.
| [Python]              | Linting, debugging (multi-threaded, remote), Intellisense, code formatting, refactoring, unit tests, snippets, and more.
| [Prettier]            | Format your JavaScript / TypeScript / CSS using Prettier.

[DotENV]: https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv
[Jinja]: https://marketplace.visualstudio.com/items?itemName=wholroyd.jinja
[Markdown All in One]: https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one
[Markdown linting]: https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint
[YAML]: https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml
[Better TOML]: https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml
[XML Tools]: https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml
[Go]: https://marketplace.visualstudio.com/items?itemName=golang.Go
[Python]: https://marketplace.visualstudio.com/items?itemName=ms-python.python
[Prettier]: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

## AI-assisted development

| Extension     | Description
|---------------|-------------
| [IntelliCode] | AI-assisted development features for Python, TypeScript/JavaScript and Java developers

[IntelliCode]: https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode

## Docker

Extensions when working with Docker containers.

| Extension | Description
|-----------|-------------
| [Docker]  | Adds syntax highlighting, commands, hover tips, and linting for Dockerfile and docker-compose files.

[Docker]: https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker

## Themes

| Extension        | Description
|------------------|------------------
| [Material Icons] | Icons based on Material Design for Visual Studio Code.

[Material Icons]: https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme

## Development

Install Visual Studio Code Extensions CLI:

```bash
npm install -g vsce
```

Build extension package:

```bash
npm run package
```

Publish new version to the marketplace:

```bash
npm run publish
```
