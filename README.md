# Bya-applets: Bluetoothmenu

A [rofi](https://github.com/davatorium/rofi) based dynamic menu applet to manage BLuetooth using [BLuez](https://www.bluez.org/) bluetoothctl.

<p align="center">
  <img src="assets/bluetoothmenu.gif" alt="bluetoothmenu" width="706"/>
</p>

Inspired by [rofi-bluetooth](https://github.com/nickclyde/rofi-bluetooth/tree/master?tab=readme-ov-file) and the GOAT [Catppuccin](https://github.com/catppuccin/rofi) rofi theme.

## Features

- Main menu to enable/disable bluetooth, control pariable/discoverable status and to start/stop bluetooth scans
- Submenu to manage devices - pairing/connection/trust

## Requirements

1. [rofi](https://github.com/davatorium/rofi)
2. [BlueZ](https://www.bluez.org/)
3. [Iosevka Nerd Font](https://www.nerdfonts.com/#features) (or any other Nerd Font you prefer)
4. libnotify compatible notification daemon ([dunst](https://github.com/dunst-project/dunst), [mako](https://github.com/emersion/mako),...)
5. [tmux](https://github.com/tmux/tmux)
6. [GNU Coreutils and gawk](https://www.gnu.org/software/coreutils/)

## Installation

Clone the repo and copy its contents to wherever u prefer. Ideally add its `scripts` directory to your `PATH` as well.

## Usage

### Bluetoothmenu

Run `bluetoothmenu`.

### Theming

You can find the theming .rasi files in the `config` directory.

```
.
└── config
    ├── colors.rasi         # color scheme
    ├── font.rasi           # font setting
    └── bluetoothmenu.rasi  # main menu and submenu theme
```

## Enjoy

Feel free to fork and modify the applet to your hearts content. If you do, please, share your results, cannot wait to see what yo'll guys create ^^!

If you enjoy this applet leave a star :P.
