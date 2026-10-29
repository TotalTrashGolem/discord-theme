# discord-theme

My configuration of the [Discord+](https://plusinsta.github.io/discord-plus) theme (by PlusInsta) for Vencord / Vesktop:
custom backdrop, colors and the JetBrains Mono Nerd Font.

## Installation

Vencord → Themes → Online Themes, paste:

```
https://raw.githubusercontent.com/TotalTrashGolem/discord-theme/main/DiscordPlus.theme.css
```

Or download `DiscordPlus.theme.css` into your themes folder.

## Backgrounds

All backgrounds live in `tla/` and none are deleted when a new one is added. The main theme uses `tla/lofi-balkon.png` by default.

To switch backgrounds with a click, copy the files from `cards/` into the Vencord themes folder (`%APPDATA%\Vencord\themes`). Each one shows up as its own card under Themes, and it only overrides `--dplus-backdrop` of the dark theme. Enable at most one background card at a time. With none enabled, the default backdrop is used.

Adding a background: put the image in `tla/<name>.png` and add a matching `cards/Tlo-<name>.theme.css`.

The fonts require [JetBrains Mono Nerd Font](https://www.nerdfonts.com/font-downloads) to be installed; otherwise a generic monospace font is used.

## License

The theme file comes from Discord+ (MIT, © Paulo Ødegård) — see `LICENSE`. The license does not cover the images in `tla/`.
