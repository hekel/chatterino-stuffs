# chatterino-stuffs
## Chatterino Native QT Patches
By default Chatterino is hardcoded to use the Fusion QT Style with a custom stylesheet enforcing a dark grey theme that doesn't integrate well with other QT apps.

These patches are based against [Chatterino7](https://github.com/SevenTV/chatterino7) and tested with [Chatterino2](https://github.com/Chatterino/chatterino2), though they *should* work with most Chatterino2 forks.

They're intended to force Chatterino to use your native system-wide QT Style and introduce minor quality-of-life tweaks to ensure consistency across various themes and color schemes.

![settings dialog](native-qt/previews/settings-4.webp)

### Y Tho?
Well, apart from wanting Chatterino to homogeneously blend-in with the rest of my desktop and have a uniform appearance;
Some QT Styles like the [Kvantum](https://github.com/tsujan/Kvantum) theming engine or [Lightly](https://github.com/boehs/Lightly)/[Darkly](https://github.com/Bali10050/Darkly) support transparent windows. This allows us to easilly use [transparency in Chatterino themes](/Themes).

![main window themed](Themes/previews/nord.webp)

## Installation
### Arch Linux
[chatterino2-7tv-native-git](https://aur.archlinux.org/packages/chatterino2-7tv-native-git) is available in the [Arch User Repository](https://aur.archlinux.org/)