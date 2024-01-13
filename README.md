# Tmux dot files

## Installation
Clone this repo inside you .config folder:
```bash
git clone https://github.com/asilvam133/.tmux.git ~/.config/tmux
```

Clone Tmux Plugin Manager:
```bash
git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm
```

## The Primeagen's Tmux Sessionizer
Place `scripts/tmux-sessionizer` in `~/.local/bin/` and run `chmod +x ~/.local/bin/tmux-sessionizer`.

## Load config and install plugins

Then, open a Tmux session by running `tmux`. The session name is not important, because the tmux-sessionizer will name it after the project (directory) name.

Run `source ~/.config/tmux/tmux.conf`

Just to make sure the configuration is loaded, run `prefix+d` to detach from the current from the current session.

*IMPORTANT - The prefix is `Ctrl+a` in this config*

Run `tmux kill-server`. Then open a Tmux a session by running `tmux`.

Finally, run `prefix+I` to install the plugins available in the `tmux.conf` file.

By default, there are only two plugins:
* nhdaly/tmux-better-mouse-mode: Improves using the mouse to scroll up/down.
* tmux-plugins/tmux-sessionist: Gives some extra capabilities to handle Tmux sessions while we are already in a Tmux session. For instance:
    * `prefix+C` will create a new session without detaching.
    * `prefix+X` will delete the current session and will move to another session after.


## Some notes
Check The Primeagen's dot files to check the original tmux-sessionizer.

I try to have the UI as minimal as possible, so right now I only change the background to blend with my terminal background.
