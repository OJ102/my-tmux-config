# my tmux config

Personal tmux configuration. Commited to Github for cross device usage.

## Key bindings

- Prefix: `C-s` (I switched my capslock to ctrl)
- `prefix r` — reload config
- `prefix C-p` / `prefix C-n` — previous/next window
- `h/j/k/l` — vim-style pane navigation
- Mouse support enabled (Don't judge)

## Plugins

Installed/managed via [tpm](https://github.com/tmux-plugins/tpm) (`prefix I` to install).

- **tpm** — tmux plugin manager, loads and updates all other plugins
- **catppuccin/tmux** — status line theme (mocha flavor)
- **tmux-cpu** — shows CPU usage in status line
- **tmux-battery** — shows battery status in status line
- **tmux-sensible** — sane baseline tmux settings
- **tmux-resurrect** — saves and restores tmux sessions (panes, windows, layout)
- **tmux-continuum** — auto-saves sessions every 30 min and auto-restores on tmux start (uses resurrect)
- **tmux-yank** — copy tmux selections to system clipboard
- **tmux-open** — open highlighted file/URL from copy mode
