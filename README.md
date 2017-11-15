# MacOS Setup

This is my highly opinionated macOS Setup.
It is structured into this general readme, [Apps](APPS.md), Sublime and Dotfiles.

## Install dependencies

### Xcode Command Line Tools

```bash
xcode-select --install
```

### Homebrew

Homebrew is the missing package manager for macOS.

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## Install homebrew formulae

```bash
./brew.sh
```

## Set sensible macOS defaults

```bash
./.macos
```

## Install Apps

```bash
./mas.sh
./cask.sh
```

## Copy dotfiles

```bash
./bootstrap.sh
```
