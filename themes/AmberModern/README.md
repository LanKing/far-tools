🇺🇦 [Українська](docs/README-uk.md) | 🇧🇾 [Беларуская](docs/README-be.md) | <sub>ru</sub> [Русский](docs/README-ru.md) | 🇵🇱 [Polski](docs/README-pl.md) | 🇨🇿 [Čeština](docs/README-cs.md) | 🇸🇰 [Slovenčina](docs/README-sk.md) | 🇩🇪 [Deutsch](docs/README-de.md) | 🇭🇺 [Magyar](docs/README-hu.md) | 🇮🇹 [Italiano](docs/README-it.md) | 🇪🇸 [Español](docs/README-es.md)

[![Far Manager](https://img.shields.io/badge/Far%20Manager-3.x-FFFF00?labelColor=0000FF)](https://www.farmanager.com/) [![Downloads](https://img.shields.io/github/downloads/LanKing/far-tools/AmberModernAndVtrEnabler.farconfig?displayAssetName=false&label=Downloads&color=B87938)](https://github.com/LanKing/far-tools/releases/download/amber-modern-latest/AmberModernAndVtrEnabler.farconfig) [![Version](https://img.shields.io/github/v/release/LanKing/far-tools?filter=amber-modern-v%2A&sort=semver&label=Version&color=D6A21E)](https://github.com/LanKing/far-tools/releases) [![License](https://img.shields.io/badge/License-MIT-657A55)](LICENSE) <img alt="VT required" src="https://img.shields.io/badge/rendering-VT%20required-526D82">

# 🎨 Amber Modern color theme

> For anyone tired of Far Manager's classic blue look and looking for a modern, calm color scheme that is easy on the eyes.

![Overview](docs/demo.png)

## 📓 Notes

1. The theme does not change file highlighting rules; it uses the rules already configured in Far Manager.
2. The theme sets the base colors of the editor and viewer but does not include its own syntax highlighting. I use [Monokai](https://github.com/joric/monokai) for the editor and recommend giving it a try.

## 📦 Installation

Amber Modern uses an extended color palette and therefore requires **Virtual Terminal Rendering**. The required setting is already enabled in the theme file.

1. [Download the theme](https://github.com/LanKing/far-tools/releases/download/amber-modern-latest/AmberModernAndVtrEnabler.farconfig) and place it in the Far Manager directory.
2. Completely close all running Far Manager instances.
3. Run the following command:

   ```bat
   far.exe /import AmberModernAndVtrEnabler.farconfig
   ```

4. Start Far Manager again.

## 📄 License

Amber Modern is distributed under the [MIT License](LICENSE). Improvements and suggestions are welcome 😊
