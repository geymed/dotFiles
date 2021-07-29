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

