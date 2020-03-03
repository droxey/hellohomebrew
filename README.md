# makerelease

Use this template repository to deploy your Go project using [Goreleaser](https://goreleaser.com/).

## Prerequisites

- Create a [new GitHub repository](https://github.com/new) named `hellohomebrew`.
- Create a [new GitHub repository](https://github.com/new) named `homebrew-hellohomebrew`.
- Run `brew install goreleaser/tap/goreleaser` to install Goreleaser.
- Open `.goreleaser.yml` and change `TODO_GITHUB_USERNAME` to your GitHub username.

## Validating Before Releasing to GitHub

```bash
goreleaser --snapshot --skip-publish --rm-dist
```

