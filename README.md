# One Dark Pro for Kiro Crew

A Kiro Crew dashboard theme pack using the
[One Dark Pro](https://github.com/Binaryify/OneDark-Pro) palette. The light
variant uses Atom's One Light palette.

## Install

1. Clone this repository on the host where the Kiro Crew gateway runs.
2. In the dashboard, open the theme settings, choose **Install Theme**, and
   enter the path to the `one-dark-pro` folder.
3. Select **One Dark Pro** in the theme picker.

The gateway copies the pack into `~/.kiro/crew/themes/`, so it survives
upgrades and restarts. No restart is needed.

## What it sets

`one-dark-pro/variables.json` sets 52 dark-mode and 22 light-mode CSS
variables from the dashboard's allowed list: surfaces, borders, accent,
status colors, JSON highlighting, diffs and terminal colors. The dashboard
derives any variable left out from `--bg` and `--text`.

| Role | Color |
| --- | --- |
| Background | `#282c34` |
| Foreground | `#abb2bf` |
| Red | `#e06c75` |
| Green | `#98c379` |
| Yellow | `#e5c07b` |
| Blue | `#61afef` |
| Magenta | `#c678dd` |
| Cyan | `#56b6c2` |
| Orange (numbers) | `#d19a66` |
| Comments / muted | `#7f848e` |

## Credits

Palette from One Dark Pro by Binaryify (MIT) and Atom One Light (MIT).
