# Install arch

Install arch using archinstall

It's easiest if you choose sway as your desktop profile in the archinstall tui 

# Install yay

https://github.com/Jguer/yay

```
sudo pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si
```

# install additional packages

```
sudo pacman -S kitty dunst firefox git neovim zsh stow tree github-cli lazygit noto-fonts-emoji
yay -S rofi-lbonn-wayland
```
# install oh my zsh

https://ohmyz.sh/

# Clone dotfiles

Clone these dotfiles into ~, cd into the directory and run:

```
stow . 
```

Resolve all potential default that come from default configs already existing
