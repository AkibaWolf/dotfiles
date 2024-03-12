# Configuration files and settings

This directory contains the dotfiles for system and applications

## Requirements

Ensure you have the following installed on your system

### Git

#### Arch Linux

```
pacman -S git
```

#### Debian

```
apt install -y git
```

### Stow

#### Arch Linux

```
pacman -S stow
```

#### Debian

```
apt install -y stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/AkibaWolf/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
