# Tmux config
## Prerequisites:
- Install [fzf](https://github.com/junegunn/fzf/) to be used for [tmux-fzf](https://github.com/sainnhe/tmux-fzf)
- For [vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator), also need to set up vim-tmux-navigator for neovim


## Keybindings
Prefix is `Ctrl-b`
Meta is `Alt` in Linux. Meta is `Option` key in MacOS but this needs to be enabled in the terminal

- `prefix + I`
    - Install plugins
- `prefix + m`
    - Mark pane
- `prefix :join-pane`
    - Joins a marked pane in the current window
- `prefix :break-pane`
    - Breaks out the current pane as a separate window
