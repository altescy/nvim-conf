Neovim Configurations
===

***Now neovim config is managed in [altescy/dotfiles](https://github.com/altescy/dotfiles) with other configs.***


### Install

```
% sudo apt-add-repository ppa:neovim-ppa/stable
% sudo apt update
% sudo apt install neovim
% sudo pip install -U neovim neovim-remote
% git clone https://github.com/altescy/nvim_conf.git ~/.config/nvim
```

### EditorConfig setup

see this: https://editorconfig.org/


### Language Support

- C/C++

```
% sudo apt install clang-tools-8
```

- Go

```
% go get -u golang.org/x/tools/cmd/gopls
```

- Python

```
% pip install python-language-server pylint mypy
```

- Rust

```
% rustup update && rustup component add rls rust-analysis rust-src
```
