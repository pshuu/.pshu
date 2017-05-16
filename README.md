.pshu - My Dotfile Repository
=============================

Minimal and based on Vim and Zsh. For productivity, not laziness.

Dependencies
------------

* fasd

Installation
------------

Use your favourite package manager to get fasd.

Clone the repository into your home directory:

`git clone --recursive https://github.com/mikopits/.pshu ~/.pshu`

Backup the following files in your home directory, if they exist.
Then create the appropriate symlinks:
```bash
ln -s .pshu/tmux/tmux.conf .tmux.conf
ln -s .pshu/vim .vim
ln -s .pshu/vim/vimrc .vimrc
ln -s .pshu/zsh/zpreztorc .zpreztorc
ln -s .pshu/zsh/zshrc .zshrc
```

Create the following symlinks if zprezto isn't loading.
```bash
ln -s .pshu/zsh/zprezto/runcoms/zprofile .zprofile
ln -s .pshu/zsh/zprezto/runcoms/zshrc .zshrc
```

Use `vimp` to edit your vim plugins, and `vimu` to install them.
