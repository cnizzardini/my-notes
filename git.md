# GIT

GIT things.

### Commands

Deleting multiple local branches:

```console
git branch | grep "<pattern>" | xargs git branch -D
```

### Forks

Tracking an upstream fork:

```console
git remote add upstream git@github.com:VENDOR/PROJECT.git
git fetch upstream
git checkout --track upstream/BRANCH_NAME
```

> Sources: 
> 
> https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/configuring-a-remote-for-a-fork
> https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork

### Checking out branches from forks

```console
git fetch origin pull/3/head:my_new_branch
git checkout my_new_branch
```

> Source:
> https://stackoverflow.com/questions/62432498/how-do-i-checkout-a-pr-from-a-fork
