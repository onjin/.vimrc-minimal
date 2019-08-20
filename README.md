# Minimal .vimrc configuration

To quick start and edit on remote machines.

## Quickstart

Ensure `curl` and `git` are  installed. They are required to perform autoinstall
vim plugin manager.

Then run:

```
curl https://raw.githubusercontent.com/onjin/.vimrc-minimal/master/.vimrc > .vimrc
```

and start vim.

Auto instalation of plugin manager and base plugins should be done

![screenshot](https://github.com/onjin/.vimrc-minimal/raw/master/screenshot.png "Screenshot")



## Details

At first start vim will auto install vim-plug https://github.com/junegunn/vim-plug
and a few plugins:

 * editorconfig/editorconfig-vim - support for .editorconfig file
 * vim-airline/vim-airline - status line
 * junegunn/fzf', { 'dir': '~/.fzf', 'do': './install --all' } - fuzzy finder
 * junegunn/fzf.vim' - fuzzy finder vim plugin

## Requirements

You have to install `git` and `curl` to autoinstall and use package manager.
