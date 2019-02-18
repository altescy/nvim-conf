Neovim Configurations
===

configuration files for neovim


### Install

```
% sudo apt-add-repository ppa:neovim-ppa/stable
% sudo apt update
% sudo apt install neovim
% sudo pip install -U neovim neovim-remote
% git clone https://github.com/altescy/nvim_conf.git ~/.config/nvim
```

### Supported Languages

- Crystal
  - `rhysd/vim-crystal`
- Go
  - `fatih/vim-go`
- Julia
  - `JuliaEditorSupport/julia-vim`
- Haskell
  - `kana/vim-filetype-haskell`
  - `vim-stylish-haskell`
- Markdown
  - `plasticboy/vim-markdown`
  - `godlygeek/tabular`
- Python
- Rust
  - `rust-lang/rust.vim`
  - `racer-rust/vim-racer`
- Scala
  - `derekwyatt/vim-scala`


#### Rust
```
% apt install build-essential cmake pkg-config zlib1g-dev libssl-dev
% rustup toolchain add nightly
% cargo +nightly install racer
```

#### Haskell
```
% stack install stylish-haskell
```

#### LaTeX
```
% sudo apt install latexmk
% pip install -U neovim-remote
% cat << EOF > ~/.latexmkrc
#!/usr/bin/perl

$latex         = 'platex %O %S';
$biber         = 'biber %O -u -U --output_safechars %B';
$bibtex        = 'upbibtex %O %B';
$dvipdf        = 'dvipdfmx %O -o %D %S';
$makeindex     = 'mendex %O -o %D %S';
$pdf_mode      = '3'; # .tex -> .dvi -> .pdf
$pdf_previewer = 'start evince %O %S';
EOF
```
