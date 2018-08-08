# package-sets

[![Build Status](https://travis-ci.org/purescript/package-sets.svg?branch=master)](https://travis-ci.org/purescript/package-sets)

Hosts and builds PureScript package sets for `psc-package` using Travis.

## Usage

To learn how to use and contribute to package sets, please see the documentation in the [psc-package repository](https://github.com/purescript/psc-package)

## Conventions

For each new snapshot create a git tag using following command (fish shell):
```shell:fish
set -lx tag "psc-0.12.0-"(date --utc +"%Y%m%d-%H%M"); git tag -a $tag -m $tag
git push origin master --tags
```
