# Installation

Recommended that you use [vundle](https://github.com/gmarik/vundle) to install.  Here is what the start of my
vimrc looks like:

    set nocompatible
    filetype off
    set rtp+=~/.vim/bundle/vundle
    call vundle#rc()
    Bundle 'gmarik/vundle'
    """ ...
    Bundle 'clord/vim-insfile'
    Bundle 'clord/vim-bookmaster'
    Bundle 'clord/vim-scenario'

    " :BundleInstall will ensure these are all installed, if vundle is available

    syntax enable " Must come after the Bundle commands so that syntax highlighting is available
    filetype plugin indent on


:BundleInstall will install from github.

