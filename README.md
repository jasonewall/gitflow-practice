# Practicing git-flow commands

This is me trying to figure out how to use git-flow with github protected branches on `develop`, `master`, & `release/*`

## Features

1. `git flow feature start some-description`
1. `git flow feature publish` - pushes the branch up and sets up tracking

## Bugfixes

1. `git flow bugfix start fix-bug-in-release release/version-number`
1. Make changes
1. `git flow bugfix publish`

## Migrations

1. Can we auto merge things from master into a protected branch via githooks?

## CI

1. Still trying to fake CI
