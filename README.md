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
sudo pacman -S kitty wofi dunst firefox pavucontrol git neovim zsh stow ripgrep tree github-cli lazygit ttf-font-awesome ttf-agave-nerd pcmanfm-qt unzip doplphin php
yay -S nvm
```
# install oh my zsh

https://ohmyz.sh/

# Clone dotfiles

Clone these dotfiles into ~, cd into the directory and run:

```
stow . 
```

Resolve all potential default that come from default configs already existing

# Fonts

Kitty is using a nerd fotn: Agave
make sure it's installed
