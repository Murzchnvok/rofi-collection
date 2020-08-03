# Rofi Collection

My personal collection.

## Getting Started

Things you need to install first.

### Prerequisites

You have to install Rofi and an icon pack, the one I'm using is [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme). I'm on Fedora so it's really simple:

```bash
sudo dnf install rofi papirus-icon-theme
```

I recommend you to take a look at [rofi repo](https://github.com/davatorium/rofi):

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
    rofi -show {run,drun,window} -theme ~/rofi-collection/material/material.rasi
```

or just copy or move the rasi config file to *~/.local/share/rofi/themes* and run this in the terminal to select a theme:

```bash
rofi-theme-selector
```

The first option will be easier to keep updated!

## Something you might be interested

* [Polybar Collection](https://github.com/Murzchnvok/polybar-collection)
* [Wallpaper Collection](https://drive.google.com/drive/folders/1o1qjRgkJtnF_8uGB1z6MRsQUjWinHUsw?usp=sharing)
* [Bind Daily (to get bing daily wallpapers)](https://github.com/Murzchnvok/bing-daily)
* [Simple Conky theme](https://github.com/Murzchnvok/simple-conky)
* [Official rofi-themes repo](https://github.com/davatorium/rofi-themes)

*Quality is more important then quantity!*

## Material

![rofi](screenshots/material/rofi.png)

I'll add some more in time!
