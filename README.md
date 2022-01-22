## TMUX
You will first need to clone [tpm](https://github.com/tmux-plugins/tpm)

```sh
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Then copy tmux config to your home dir

```sh
cp .tmux.config ~
```

Then if tmux is already running type this in terminal:

```sh
tmux source ~/.tmux.conf
```

And finally, to install plugins, press `prefix` + `I` (capital i, as in Install).

## Vim

Copy `.vimrc` to your home dir 
```sh
cp .vimrc $HOME/.vimrc
```

Create a `~.vim/bundle` folder and clone `Vundle.vim` into it

```sh
mkdir -p ~.vim/bundle 
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

Install **One Dark** theme as [explained here](https://github.com/joshdick/onedark.vim#installation)

Install vim plugins
```
vim +PluginInstall +qall
```



