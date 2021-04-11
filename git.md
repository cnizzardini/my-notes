# GIT

GIT things.

## Commands

Deleting multiple local branches:

```console
git branch | grep "<pattern>" | xargs git branch -D
```

## Forks

```console
git remote add upstream git@github.com:cakephp/cakephp.git
git fetch upsream
```

https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/configuring-a-remote-for-a-fork
https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork
