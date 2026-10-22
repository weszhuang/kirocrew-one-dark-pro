# One Dark Pro for Kiro Crew

A Kiro Crew dashboard theme pack using the
[One Dark Pro](https://github.com/Binaryify/OneDark-Pro) palette. The light
variant uses Atom's One Light palette.

## Install

### From GitHub (recommended)

1. In the Kiro Crew dashboard, open **Settings → Display → Theme** and
   choose **Install Theme**.
2. Set **Theme source** to **GitHub** and enter:

   ```
   https://github.com/weszhuang/kirocrew-one-dark-pro
   ```

3. In the same **Theme** section, select **⚛️ One Dark Pro** and set the
   mode to dark.

The gateway clones the repository, validates it, and copies the pack into
`~/.kiro/crew/themes/`, so it survives upgrades and restarts. No restart is
needed.

### From a local folder

If the gateway host cannot reach GitHub, clone this repository on that host,
then in **Settings → Display → Theme → Install Theme** set **Theme source** to
**Local folder** and enter the path to the cloned repository root.

## What it sets

`variables.json` sets 52 dark-mode and 22 light-mode CSS
variables from the dashboard's allowed list: surfaces, borders, accent,
status colors, JSON highlighting, diffs and terminal colors. The dashboard
derives any variable left out from `--bg` and `--text`.

`styles/overrides.css` recolors added, removed and modified lines in the
dashboard's code viewer (diffs and code review panels) to the One Dark Pro
green, red and yellow. Syntax highlighting inside the code viewer still uses
its built-in color scheme, which a theme pack cannot change.

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
