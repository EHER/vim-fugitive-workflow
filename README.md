# vim-fugitive-workflow
My workflow for [vim-fugitive](https://github.com/tpope/vim-fugitive).

In order to have Vim configuration a bit easier to compose I'll extract
configurations for specific plugins into "workflow plugins". So it's something
that make sense for the way that I'm working but that can be removed once
the plugin is not used anymore.

## How to use it
I recommend to use [Plug](https://github.com/junegunn/vim-plug) but can be
any vim package manager or git clone inside ~/.vim/autoload.

A quick/durty/easy way to install Plug is like this:
```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

Then add this to you .vimrc
```vim
call plug#begin('~/.vim/my-stuff')
    Plug 'tpope/vim-fugitive'
    Plug 'EHER/vim-fugitive-workflow'
call plug#end()
```
Reload .vimrc and `:PlugInstall` to install plugins.

Enjoy! ;)
