dotfiles
========

A collection of my personal dotfiles. Here's a little preview of what it can look like:

![screenshot-ubuntu](screenshot-ubuntu.png)

![screenshot](screenshot.png)

Ps: Yes i'm using windows with cygwin in this screenshot, haters gonna hate.

Inpired by: https://github.com/hamvocke/dotfiles


Installation
------------

Clone this repository:

    git clone https://github.com/edbizarro/dotfiles.git ~/.dotfiles

### Using [GNU Stow](https://www.gnu.org/software/stow/) _(recommended)_
Install GNU Stow _(if not already installed)_

    Mac:      brew install stow
    Ubuntu:   apt-get install stow
    Fedora:   yum install stow
    Arch:     pacman -S stow

Then simply use stow to install the dotfiles you want to use:

    cd ~/.dotfiles
    stow vim
    stow tmux
    stow git
    stow zsh
    stow bash
    stow ssh
    stow base16-shell

Use base16 colors
-----------------
To get the most out of my dotfiles I recommend installing [base16-shell](https://github.com/chriskempson/base16-shell) on your system. This will allow you to have unified colors in all your command line applications. If you see that some colors are off when using my setup, installing base16-shell is most likely the way to fix it.
