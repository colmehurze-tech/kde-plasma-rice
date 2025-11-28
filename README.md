# KDE-plasma-rice
My First Arch Linux KDE Plasma Rice. 

I have attached a detailed guide on how to get this exact rice on your preferred linux distro. Please note that being on an Arch Based distro gives you an advantage as you can use package managers like yay to install dependencies quickly.

## Pre-Requisites:
1. Any Linux Based distribution running KDE plasma version 5 and above, on wayland.
2. Atleast 1gb ram and 15-20gb storage. My rice uses around 800-900MB ram on idle.

## Getting Started:

1. Install these packages:
``alacritty waybar htop cava zsh git rofi fastfetch``

Note: If you are using arch linux, you can do ``sudo pacman -S --needed base-devel git`` instead to install git and the packages we need to build yay later.

2. Clone my repository using:

``git clone https://github.com/colmehurze-tech/kde-plasma-rice.git``

3. Make a backup of your existing config files:

``mkdir ~/.config-backup && cp -r ~/.config ~/.config-backup``

4. Copy my config files over to your user config folder:

``cd kde-plasma-rice``

``cp -r .config/alacritty ~/.config/alacritty``

``cp -r .config/waybar ~/.config/waybar``

``cp -r .config/rofi ~/.config/rofi``

``cp -r .config/cava ~/.config/cava``