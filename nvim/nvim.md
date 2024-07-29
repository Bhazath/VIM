# NVIM
- to downlaod nvim

```
apt install nvim
```

- Create .config/nvim/init.vim
- OR Create ~/.vimrc
 
```
set number
set hlsearch
set mouse=a
syntax on
set cursorline 
:highligh Cursorline cterm=bold ctermbg=black

set ignorecase 
set smartcase

set tabstop =4
set softtabstop =4
set shiftwidth =4
set textwidth =79
set expandtab
set autoindent

set showmatch

if !has('gui_running')
    set t_Co=256
endif

" Auto-completion for braces, brackets, quotes, etc.
inoremap { {}<Esc>i
inoremap ( ()<Esc>i
inoremap [ []<Esc>i
inoremap " ""<Esc>i
inoremap ' ''<Esc>i
inoremap ` ``<Esc>i
```

```
" Enable line numbers
set number

" Enable search highlighting
set hlsearch

" Enable mouse support
set mouse=a

" Enable syntax highlighting
syntax on

" Highlight the current line
set cursorline
highlight Cursorline cterm=bold ctermbg=black

" Ignore case in search patterns
set ignorecase

" Override the ignorecase option if the search pattern contains uppercase letters
set smartcase

" Set tab behavior and indentation
set tabstop=4
set softtabstop=4
set shiftwidth=4
set textwidth=79
set expandtab
set autoindent

" Show matching parentheses
set showmatch

" Set color support for terminal if not running in a GUI
if !has('gui_running')
    set t_Co=256
endif

" Auto-completion for braces, brackets, quotes, etc.
inoremap { {}<Esc>i
inoremap ( ()<Esc>i
inoremap [ []<Esc>i
inoremap " ""<Esc>i
inoremap ' ''<Esc>i
inoremap ` ``<Esc>i

```
