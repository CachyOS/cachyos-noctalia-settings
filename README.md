# cachyos-noctalia-settings

This projects contains CachyOS'es settings for Noctalia projects: [**Noctalia Shell**](https://github.com/noctalia-dev/noctalia) and [**Noctalia Greeter**](https://github.com/noctalia-dev/noctalia-greeter).

Thank you for choosing CachyOS!

Dependencies:

```Sh
noctalia noctalia-greeter swash
```

# Project tree

There are 3 major directories:

## [etc/skel/.config/noctalia/](./etc/skel/.config/noctalia)

Contains `config.toml` and `config/` for configuration `noctalia` itself, `palettes/` for `Apathy` theme.

| config | purpose |
| ------ | ------- |
| [`bar.toml`](./etc/skel/.config/noctalia/config/bar.toml) | bar settings; bar itself a widget, follows defaults |
| [`misc.toml`](./etc/skel/.config/noctalia/config/misc.toml) | "misc" or non-essential settings; like scaling |
| [`shell.toml`](./etc/skel/.config/noctalia/config/shell.toml) | Noctalia settings itself; like how it behaves after screenshot |
| [`wallpaper.toml`](./etc/skel/.config/noctalia/config/wallpaper.toml) | wallpaper service settings; directory, default file, transition |
| [`theme.toml`](./etc/skel/.config/noctalia/config/theme.toml) | theming; [`Apathy`](./etc/skel/.config/noctalia/palettes/apathy.json/) is applied there |
| [`widget.toml`](./etc/skel/.config/noctalia/config/widget.toml) | widgets; how they look and behave, react on mouse clicks or scroll |

## [usr/share/noctalia-greeter/](./usr/share/noctalia-greeter/)

Contains session configuration file.

## [var/lib/noctalia-greeter/](./var/lib/noctalia-greeter/)

Contains greeter configuration file.
