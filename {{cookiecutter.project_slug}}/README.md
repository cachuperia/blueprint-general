# {{ cookiecutter.git_repo_name }}

![checks][checks] ![release][release]

## Table of contents

* [About](#about)
* [Prerequisites](#prerequisites)
* [Usage](#usage)
* [CD/CI](#cdci)
* [Contributing](#contributing)

## About

{{ cookiecutter.project_short_description }}

## Prerequisites

Tools to install: [git][g], [pre-commit][pk], and [detect-secrets][ds].

You can use [this][a] playbook for automated tools installation.

## Usage

**TODO**

### Setup local environment

```shell
git clone git@github.com:{{ cookiecutter.github_organization }}/{{ cookiecutter.git_repo_name }}.git
cd {{ cookiecutter.git_repo_name }}
make init
```

Run `make` to list all available targets.


## CD/CI

- `check` GitHub [workflow][wch].
- `release` GitHub [workflow][wr]. Release commit types: `fix`, `feat`.

## Contributing

- Commit message style - [Conventional Commits][cc].


[a]: https://github.com/cachuperia/ansible-role-server-bootstrap
[cc]: https://www.conventionalcommits.org/en/v1.0.0/
[ds]: https://github.com/Yelp/detect-secrets#installation
[g]: https://www.atlassian.com/git/tutorials/install-git
[pk]: https://pre-commit.com/#install

[wch]: .github/workflows/checks.yml
[wr]: .github/workflows/release.yml

[checks]: https://github.com/{{ cookiecutter.github_organization }}/{{ cookiecutter.git_repo_name }}/actions/workflows/checks.yml/badge.svg
[release]: https://github.com/{{ cookiecutter.github_organization }}/{{ cookiecutter.git_repo_name }}/actions/workflows/release.yml/badge.svg
