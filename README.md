# blueprint-general

![checks][checks] ![release][release]

## Table of contents

* [About](#about)
* [Prerequisites](#prerequisites)
* [Contribute](#contribute)

## About

Basic language agnostic repo template.

## Prerequisites

Tools to install: [git][g], [pre-commit][pk], and [detect-secrets][ds].

You can use [this][a] playbook for automated tools installation(Ubuntu only).

## CD/CI

- `check` GitHub [workflow][wch].
- `release` GitHub [workflow][wr]. Release commit types: `fix`, `feat`.

## Contribute

- Commit message style - [Conventional Commits][cc].


[a]: https://github.com/IaroslavR/ansible-role-server-bootstrap
[cc]: https://www.conventionalcommits.org/en/v1.0.0/
[ds]: https://github.com/Yelp/detect-secrets#installation
[g]: https://www.atlassian.com/git/tutorials/install-git
[pk]: https://pre-commit.com/#install

[wch]: .github/workflows/checks.yml
[wr]: .github/workflows/release.yml

[checks]: https://github.com/cachuperia/blueprint-general/actions/workflows/checks.yml/badge.svg
[release]: https://github.com/cachuperia/blueprint-general/actions/workflows/release.yml/badge.svg
