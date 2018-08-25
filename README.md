Neovim Configurations
===

configuration files for neovim


### Install

```
sudo apt-add-repository ppa:neovim-ppa/stable
sudo apt update
sudo apt install neovim
sudo pip install -U neovim
git clone https://github.com/altescy/nvim_conf.git ~/.config/nvim
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
% sudo apt install build-essential cmake pkg-config zlib1g-dev libssl-dev
% rustup toolchain add nightly
% cargo +nightly install racer
```

#### Haskell
```
% stack install stylish-haskell
```
