gtk2-vim-zoom
==============

This script is copied from [vim wiki](http://vim.wikia.com/wiki/Change_font_size_quickly) 
in order to manage it with [Vundle](https://github.com/gmarik/vundle).

It can zoom in/out font size with single command in gtk2 based gvim(e.g. gnome-vim).

Install
--------------

### With vundle

Add below code into your _~/.vimrc_

    Bundle 'crusoexia/gtk2-vim-zoom'

### Other methods

If you don't use vundle, download the _vim-zoom.vim_ and use it in your preferred method, anyway,
it just works.

Usage
--------------

___:LargerFont___ - zoom in

___:SmallerFont___ - zoom out

Map the commands with shotcuts to make it handy:

    nnoremap <silent> <C-UP> :LargerFont<CR>
    nnoremap <silent> <C-DOWN> :SmallerFont<CR>
