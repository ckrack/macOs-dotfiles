# MacOS Setup

This is my highly opinionated macOS Setup.
It is structured into this general readme, [Apps](APPS.md), [Sublime](SUBLIME.md) and [Dotfiles](DOTFILES.md).

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

### Install homebrew formulae

```bash
brew install node yarn git git-flow bash bash-completion mas cask homebrew-bundle m-cli
```

Now make the homebrew installed bash your default

```bash
sudo -s
echo /usr/local/bin/bash >> /etc/shells
chsh -s /usr/local/bin/bash
```

### Frontend tools

```bash
brew install node yarn
```

### Backend dependencies

```bash
brew install php71 composer phpunit php-code-sniffer pdepend php-cs-fixer phpcpd phpmd
```

## Generate SSH Key

Follow the steps.

```bash
ssh-keygen -t rsa
```

**Never share your private key with anyone!**

## App Suggestions

- [Sublime Text](https://www.sublimetext.com/) Text editor
- [Sourcetree](https://www.sourcetreeapp.com/) Git client
- [Filezilla](https://filezilla-project.org/) SFTP client
- [Sequel Pro](https://www.sequelpro.com/) SQL client
- [iTerm2](https://www.iterm2.com/) Terminal client
- [Postman](https://www.getpostman.com/) API client
