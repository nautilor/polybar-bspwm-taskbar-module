# BSPWM Taskbar Module for Polybar

[![Generic badge](https://img.shields.io/badge/BSPWM-red)](https://github.com/baskerville/bspwm)
[![Generic badge](https://img.shields.io/badge/POLYBAR-green)](https://github.com/polybar/polybar)
[![Generic badge](https://img.shields.io/badge/UNIXPORN%20TELEGRAM-blue)](https://t.me/r_unixporn_group)

A simple taskbar for bspwm to add to your Polybar

## Install

Place the script in any of the `$PATH` for example

- `/usr/bin/`
- `$HOME/.local/bin/`

## Polybar configuration example

```conf
[module/windows]
type = custom/script
tail = true
format = "<label>"
format-prefix = "  "
format-prefix-foreground = #111111
format-prefix-background = #0c9c84
format-background = #111111
format-foreground = #d0d060
exec = taskbar
```

The colors and/or separator character can also be customized from the exec option as given below:
```shell
exec = taskbar --activebg "#000" --inactivebg "#303030" --fg "#eaeaea" --separator "·"
```

## Demo Video

![](demo/demo.gif)
