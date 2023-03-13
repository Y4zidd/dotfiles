# AwesomeWM 

### Dependencies

```
yay -S awesome-git picom-git zsh redshift thunar kitty rofi rofi-emoji xclip scrot gvfs ttf-jetbrains-mono noto-fonts noto-fonts-cjk networkmanager lxappearance materia-gtk-theme papirus-icon-theme lsd playerctl brightnessctl pipewire pipewire-alsa pipewire-pulse alsa-utils acpi
```

### Install

```
git clone --recurse-submodules https://github.com/Y4zidd/dotfiles.git
cd dotfiles
cp -r config/awesome/* ~/.config/awesome
cp -r config/picom/* ~/.config/picom
cp -r config/fontconfig/* ~/.config/fontconfig
cp -r config/kitty/* ~/.config/kitty
cp -r config/rofi/* ~/.config/rofi
cp -r fonts/* ~/.local/share/fonts
```
