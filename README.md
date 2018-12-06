# JonMontgo Tmux Config

## Install

Clone config into ~/.tmux *(assumes no previous .tmux)*
```sh
https://github.com/JonMontgo/tmux-config.git ~/.tmux
```

Link tmux config to home
```sh
ln -s ~/.tmux/.tmux.conf ~/.tmux.conf
```


Clone tpm into ~/.tmux
```sh
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```


Reload tmux environment so tpm is sourced
*Type this in when running tmux*
```sh
tmux source ~/.tmux.conf
```
