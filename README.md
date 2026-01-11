<h2 align="center">Rofi Collection</h2>
<div align="center">
    <img src="https://github.com/Murzchnvok/rofi-collection/blob/master/screenshots/hidrot.png?raw=true" />
</div>

## Getting Started
> I'll add a new theme when I make something nice.

### Prerequisites
> You need [rofi](https://github.com/davatorium/rofi) installed.

### Install
> There's different ways on how you can set this up, this is how I do it.

#### Clone repo
> **--depth=1** shallow clone (basically smaller repo size).

```bash
git clone --depth=1 https://github.com/Murzchnvok/rofi-collection
```

#### Use
> Before you could create a symlink or copy/move to **~/.local/share/rofi/theme** and run rofi-the-selector to set a theme.
> Now I'm trying something different, kinda easier to change things, but maybe a bit harder to run since you have to set a bind to manually run this theme.

If you're using **sxhkd** add to your sxhkdrc:

```bash
super + shift + {i,o,p}
    rofi -show {run,drun,window} -theme $HOME/rofi-collection/theme.rasi
```
> `super + shift + {i,o,p}` is just an example, use whatever you want.

> Also the _path_ `$HOME/rofi-collection/theme.rasi` is where you cloned the repo.

### Customization

#### Change font
> By default is using **JetBrainsmono** font from [nerd fonts](https://www.nerdfonts.com/font-downloads).

Open `config/font.rasi`, and change what's inside `""`:

```bash
configuration {
  font: env(ROFI_FONT, "Font You Want to Use SIZE");
}
```

Second option, set an environment variable to `ROFI_FONT`:
> If you don't know how to set the variable google it.

```bash
ROFI_FONT="JetBrainsMono Nerd Font Medium 12"
```

### You might be interested
> Other repos related to rofi themes.

- [rofi-themes-collection](https://github.com/newmanls/rofi-themes-collection) by newmanls

### Examples
> Change goes in `theme.rasi`.

#### Gnomio

![example of gnomio theme](screenshots/gnomio.png)

```bash
@import "config/general"
@import "config/icons"
@import "colorscheme/onedark"

@import "themes/gnomio"
```

#### Hidrot

![example of hidrot theme](screenshots/hidrot.png)

```bash
@import "config/general"
@import "config/disable-prompt"
@import "colorscheme/gruvbox"

@import "themes/hidrot"
```

#### Murz

![example of murz theme](screenshots/murz.png)

```bash
@import "config/general"
@import "config/disable-prompt"
@import "colorscheme/dracula"

@import "themes/murz"
```
