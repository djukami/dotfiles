# Will's dotfiles

## dotfiles

There are many dotfiles, but this one is mine.

## install

Run this:

```sh
git clone https://github.com/djukami/dotfiles.git ~/dotfiles
~/dotfiles/bin/install_dotfiles
```

This will backup your existing important files (see `~/dotfiles/backup`) and install versions that link to the dotfiles' implementations.

It also creates `.bashrc.local` and `.gitconfig.local` for you to put private data (e.g. GitHub API keys).

## Why?

My eventual goal is to have a series of scripts that I can run on a machine to get it running how I like it.
