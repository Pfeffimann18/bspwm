# bspwm
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Pfeffimann18/bspwm)
![GitHub repo size](https://img.shields.io/github/repo-size/Pfeffimann18/bspwm)
![GitHub repo file count](https://img.shields.io/github/directory-file-count/Pfeffimann18/bspwm)
![GitHub](https://img.shields.io/github/license/Pfeffimann18/bspwm) </br>
[README (English)](https://github.com/Pfeffimann18/bspwm/blob/main/README_ENG.md)
</br>

<p align="center">
  <img src="https://thumbs2.imgbox.com/06/86/kJbzbfji_t.png" width="900px">
</p>

<p align="center">
  <img src="https://thumbs2.imgbox.com/45/c9/FzDWwV73_t.png" width="900px">
</p>
</br>

## Installation der erforderlichen Pakete
```bash
yay -S xf86-video-amdgpu xorg xorg-xinit bspwm sxhkd nitrogen rofi picom alacritty firefox arandr ranger bashtop
```
> Kopieren Sie außerdem [ZSH](https://github.com/Pfeffimann18/ZSH), [Alacritty](https://github.com/Pfeffimann18/ArchBasicSetup/blob/main/alacritty.yml), [Rofi](https://github.com/Pfeffimann18/ArchBasicSetup/tree/main/rofi) und [Picom](https://github.com/Pfeffimann18/ArchBasicSetup/blob/main/picom.conf). 
</br>

mkdir ~/.config/bspwm
mkdir ~/.config/sxhdk
cp bspwmrc ~/.config/bspwm
cp sxhkdrc ~/.config/sxhkd

cp .xinitrc ~








## Verzeichnisse erstellen
```bash
mkdir ~/.screenlayout
mkdir ~/.config/bspwm
mkdir ~/.config/sxhdk
mkdir ~/.config/polybar
mkdir ~/.config/ranger/
mkdir ~/.config/ranger/colorschemes
```
</br>

## Konfigurationsdateien kopieren
```bash
cp display.sh ~/.screenlayout
chmod +x display.sh
cp config.ini ~/.config/polybar
```