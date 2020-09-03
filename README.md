# Rofi Collection

My personal collection.

## Getting Started

Things you need to install first.

### Prerequisites

You need to install Rofi and an icon pack, the one I'm using is [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme):

Debian

```bash
sudo apt install rofi papirus-icon-theme
```

Fedora

```bash
sudo dnf install rofi papirus-icon-theme
```

If you're having trouble I highly recommend you to take a look at [rofi repo](https://github.com/davatorium/rofi):

### Installing

First you need to download or clone the repo:

```bash
git clone https://github.com/Murzchnvok/rofi-collection
```

Also you'll need to download and install these fonts from [nerd fonts](https://www.nerdfonts.com/font-downloads):

* JetBrainsMono
* Sauce Code Pro

If you're using sxhkd you need to add something like this to your sxhkdrc:

```bash
super + shift + {i,o,p}
    rofi -show {run,drun,window} -theme ~/rofi-collection/nord/nord.rasi
```

or just copy or move the rasi config file to *~/.local/share/rofi/themes* and run this in the terminal to select a theme:

```bash
rofi-theme-selector
```

The first option will be easier to keep updated!

## Something you might be interested

* [Polybar Collection](https://github.com/Murzchnvok/polybar-collection)
* [Wallpaper Collection](https://drive.google.com/drive/folders/1o1qjRgkJtnF_8uGB1z6MRsQUjWinHUsw?usp=sharing)
* [Official rofi-themes repo](https://github.com/davatorium/rofi-themes)

*Quality is more important then quantity!*

## Material

![rofi](screenshots/material/rofi.png)

## Nord

![rofi](screenshots/nord/rofi.png)