# Neovim Configs
This repository holds the source code of Chaminn's Neovim

## Quickstart

-   Install [Git](https://git-scm.com/)
-   Install [Neovim](https://neovim.io/)
-   Create init.vim config file into .config dir
    ```
    set runtimepath^=~/.vim runtimepath+=~/.vim/after
    let &packpath = &runtimepath
    source ~/.vimrc
    ```
    -   For windows create file in C:\Users\$YOURUSER\AppData\Local\nvim
-   Clone this repository into .config dir
-   Create symbolic links to .vimrc and .vim
-   Install Vim-Plug 
    ```
    curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
    ```
## Plugins Install

-   Open NeoVim
-   Execute :PlugInstall
-   Restart NeoVim
