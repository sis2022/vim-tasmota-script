# vim-tasmota-script
VIM Syntax highlighting for Tasmota scripting.

You may want to add an autocmd for tasmota script files (ending in '.ts') in '~/.vimrc':

'''
filetype on
if has("autocmd")
  au Syntax tasmota     runtime! syntax/tasmota.vim
  au BufRead,BufNewFile *.ts setfiletype tasmota
endif¬
'''
