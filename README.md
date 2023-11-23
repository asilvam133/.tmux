# Tmux dot files

Place `.tmux.conf` in the user root folder.

Place the files inside `scripts/` inside `~/.local/bin/` and `chmod +x` each one of them. Then, add the following to `.zshrc` if you'll like to run them from the raw command line.
* For the tmux-sessionizer:
`alias tmux-sessionizer='~/.local/bin/tmux-sessionizer'`

Run this line `git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`

Run `source ~/.tmux.conf`
