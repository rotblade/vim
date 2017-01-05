set nocompatible             " Required by Vundle 
filetype off                 " Required by Vundle 

" set the runtime path to include Vundle and initialize 
set rtp+=~/.vim/bundle/Vundle.vim 

call vundle#begin() 
Plugin 'VundleVim/Vundle.vim' 
Plugin 'tmhedberg/SimpylFold' 
Plugin 'vim-scripts/indentpython.vim' 
Plugin 'altercation/vim-colors-solarized' 
Plugin 'Lokaltog/vim-powerline' 
Plugin 'scrooloose/syntastic' 
call vundle#end()            " Required by Vundle 
filetype plugin indent on    " Required by Vundle 

syntax enable
set background=dark 
let g:solarized_termcolors=256
colorscheme solarized 

au BufNewFile,BufRead *.py,*.js set tabstop=4 softtabstop=4 shiftwidth=4 

au BufNewFile,BufRead *.html,*.css,*.yml,*.yaml,*.txt,*.rst set tabstop=2 
       \ softtabstop=2 
       \ shiftwidth=2 

"splitt && windows navigations 
set splitbelow 
set splitright 
nnoremap <C-J> <C-W><C-J> 
nnoremap <C-K> <C-W><C-K> 
nnoremap <C-L> <C-W><C-L> 
nnoremap <C-H> <C-W><C-H> 

" Enable folding 
set foldmethod=indent 
set foldlevel=99 
nnoremap <space> za 
let g:SimpylFold_docstring_preview=1 

" disable cursor lighting 
set gcr=a:block-blinkon0 
" show status bar 
set laststatus=2 
" show cursor current position 
set ruler 
" show line number 
set number 
" highlight current row/column 
set cursorline 
set cursorcolumn 

set textwidth=79 
set expandtab 
set autoindent 
set fileformat=unix 
set encoding=utf-8 
set fileencoding=utf-8

