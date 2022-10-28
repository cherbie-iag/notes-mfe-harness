# Notes MFE Harness


## Submodules Cheat Sheet

How to initialize the repositories `git submodules`:

```zsh
git submodule update --init --recursive
```

How to update/checkout to relevant `submodule` commits:

```zsh
# git reset --hard HEAD
git pull
git submodule update --checkout
```

> Note: `git submodule update --checkout` will fail if there are changes on your local commit HEAD. These need to be resolved by either committing, stashing or deleting them.