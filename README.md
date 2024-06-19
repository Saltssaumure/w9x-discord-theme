[screenshot]:       https://saltssaumure.github.io/w9x-discord-theme/preview/preview.png
[light]:            https://saltssaumure.github.io/w9x-discord-theme/preview/ninex1.png
[dark]:             https://saltssaumure.github.io/w9x-discord-theme/preview/ninex2.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[css-string]:       https://developer.mozilla.org/en-US/docs/Web/CSS/string
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://vencord.dev/

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-css-dl]:    https://img.shields.io/github/downloads/Saltssaumure/w9x-discord-theme/NineX.theme.css?color=purple&label=BetterDiscord%20GitHub%20downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/Saltssaumure/w9x-discord-theme/net.saltssaumure.NineX.asar?color=purple&label=Replugged%20GitHub%20downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/saltssaumure/w9x-discord-theme?style=flat-square "Total size"

[github]:           https://github.com/Saltssaumure/w9x-discord-theme
[issues]:           https://github.com/Saltssaumure/w9x-discord-theme/issues
[license]:          https://github.com/Saltssaumure/w9x-discord-theme/blob/main/LICENSE
[.theme.css]:       https://github.com/Saltssaumure/w9x-discord-theme/blob/main/NineX.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=933 "BetterDiscord store page"
[release-css-gh]:   https://github.com/Saltssaumure/w9x-discord-theme/releases/latest/download/NineX.theme.css "Latest release"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.NineX "Replugged store page"
[release-rp-gh]:    https://github.com/Saltssaumure/w9x-discord-theme/releases/latest/download/net.saltssaumure.NineX.asar "Latest release"

# NineX Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-css-dl]][release-css-gh]
[![Replugged GitHub downloads][shield-asar-dl]][release-rp-gh]
![Total size][shield-repo-size]

***A Windows 95/98 style Discord theme.***

| Light mode                                                  | Dark mode                                                 |
| ----------------------------------------------------------- | --------------------------------------------------------- |
| ![Screenshot of NineX light mode applied to Discord][light] | ![Screenshot of NineX dark mode applied to Discord][dark] |

## Installation

### [BetterDiscord][BetterDiscord]
<details>
    <summary>Click to expand</summary>

1. Download `NineX.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-css-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.
</details>

### [Replugged][Replugged]
<details>
    <summary>Click to expand</summary>

#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.NineX.asar`:
    - [GitHub][release-rp-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.
</details>

### [Vencord][Vencord]
<details>
    <summary>Click to expand</summary>

#### Local
1. Download `NineX.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-css-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://saltssaumure.github.io/w9x-discord-theme/NineX.theme.css`
</details>

## Customisation

| Description             | Variable name                           | Valid values                       | Default value                                         |
| ----------------------- | --------------------------------------- | ---------------------------------- | ----------------------------------------------------- |
| Background image        | `--w9x-background-image`                | Any image link encased in `url()`. | `none`                                                |
| Background colour       | `--w9x-background-color`                | Any [colour][css-color].           | `#008080`                                             |
| Start menu text         | `--w9x-start-text`                      | Any [text][css-string].            | `"Windows95"`                                         |
| Titlebar colour         | `--w9x-titlebar-color`                  | Any [colour][css-color].           | `#000080`                                             |
| Warning colour          | `--w9x-warning-color`                   | Any [colour][css-color].           | `#FF0000`                                             |
| Positive colour         | `--w9x-positive-color`                  | Any [colour][css-color].           | `#008000`                                             |
| Highlight ring colour   | `--w9x-highlight-color`                 | Any [colour][css-color].           | `#0000FF`                                             |
| Box colour              | `--w9x-box-color-1`, `2`, `3`, `4`, `5` | Any [colour][css-color].           | `#FFFFFF`, `#DFDFDF`, `#C0C0C0`, `#808080`, `#000000` |
| Inner background colour | `--w9x-bg-color`                        | Any [colour][css-color].           | `#FFFFFF` (light) / `#000000` (dark)                  |
| Inner text colour       | `--w9x-text-color`                      | Any [colour][css-color].           | `#000000` (light) / `#DFDFDF` (dark)                  |

### BetterDiscord
<details>
    <summary>Click to expand</summary>

1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.
</details>

### Replugged
<details>
    <summary>Click to expand</summary>

1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-41 of [`NineX.theme.css`][.theme.css].
3. Edit the variable values and save.
</details>

### Vencord
<details>
    <summary>Click to expand</summary>

#### Local
2. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
3. Open `NineX.theme.css` with your favourite text editor.
4. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-41 of [`NineX.theme.css`][.theme.css].
3. Edit the variable values.
</details>

## License
Copyright (c) 2023-2024 Saltssaumure

This theme is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This theme is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU Affero General Public License][license] for more details.

## Credits
### Themes
[hsl]:      https://github.com/DiscordStyles/HorizontalServerList
[squared]:  https://github.com/MiniDiscordThemes/Squared

- [HorizontalServerList][hsl] by [DiscordStyles](https://github.com/DiscordStyles) ([Gibbu](https://github.com/Gibbu)) - MIT license
- [Squared][squared] by [MiniDiscordThemes](https://github.com/MiniDiscordThemes) ([Saltssaumure](https://github.com/Saltssaumure)) - MIT license

### Fonts
[w95fa]:    https://www.dafont.com/w95fa.font
[unifont]:  https://savannah.gnu.org/projects/unifont
[fixedsys]: https://github.com/kika/fixedsys

- [W95FA][w95fa] by FontsArena - OFL
- [Unifont][unifont] by GNU - GPL-2.0-or-later-with-font-exception
- [Fixedsys Excelsior][fixedsys] by [bathos](https://github.com/Bathos) and [kika](https://github.com/kika) - Public domain / CC0

### Assets
[winicons]: https://archive.org/details/windows-95-all-icons

- [Windows 95 All Icons][winicons] by [Vovan29](https://www.deviantart.com/vovan29) - CC BY-ND 4.0

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].