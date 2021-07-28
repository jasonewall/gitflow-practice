# Practicing git-flow commands

This is me trying to figure out how to use git-flow with github protected branches on `develop`, `master`, & `release/*`

## Features
1. `git flow feature start some-description`
1. Make Changes
1. `git flow feature publish` - pushes the branch up and sets up tracking
1. Make PR

## Bugfixes
1. `git flow bugfix start fix-bug-in-release release/version-number`
1. Make changes
1. `git flow bugfix publish`
1. Make PR

## Creating a release
1. ys flow build release

## Creating a hotfix
1. ys flow build hotfix
1. Make & commit changes
1. `git flow hotfix publish`
1. Make PR

## Migrations
1. Can we auto merge things from master into a protected branch via githooks?
    - No
1. If CI passing is the only check can we still use merge commits from PRs to push to this branch?
    - Yes
1. Can we push to multiple protected branches in the same command if checks are passing for both?
    - Yes
1. What about a PR destined for a different branch?
    - No
