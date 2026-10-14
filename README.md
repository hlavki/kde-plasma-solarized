# KDE Plasma Solarized

![KDE Plasma Solarized Dark and Light](screenshots/kde_plasma_solarized.png)

This repository contains Solarized Dark and Light color schemes for KDE Plasma 6.

The color schemes are based on the official Breeze Dark and Light color schemes that come pre-installed with KDE Plasma.
Each color was replaced with the closest equivalent from the [official Solarized color schemes](https://ethanschoonover.com/solarized/) by Ethan Schoonover.

This is a fork of [ret2src/kde-plasma-solarized](https://github.com/ret2src/kde-plasma-solarized) updated for Plasma 6:

- selected text uses `base3`/`base2` instead of `base0`/`base00`, so it is readable on the Solarized blue highlight
  (Plasma 6 uses the scheme's own selection colors whenever no accent color is set, which is the default);
- the `ColorScheme` key matches the file name, as in the Breeze schemes;
- the files are packaged for openSUSE (see below).

## Installation

### openSUSE Tumbleweed

The schemes are packaged in the [home:hlavki](https://build.opensuse.org/package/show/home:hlavki/kde-plasma-solarized) OBS project:

``` bash
$ sudo zypper addrepo https://download.opensuse.org/repositories/home:/hlavki/openSUSE_Tumbleweed/home:hlavki.repo
$ sudo zypper refresh
$ sudo zypper install kde-plasma-solarized
```

The package installs the schemes system-wide into `/usr/share/color-schemes/`.

### Manual

Download either the dark or light variant of the color scheme file from this repository and place it into your `~/.local/share/color-schemes/`.
You can then select the color scheme from _System Settings > Colors & Themes > Colors_.

You can also use a tool like `wget` to download the files:

``` bash
$ wget https://raw.githubusercontent.com/hlavki/kde-plasma-solarized/main/BreezeSolarizedDark.colors -O ~/.local/share/color-schemes/BreezeSolarizedDark.colors

$ wget https://raw.githubusercontent.com/hlavki/kde-plasma-solarized/main/BreezeSolarizedLight.colors -O ~/.local/share/color-schemes/BreezeSolarizedLight.colors
```

## Accent Color

If you're using a current version of KDE Plasma, you'll have the choice to set an accent color.
For an unobtrusive look, I recommend you set it to `#657b83`, which is color `base 0` in the Solarized color scheme.
Alternatively, if you prefer less decency and some more "pop" on your desktop, set it to one of the other Solarized accent colors shown below.

### Base 0 Accent Color (#657b83)

![KDE Plasma Solarized Dark with Base 0 Accent Color](screenshots/kde_plasma_solarized_dark_base0.png)

![KDE Plasma Solarized Light with Base 0 Accent Color](screenshots/kde_plasma_solarized_light_base0.png)

### Yellow Accent Color (#b58900)

![KDE Plasma Solarized Dark with Yellow Accent Color](screenshots/kde_plasma_solarized_dark_yellow.png)

![KDE Plasma Solarized Light with Yellow Accent Color](screenshots/kde_plasma_solarized_light_yellow.png)

### Orange Accent Color (#cb4b16)

![KDE Plasma Solarized Dark with Orange Accent Color](screenshots/kde_plasma_solarized_dark_orange.png)

![KDE Plasma Solarized Light with Orange Accent Color](screenshots/kde_plasma_solarized_light_orange.png)

### Red Accent Color (#dc322f)

![KDE Plasma Solarized Dark with Red Accent Color](screenshots/kde_plasma_solarized_dark_red.png)

![KDE Plasma Solarized Light with Red Accent Color](screenshots/kde_plasma_solarized_light_red.png)

### Magenta Accent Color (#d33682)

![KDE Plasma Solarized Dark with Magenta Accent Color](screenshots/kde_plasma_solarized_dark_magenta.png)

![KDE Plasma Solarized Light with Magenta Accent Color](screenshots/kde_plasma_solarized_light_magenta.png)

### Violet Accent Color (#6c71c4)

![KDE Plasma Solarized Dark with Violet Accent Color](screenshots/kde_plasma_solarized_dark_violet.png)

![KDE Plasma Solarized Light with Violet Accent Color](screenshots/kde_plasma_solarized_light_violet.png)

### Blue Accent Color (#268bd2)

![KDE Plasma Solarized Dark with Blue Accent Color](screenshots/kde_plasma_solarized_dark_blue.png)

![KDE Plasma Solarized Light with Blue Accent Color](screenshots/kde_plasma_solarized_light_blue.png)


### Cyan Accent Color (#2aa198)

![KDE Plasma Solarized Dark with Cyan Accent Color](screenshots/kde_plasma_solarized_dark_cyan.png)

![KDE Plasma Solarized Light with Cyan Accent Color](screenshots/kde_plasma_solarized_light_cyan.png)


### Green Accent Color (#859900)

![KDE Plasma Solarized Dark with Green Accent Color](screenshots/kde_plasma_solarized_dark_green.png)

![KDE Plasma Solarized Light with Green Accent Color](screenshots/kde_plasma_solarized_light_green.png)
