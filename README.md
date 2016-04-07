# Charmm.vim

Syntax and indent files for CHARMM(https://www.charmm.org/charmm/)

Features included so far:

* Syntax highlighting for Charmm
* Filetype detection for `*.charmm.*` files

## Installation

### Plugin managers

Install with the most common plugin managers including [Vundle][vundle] and [pathogen.vim][pathogen].

With Vundle.vim:

1. Add line to `~/.vimrc` file:

  ```viml
  " Vundle
  Plugin 'jonnyjohannes/vim-charmm'
  ```

2. Install Plugins:

  Launch `vim` and run `:PluginInstall`
  
  To install from command line: `vim +PluginInstall +qall`

### Manual installation

Copy the contents of each directory in the respective directories inside
`~/.vim`.
