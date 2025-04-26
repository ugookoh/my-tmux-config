# Intro
I am adding some of my configurations here so that I can easily replicate them when I move to another system

# Installing Tmux

Clone tmux
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Create a tmux file using `touch ~/.tmux.conf` and put the tmux script there. You can find it in the repo.

Go into an active `tmux` terminal by opening a new terminal and entering `tmux`, then source by running

```
tmux source-file ~/.tmux.conf
```

Once reloaded, press this key combo inside tmux:
```
Prefix + I
Prefix is usually Ctrl-b, so: Ctrl-b I
```
This installs all the plugins defined with set -g @plugin.
