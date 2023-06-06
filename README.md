# My configs:

*Heads up*: **This package should better go to `~/Projects/dotfiles` unless you want to modify the dir paths for the scripts**

## zshrc
[TBD]

## vimrc

1. Copy the contents from `vim/.vimrc` to your PC
1. Close or source the file
1. Install [VimPlug](https://github.com/junegunn/vim-plug#vim)
1. Open `.vimrc` and run `:PlugInstall`

## nvim

1. Run `sudo apt install neovim`
1. Create `~/.config/nvim` dir and copy the `nvim/init.vim` file
1. Close or source the file
1. Install [VimPlug](https://github.com/junegunn/vim-plug#neovim)
1. Open `vim.init` and run `:PlugInstall`
1. For `coc.vim` go to `~/.local/share/nvim/plugged/coc.nvim` and [run](https://github.com/neoclide/coc.nvim/issues/3258):
```
yarn install
yarn build
```
1. For `markdown-preview.nvim` [run](https://github.com/iamcco/markdown-preview.nvim) (use node version 16.20.0):
```
mkdir -p pack/packer/start
cd pack/packer/start
git clone https://github.com/iamcco/markdown-preview.nvim.git
cd markdown-preview.nvim
yarn install
yarn build
```


Interesting cofigs from others:
* https://github.com/NeuralNine/config-files/blob/master/init.vim

## tmux

1. Copy file `.tmux.conf` to HOME

Check these if you see any trouble:
* https://github.com/romkatv/powerlevel10k/issues/1656
* https://github.com/tmux/tmux/wiki/Installing
