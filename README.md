
# 🛠️ Dotfiles: Neovim, Rofi, Alacritty, Kitty

This repository contains my personal configuration files (dotfiles) for:

- 📝 **Neovim** – Highly customizable modern Vim-based editor
- 🎨 **Rofi** – Lightweight and stylish app launcher
- 🖥️ **Alacritty** – GPU-accelerated terminal emulator
- 🐱 **Kitty** – Fast, feature-rich terminal with OpenGL support



# 📁 Directory Structure
``` text
.
├── nvim/ # Neovim config (usually ~/.config/nvim)
├── rofi/ # Rofi config and themes (usually ~/.config/rofi)
├── alacritty/ # Alacritty config (usually ~/.config/alacritty)
├── kitty/ # Kitty config (usually ~/.config/kitty)
└── README.md
```
## 🚀 How to Use

```bash
git clone https://github.com/your-username/dotfiles-nrk.git
cd dotfiles-nrk

# Neovim
mkdir -p ~/.config/nvim
cp -r nvim/* ~/.config/nvim/

# Rofi
mkdir -p ~/.config/rofi
cp -r rofi/* ~/.config/rofi/

# Alacritty
mkdir -p ~/.config/alacritty
cp -r alacritty/* ~/.config/alacritty/

# Kitty
mkdir -p ~/.config/kitty
cp -r kitty/* ~/.config/kitty/
