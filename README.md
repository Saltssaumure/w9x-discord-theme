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

[shield-total-dl]:  https://img.shields.io/github/downloads/Saltssaumure/w9x-discord-theme/NineX.theme.css?color=purple&label=BD%20GitHub%20downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/Saltssaumure/w9x-discord-theme/net.saltssaumure.NineX.asar?color=purple&label=Replugged%20downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/saltssaumure/w9x-discord-theme?style=flat-square "Total size"

[license]:          https://github.com/Saltssaumure/w9x-discord-theme/blob/main/LICENSE
[issues]:           https://github.com/Saltssaumure/w9x-discord-theme/issues
[.theme.css]:       https://github.com/Saltssaumure/w9x-discord-theme/blob/main/NineX.theme.css

[release-gh]:       https://github.com/Saltssaumure/w9x-discord-theme/releases/latest "Latest release"
[release-bd]:       https://betterdiscord.app/theme/?id=823 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/install?identifier=Saltssaumure/w9x-discord-theme&source=github "Replugged addon installer"

# NineX Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-total-dl]][release-gh]
[![Replugged downloads][shield-asar-dl]][release-rp]
![Total size][shield-repo-size]

***A Windows 9x style Discord theme.***

| Light mode                                                  | Dark mode                                                 |
| ----------------------------------------------------------- | --------------------------------------------------------- |
| ![Screenshot of NineX light mode applied to Discord][light] | ![Screenshot of NineX dark mode applied to Discord][dark] |

## Installation

### BetterDiscord
1. Install [BetterDiscord][BetterDiscord].
2. Download the theme file:
    - [GitHub][release-gh]
    - [BD Store][release-bd]
3. Place theme file in the `themes` folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged][Replugged].
2. Install the theme:
    - [GitHub][release-gh]
    - [Installer][release-rp]

### Vencord
1. Install [Vencord][Vencord].
2. Paste the following in `Settings` > `Vencord` > `Themes`:
    - `https://saltssaumure.github.io/w9x-discord-theme/NineX.theme.css`

## Customisation

| Description             | Variable name            | Valid values                       | Default value                        |
| ----------------------- | ------------------------ | ---------------------------------- | ------------------------------------ |
| Background image        | `--w9x-background-image` | Any image link encased in `url()`. | `none`                               |
| Background colour       | `--w9x-background-color` | Any [colour][css-color].           | `#008080`                            |
| Inner background colour | `--w9x-bg-color`         | Any [colour][css-color].           | `#FFFFFF` (light) / `#000000` (dark) |
| Inner text colour       | `--w9x-text-color`       | Any [colour][css-color].           | `#000000` (light) / `#DFDFDF` (dark) |
| Start menu text         | `--w9x-start-text`       | Any quoted text.                   | `"Windows95"`                        |

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Open `Settings` > `Replugged` > `Quick CSS`.
2. Copy and paste lines 15-30 of [`NineX.theme.css`][.theme.css].
3. Edit the variable values and apply changes.

### Vencord
#### Standard method
1. Follow the instructions in `Settings` > `Vencord` > `Themes`.
#### Recommended method
1. Open `Settings` > `Vencord` > `Vencord`.
2. Toggle on `Enable Custom CSS` and click `Open QuickCSS File`.
3. Copy and paste lines 15-30 of [`NineX.theme.css`][.theme.css].
4. Edit the variable values.
 
## License
[GNU General Public License v3.0][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].
