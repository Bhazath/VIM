# NVIM
- to downlaod nvim

```
apt install nvim
```

- Create .config/nvim/init.vim
- OR Create ~/.vimrc
  
```
" Enable line numbers
set number

" Enable relative line numbers
set relativenumber

" Enable syntax highlighting
syntax on

" Set the theme (use a simple theme similar to VSCode's default)
colorscheme desert

" Enable mouse support
set mouse=a

" Set tab behavior to spaces and define tab width
set tabstop=4
set shiftwidth=4
set expandtab

" Enable auto-indentation
set autoindent
set smartindent

" Highlight current line
set cursorline

" Show matching parentheses
set showmatch

" Enable line wrapping
set wrap

" Set the status line to always display
set laststatus=2

" Enable search highlighting and incremental search
set hlsearch
set incsearch

" Enable file type detection and plugin support
filetype plugin indent on

" Display a ruler
set ruler

" Set UTF-8 encoding
set encoding=utf-8

" Configure clipboard to use the system clipboard
set clipboard=unnamedplus

" Disable swap file creation
set noswapfile

" Disable backup file creation
set nobackup
set nowritebackup

" Set split window behavior (similar to VSCode's editor layout)
set splitright
set splitbelow

" Set up a simple status line
set statusline=%F%m%r%h%w\ [%{&ff}]\ [%Y]\ [%p%%]\ [%l,%c]

" Remove the mode display (we don't need to see -- INSERT -- anymore)
set showmode

" Set wildmenu for command line completion
set wildmenu
set wildmode=list:longest

" Set command line height to 2 for better visibility
set cmdheight=2

" Enable hidden buffers
set hidden

" Set folding method to syntax (you can use indent if you prefer)
set foldmethod=syntax
set nofoldenable

```
