# dotfiles

Managed with [chezmoi](https://www.chezmoi.io/).

## Managed Configurations

- **tmux**: `~/.config/tmux/tmux.conf`
- **Neovim**: `~/.config/nvim/init.lua`
- **Ghostty**: `~/.config/ghostty/config.ghostty`

## Quick Start on a New Machine

```bash
# Initialize and apply from GitHub
chezmoi init --apply https://github.com/fdkevin0/dotfiles.git
```

## Daily Usage

```bash
# Pull latest changes from remote and apply
chezmoi update

# Preview pending changes before applying
chezmoi diff

# Apply local source changes to $HOME
chezmoi apply

# Re-add modified files from $HOME into chezmoi source
chezmoi re-add
```
