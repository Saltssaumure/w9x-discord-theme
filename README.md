[screenshot]: https://user-images.githubusercontent.com/29710355/231909312-bf3786dc-317a-40c4-909b-b5dc58093b15.png
[light]: https://user-images.githubusercontent.com/29710355/231909647-72871e7f-8763-4174-9c71-5f1bb7d401bc.png
[dark]: https://user-images.githubusercontent.com/29710355/231909520-b24c4301-2d90-4c6c-9e5d-ca9ce20e3ba6.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/Saltssaumure/w9x-discord-theme/NineX.theme.css?color=purple&label=BetterDiscord%20GitHub%20downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/Saltssaumure/w9x-discord-theme/net.saltssaumure.NineX.asar?color=purple&label=Replugged%20GitHub%20downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/saltssaumure/w9x-discord-theme?style=flat-square "Total size"

[license]:          https://github.com/Saltssaumure/w9x-discord-theme/blob/main/LICENSE
[issues]:           https://github.com/Saltssaumure/w9x-discord-theme/issues
[.theme.css]:       https://github.com/Saltssaumure/w9x-discord-theme/blob/main/NineX.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=933 "BetterDiscord store page"
[release-bd-gh]:    https://github.com/Saltssaumure/w9x-discord-theme/releases/latest/download/NineX.theme.css "Latest release"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.NineX "Replugged store page"
[release-rp-gh]:    https://github.com/Saltssaumure/w9x-discord-theme/releases/latest/download/net.saltssaumure.NineX.asar "Latest release"

# NineX Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-bd-dl]][release-bd-gh]
[![Replugged GitHub downloads][shield-asar-dl]][release-rp-gh]
![Total size][shield-repo-size]

***A Windows 95/98 style Discord theme.***

| Light mode                                                  | Dark mode                                                 |
| ----------------------------------------------------------- | --------------------------------------------------------- |
| ![Screenshot of NineX light mode applied to Discord][light] | ![Screenshot of NineX dark mode applied to Discord][dark] |

## Installation

### [BetterDiscord][BetterDiscord]
1. Download `NineX.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.

### [Replugged][Replugged]
#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.NineX.asar`:
    - [GitHub][release-rp-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.

### [Vencord][Vencord]
#### Local
1. Download `NineX.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://saltssaumure.github.io/w9x-discord-theme/NineX.theme.css`

## Customisation

| Description             | Variable name                           | Valid values                       | Default value                                         |
| ----------------------- | --------------------------------------- | ---------------------------------- | ----------------------------------------------------- |
| Background image        | `--w9x-background-image`                | Any image link encased in `url()`. | `none`                                                |
| Background colour       | `--w9x-background-color`                | Any [colour][css-color].           | `#008080`                                             |
| Start menu text         | `--w9x-start-text`                      | Any quoted text.                   | `"Windows95"`                                         |
| Titlebar colour         | `--w9x-titlebar-color`                  | Any [colour][css-color].           | `#000080`                                             |
| Warning colour          | `--w9x-warning-color`                   | Any [colour][css-color].           | `#FF0000`                                             |
| Positive colour         | `--w9x-positive-color`                  | Any [colour][css-color].           | `#008000`                                             |
| Highlight ring colour   | `--w9x-highlight-color`                 | Any [colour][css-color].           | `#0000FF`                                             |
| Box colour              | `--w9x-box-color-1`, `2`, `3`, `4`, `5` | Any [colour][css-color].           | `#FFFFFF`, `#DFDFDF`, `#C0C0C0`, `#808080`, `#000000` |
| Inner background colour | `--w9x-bg-color`                        | Any [colour][css-color].           | `#FFFFFF` (light) / `#000000` (dark)                  |
| Inner text colour       | `--w9x-text-color`                      | Any [colour][css-color].           | `#000000` (light) / `#DFDFDF` (dark)                  |

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-41 of [`NineX.theme.css`][.theme.css].
3. Edit the variable values and save.

### Vencord
#### Local
2. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
3. Open `NineX.theme.css` with your favourite text editor.
4. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-41 of [`NineX.theme.css`][.theme.css].
3. Edit the variable values.

## License
[GNU General Public License v3.0][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].