# i3 Dotfiles – Mon premier rice

Thème sombre violet/noir avec i3, polybar, rofi, picom et alacritty.

<p align="center">
  <img src="https://preview.redd.it/i3-my-first-rice-ever-on-vbox-v0-ax4qidcy9ljf1.png?width=1080&crop=smart&auto=webp&s=5f99bf6718d5d9d9a87cc96c00fff0bdbfa41caa" alt="Mon setup i3" width="80%"/>
  <br>
  <sub>Premier rice fait sur VirtualBox – EndeavourOS</sub>
</p>

## Ce qu’il y a dedans

- i3 avec gaps et raccourcis simples  
- Polybar violette (cpu, ram, volume, heure…)  
- Rofi pour lancer les apps + menu d’arrêt  
- Picom (ombres + coins arrondis légers)  
- Alacritty + fastfetch stylé  
- Palette sombre violet/noir cohérente

## Installation (la méthode la plus bête)

```bash
git clone https://github.com/xccoding01/i3-Dotfiles.git ~/.dotfiles
cd ~/.dotfiles

# Option 1 – copier tout (rapide mais pas propre)
cp -r .config/* ~/.config/
cp .Xresources ~/.Xresources   # si tu l’utilises

# Option 2 – liens symboliques (mieux)
# ln -s ~/.dotfiles/.config/i3       ~/.config/i3
# ln -s ~/.dotfiles/.config/polybar  ~/.config/polybar
# etc...

# Après ça :
# recharge i3 → Mod+Shift+R
# ou redémarre ta session
