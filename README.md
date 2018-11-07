# terminology-theme-pack
Color schemes for the Terminology terminal emulator.

[Charles Milette's collection of Terminology Themes](https://github.com/sylveon/terminology-themes), as packaged by Bodhi Linux.

Previews are available [on his website](https://charlesmilette.net/terminology-themes).

------------------------

The tab appearance is a WIP. If anyone with better knowledge of EDC than me wants to help, feel free to PR. Mostly, I would like to, if anyone can help:

- Remove all the useless `tab_bevel` structures and some other useless `tab_bg_*`, `tab_other_*` and `tab_shad_*` assets file.
- Add a little | separator between tabs.
- Fix a [little alignment glitch when switching tabs](http://i.imgur.com/Vok8agA.gif).

## Installation

Users of Bodhi linux 4.x or 5.x can install all themes by:

```sudo apt update
sudo apt install terminology-theme-pack
```

Since each theme is indivually packaged in Bodhi, single  themes can be also be installed for user not wanting all 185 themes. For example, to install the theme solarizeddark:

```sudo apt update
sudo apt install terminology-theme-solarizeddark
```

**Note**: A package might be available for your distro. Scroll down to the [packages section](#packages) to find it out.


## Packages

 - Arch Linux: [terminology-themes-git](https://aur.archlinux.org/packages/terminology-themes-git/) on the AUR
 - Gentoo: [x11-themes/terminology-themes](https://packages.gentoo.org/packages/x11-themes/terminology-themes)
