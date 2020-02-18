## Force-based Git Guide

### Undoing changes (pushed and not) with keeping them locally
```shell
git reset --hard <commit hash> # DANGER: Do not keeping changes in local files.
git reset --mixed <commit hash> # Resetting history, and marking undoed changes unstaged (red).
git reset --soft <commit hash> # Resetting history, and marking undoed changes staged (green).
git reset <commit hash> # Looks like it set by default as --mixed
```
