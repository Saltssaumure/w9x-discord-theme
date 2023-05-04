[screenshot]: https://user-images.githubusercontent.com/29710355/231909312-bf3786dc-317a-40c4-909b-b5dc58093b15.png
[light]: https://user-images.githubusercontent.com/29710355/231909647-72871e7f-8763-4174-9c71-5f1bb7d401bc.png
[dark]: https://user-images.githubusercontent.com/29710355/231909520-b24c4301-2d90-4c6c-9e5d-ca9ce20e3ba6.png

[css-color]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

# NineX Discord Theme
[![GitHub downloads](https://img.shields.io/github/downloads/saltssaumure/w9x-discord-theme/total?color=purple&label=GitHub%20downloads&style=flat-square)](https://github.com/Saltssaumure/w9x-discord-theme/releases/latest "Latest release")
![Total size](https://img.shields.io/github/repo-size/saltssaumure/w9x-discord-theme?style=flat-square "Total size")

***A Windows 9x style Discord theme.***

| Light mode                                                  | Dark mode                                                 |
| ----------------------------------------------------------- | --------------------------------------------------------- |
| ![Screenshot of NineX light mode applied to Discord][light] | ![Screenshot of NineX dark mode applied to Discord][dark] |

## Installation

### BetterDiscord
1. Install [BetterDiscord](https://betterdiscord.app/).
2. Download the theme file:
    - [GitHub](https://github.com/Saltssaumure/w9x-discord-theme/releases/latest)
    - [BD Store](https://betterdiscord.app/theme/?id=933)
3. Place theme file in BetterDiscord's theme folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged](https://replugged.dev/).
2. Install the theme:
    - [GitHub](https://github.com/Saltssaumure/w9x-discord-theme/releases/latest)
    - [Replugged.dev](https://replugged.dev/install?identifier=Saltssaumure/w9x-discord-theme&source=github)

### Vencord
1. Install [Vencord](https://github.com/Vendicated/Vencord).
2. Paste the following in Themes:
    - `https://saltssaumure.github.io/w9x-discord-theme/NineX.theme.css`

## Customisation

| Description       | Variable name            | Valid values                               | Default value |
| ----------------- | ------------------------ | ------------------------------------------ | ------------- |
| Background image  | `--w9x-background-image` | Any image link encased in `url()`. | `none`        |
| Background colour | `--w9x-background-color` | Any [colour][css-color].                   | `#008080`     |
| Start menu text   | `--w9x-start-text`       | Any quoted text.                           | `"Windows95"` |

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-20 of [`NineX.theme.css`](https://github.com/Saltssaumure/w9x-discord-theme/blob/main/NineX.theme.css).
3. Edit the variable values and apply changes.

### Vencord
#### Standard method
1. Follow the instructions in `Settings` > `Vencord` > `Themes`.
#### Recommended method
1. Open `Settings` > `Vencord` > `Vencord`.
2. Toggle on `Enable Custom CSS` and click `Open QuickCSS File`.
3. Copy and paste lines 15-20 of [`NineX.theme.css`](https://github.com/Saltssaumure/w9x-discord-theme/blob/main/NineX.theme.css).
4. Edit the variable values.

## License
[GNU General Public License v3.0](https://github.com/Saltssaumure/w9x-discord-theme/blob/main/LICENSE)
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.

## Questions or suggestions?
- Post [an issue](https://github.com/Saltssaumure/w9x-discord-theme/issues) on GitHub.
- Post in `#theme-support` on [my support server](https://discord.gg/uy8nKQVatp).
