# Dotfiles

Dotfiles for:
 * Vim
 * Mutt
 * Zsh

## Installing

Clone repo with submodules:

```
cd ~
git clone --recursive https://github.com/w1zdun/dotfiles.git
```

Move dotfiles to home:
```
cd dotfiles
mv .* ~
rm -fr dotfiles
```

Or:
```
cd ~
git init
git remote add origin https://github.com/w1zdun/dotfiles.git
git pull origin master
git submodule update --init --recursive
```

## Acknowledgments

* vimrc heavily based on [Tomasz Święcicki <tomislater@gmail.com>](https://github.com/tomislater/dotfiles.git) config
* zsh from grml.org 
