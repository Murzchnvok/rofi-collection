# Rofi Collection

My personal collection.

*If you find any error or you think I need to add something to this readme please send a message to me on [reddit](https://www.reddit.com/user/murzchnvok)*

## Getting Started

### Prerequisites

You need to install Rofi and an icon pack, the one I'm using is [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme):

Debian/Ubuntu

```bash
$HOME
-> sudo apt install rofi papirus-icon-theme
```

Fedora

```bash
$HOME
-> sudo dnf install rofi papirus-icon-theme
```

If you're having trouble:

[rofi repo](https://github.com/davatorium/rofi).

[Papirus Icon repo](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme#installation)

Also you need to download and install this font from [nerd fonts](https://www.nerdfonts.com/font-downloads):

* JetBrainsMono

To install this font, copy/move to the folder *~/.fonts* and run in the terminal:

```bash
$HOME
-> fc-cache -fv
```

### Installing

First you need to clone the repo (recommend in $HOME, or Projects directory):

```bash
$HOME
-> git clone https://github.com/Murzchnvok/rofi-collection
```

If you're using sxhkd you need to add something like this to your sxhkdrc:

```bash
super + shift + {i,o,p}
    rofi -show {run,drun,window} -theme $HOME/rofi-collection/nord/nord.rasi
```

or copy/move the rasi config file to *~/.local/share/rofi/themes/* and run rofi theme selector:

```bash
$HOME/rofi-collection
-> cp -r nord $HOME/.local/share/rofi/themes/

$HOME
-> rofi-theme-selector
```

Remember to keep updated:

```bash
$HOME
-> cd $HOME/rofi-collection && git pull
```

## You might be interested

* [Polybar Collection](https://github.com/Murzchnvok/polybar-collection)
* [Wallpaper Collection](https://drive.google.com/drive/folders/1o1qjRgkJtnF_8uGB1z6MRsQUjWinHUsw?usp=sharing)
* [Official rofi-themes repo](https://github.com/davatorium/rofi-themes)

*Quality is more important then quantity!*

## Dracula

![rofi](screenshots/dracula/rofi.png)

## Material

![rofi](screenshots/material/rofi.png)

## Neon

![rofi](screenshots/neon/rofi.png)

## Nord

![rofi](screenshots/nord/rofi.png)
