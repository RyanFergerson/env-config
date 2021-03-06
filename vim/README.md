# Vim Configuration
* font: FiraCode
* colorscheme: Gruvbox

## Features
* Leader system
* Shared/Private configuration

## Installation

**Clone repo**
``` sh
git clone https://github.com/RyanFergerson/THC.git
```
**Place inside ~/.vimrc**
``` sh
source ~/Code/THC/vim/rc.vim
```
**Place inside ~/.gvimrc (for MacVim/gVim)**
``` sh
source ~/Code/THC/vim/grc.vim
```
**Place inside ~/.ideavimrc (for JetBrains)**
``` sh
source ~/Code/THC/vim/jetbrains.vim
```
**Install Vundle**
``` sh
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
**Install Plugins**
``` vim
:PluginInstall
```

## Leader system

**A leader key with two characters can (with just the alphabet alone) create 456,976 key combinations!**

Case sensitve, mixed case characters make different commands
* \<leader\>ff
* \<leader\>FF
* \<leader\>Ff
* \<leader\>fF
