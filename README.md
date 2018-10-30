## Introduction

这是为 fork 来的 vimrc，来自 [fuh/vimrc](https://github.com/fuh/vimrc)。之前用过那个 star 数最多的那个 vimrc。然后。。。反正现在换了一个 vimrc。之前那个很全很强大，但是 README 太多了，所以找了个稍微 minimal 来。

原作者的 README 在 [README_ORIGIN.md](./README_ORIGIN.md)

## Installation

1. Backup your old vim configuration files:

        mv ~/.vim ~/.vim.orig
        mv ~/.vimrc ~/.vimrc.orig

2. Clone and install this repo:

        git clone https://github.com/hfucn/vimrc.git ~/.vim
        ln -s ~/.vim/vimrc ~/.vimrc

3. Setup `Vundle`:

        git clone https://github.com/VundleVim/Vundle.vim ~/.vim/bundle/Vundle.vim

4. Install bundles. Launch vim(ignore the errors and they will disappear after installing needed plugins)and run:

        :PluginInstall

## Vim

vim 的基本功能就不介绍了。

## Plugin

这个 vimrc 是用 `vundle` 来管理插件的。

### Code Completion

- neocomplcache，补全
- snipMate，code snippets
- supertab
- delimitMate，括号补全

### Navigation

- matchit，`%` 匹配
- easyMotion，跳转

### Edit

- surrround，快速删除，替换
- nerdcommenter，快速注释，`<leader>` + `c` + `<space>`
- tabular，对齐
- IndentGuides，缩进助手，`F4`

### IDE

- nerdtree，目录树，`F5`
- tabbar，tab bar
- tagbar，显示 file 的 tag，`F6`
- ack-vim，查找的，`<leader>` + `a`
- ctrlp，mru 什么的，`Ctrl` + `p`
- powerline，ultimate 状态条
- fugitive, Git wrapper
- syntastic，Syntax checking
