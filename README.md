# Ubuntu Dotfiles
1. Install the must have apps
```bash
sudo apt install stow zsh tmux neovim starship ripgrep zoxide eza fzf
```

```bash 
curl -sS https://starship.rs/install.sh | sh

LAZYGIT_VERSION=$(curl -s "https://api.github.com/repos/jesseduffield/lazygit/releases/latest" | \grep -Po '"tag_name": *"v\K[^"]*')
curl -Lo lazygit.tar.gz "https://github.com/jesseduffield/lazygit/releases/download/v${LAZYGIT_VERSION}/lazygit_${LAZYGIT_VERSION}_Linux_x86_64.tar.gz"
tar xf lazygit.tar.gz lazygit
sudo install lazygit -D -t /usr/local/bin/
```
```
```

2. Set shell to `zsh` 
```bash
chsh -s $(which zsh)
```

