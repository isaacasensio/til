# List outdated packages
```bash
$ brew outdated
```

# Skip some packages to be upgraded
```bash
$ brew upgrade `brew outdated | grep -v ansible`
```

# Update, upgrade and clean up Homebrew packages

- Updates Hombrew package manager.
- Upgrades all previously installed packages.
- Removes old versions of previously installed packages.

```bash
$ brew update && brew upgrade && brew cleanup
```
