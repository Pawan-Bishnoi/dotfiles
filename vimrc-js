call plug#begin('~/.vim/bundle')

" make sure to use single quotes

Plug 'https://github.com/scrooloose/nerdtree.git'
Plug 'Valloric/YouCompleteMe'
Plug 'https://github.com/vim-syntastic/syntastic.git'
Plug 'https://github.com/Lokaltog/vim-distinguished.git'
Plug 'https://github.com/easymotion/vim-easymotion.git'
Plug 'wookiehangover/jshint.vim'
Plug 'https://github.com/pangloss/vim-javascript.git'
Plug 'https://github.com/goatslacker/mango.vim.git'
Plug 'https://github.com/tpope/vim-fugitive.git'

call plug#end()

set mouse=a " always enable mouse movements  v/a/r
set hlsearch
set shiftwidth=4
set tabstop=4

set background=dark     " you can use `dark` or `light` as your background
syntax on
color mango

" you_complete_me conf
let g:ycm_server_python_interpreter = '/usr/bin/python'


" start syntastic conf
set statusline+=%#warningmsg#
set statusline+=%{SyntasticStatuslineFlag()}
set statusline+=%*

let g:syntastic_always_populate_loc_list = 1
let g:syntastic_auto_loc_list = 1
let g:syntastic_check_on_open = 0
let g:syntastic_check_on_wq = 0
" end syntastic

" easy motion conf
map \ <Plug>(easymotion-prefix)
nmap \s <Plug>(easymotion-overwin-f2)
map \j <Plug>(easymotion-j)
map \k <Plug>(easymotion-k)

" jshint.vim conf
let JSHintUpdateWriteOnly=1

" vimjavascript conf
let g:javascript_plugin_jsdoc = 1
let g:javascript_plugin_ngdoc = 1
let g:javascript_plugin_flow = 1

" PERFORMANCE KILLER !!   Disable if vim is slow
" augroup javascript_folding
"     au!
"     au FileType javascript setlocal foldmethod=syntax
" augroup END
