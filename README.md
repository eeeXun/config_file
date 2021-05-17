# vim

```sh
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
- Vundle with markdown-preview
    - call mkdp#util#install()
```sh
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

# neovim

```sh
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
- sudo pacman -S xclip

# coc.nvim
- sudo pacman -S nodejs # (for coc.nvim)
- sudo pacman -S yarn # (for coc.nvim)
- sudo pacman -S ripgrep # (for CocSearch)
- sudo pacman -S ccls
- pip3 install jedi-language-server
- pip3 install mypy # (for python diagnostics)
- sudo pacman -S gopls

# bspwm
- sudo pacman -S bspwm
- sudo pacman -S sxhkd
- sudo pacman -S polybar

# dwm
- sudo mv ./systemSetting/dwm.desktop /usr/share/xsessions/

## Source of dwm
- source
    - [Luke Smith](https://github.com/LukeSmithxyz/dwm)
- patches
    - [systray](https://dwm.suckless.org/patches/systray/dwm-systray-20200914-61bb8b2.diff)
    - [focusonclick](https://dwm.suckless.org/patches/focusonclick/dwm-focusonclick-20200110-61bb8b2.diff)
    - [focusonnetactive](https://dwm.suckless.org/patches/focusonnetactive/dwm-focusonnetactive-6.2.diff)

# Packages
- sudo pacman -S termite
- sudo pacman -S dmenu
- sudo pacman -S feh
- sudo pacman -S flameshot
- sudo pacman -S picom
    - `touch ~/.config/picom.conf`

# zsh
- paru -S zsh-theme-powerlevel10k-git
- chsh -s /bin/zsh

# lf
- paru -S lf
- sudo pacman -S source-highlight
- sudo pacman -S mdcat
- pip3 install ueberzug
- sudo pacman -S atool
- sudo pacman -S pandoc

# font
- paru -S nerd-fonts-hack
- sudo pacman -S noto-fonts-emoji
- paru -S noto-fonts-tc

# touchpad
- sudo mv 01-touchpad.conf /etc/X11/xorg.conf.d/01-touchpad.conf
