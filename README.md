# Tmux dot files

Create the Tmux config directory: `mkdir ~/.config/tmux`

Place `tmux.conf` inside the Tmux config directory.

Place the files inside `scripts/` in `~/.local/bin/` and `chmod +x` each one of them. Then, add the following to `.zshrc` if you'll like to run them from the raw command line.
* For the tmux-sessionizer:
`alias tmux-sessionizer='~/.local/bin/tmux-sessionizer'`

Run this line `git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm`

Run `source ~/.config/tmux/tmux.conf`
