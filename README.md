## Welcome to Floorp Browser GitHub Repository 👋

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Floorp-Projects/Floorp.svg?style=for-the-badge
[contributors-url]: https://github.com/Floorp-Projects/Floorp/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Floorp-Projects/Floorp?style=for-the-badge
[forks-url]: https://github.com/Floorp-Projects/Floorp/network/members
[stars-shield]: https://img.shields.io/github/stars/Floorp-Projects/Floorp.svg?style=for-the-badge
[stars-url]: https://github.com/Floorp-Projects/Floorp/stargazers
[issues-shield]: https://img.shields.io/github/issues/Floorp-Projects/Floorp.svg?style=for-the-badge
[issues-url]: https://github.com/Floorp-Projects/Floorp-Projects/issues
[license-shield]: https://img.shields.io/github/license/Floorp-Projects/Floorp.svg?style=for-the-badge
[license-url]: https://github.com/Floorp-Projects/Floorp/blob/master/LICENSE

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Floorp-Projects/Floorp">
    <img src="https://avatars.githubusercontent.com/u/94953125?s=200&v=4" alt="Logo" width="150" height="150">
  </a>

  <h3 align="center">Floorp Browser </h3>

  <p align="center">
       A Browser build for keeping the Open, Private and Sustainable Web alive. Based on Mozilla Firefox.
    <br />
    <br />
    <a href="https://floorp.app">Official Site</a>
    ・
    <a href="#📥-download--📦-install">Download</a>
    ・
    <a href="https://blog.ablaze.one/category/ablaze/ablaze-project/floorp/">Blog & Release Notes</a>
    ・
    <a href="https://support.ablaze.one">Official Support Site & Send feedback</a>
  </p>
</div>


## ⚡ Get Started


### 💻 Supported Operating Systems & Requirements

Floorp Browser is available for Windows, macOS and Linux. You can install it by running the installer or by extracting the archive.

#### Windows

- Windows 10 or later. (Windows 7 and 8 are not supported)

- x86_64 CPU architecture. AArch64 is not supported.

- Floorp provides "exe" installer & "Winget" install.

Winget install command: 
```
winget install Ablaze.Floorp
```
Winget repository provided by [@Hibi_10000](https://github.com/Hibi-10000)

**Floorp get Certum Open Source Code Signing Certificate. Official Floorp installer is signed by "Open Source Developer, Ryosuke Asano". Daylight build installer is not signed.**

#### macOS

- macOS 10.12 or later.

- x86_64 CPU & ARM64 CPU architecture. Floorp provides a Universal build for both architectures.

**After Floorp 11.0.0, Floorp gets Apple Notarization & Certification. You can install Floorp without warning. It also has an auto-update system included**

#### Linux

- Debian-based distributions (Ubuntu, Linux Mint, etc.) & Arch-based distributions (Manjaro, etc.) are supported.

- x86_64 & AAarch64 CPU architecture.

- Floorp Browser Requirements: ["Firefox Linux Requirements"](https://www.mozilla.org/en-US/firefox/115.0beta/system-requirements/#gnulinux)

- List of supported package managers:

```md
1. PPA (Ubuntu, Linux Mint, etc.)       "https://ppa.ablaze.one"

2. Flatpak (All Linux Distributions)    "https://flathub.org/apps/one.ablaze.floorp"

3. tarball (All Linux Distributions)    "https://GitHub.com/Floorp-Projects/Floorp/releases/latest"

4. AUR (Arch-based distributions)        "https://aur.archlinux.org/packages/floorp/" **Unofficial**
```

### 📥 Download & 📦 Install

You can download the latest version of Floorp Browser from the official website: [Floorp.app](https://floorp.app/download) or from the [GitHub Releases](https://github.com/Floorp-Projects/Floorp/releases) page.

---

## 📖 Documentation

### 📝 License

[Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/)

- Floorp's name is a registered trademark of Floorp's developer. & Floorp's logo is protected by Copyright.

- Floorp Browser is based on Mozilla Firefox. Floorp Browser is not affiliated with Mozilla & Mozilla Firefox.

- Floorp uses Mozilla Firefox's source code & other open-source projects. See [Floorp License Notices](#📄-Floorp-License-Notices-📄)

### 📧 Contact

- [Official Support Site](https://support.ablaze.one)

- [Official Floorp Twitter](https://twitter.com/Floorp_Browser) or [Official Ablaze Twitter](https://twitter.com/Ablaze_MIRAI)

- [Official Ablaze Community Discord Server](https://discord.gg/qw3WX7pB)

### 📜 Privacy Policy

- [Ablaze Privacy Policy](https://docs.ablaze.one/privacy_policy)

- [Floorp Privacy Policy](https://docs.ablaze.one/floorp_privacy_policy)

---

## 🌟 Contributing

### 🧰 Writing Code

- We welcome contributions from everyone. First of all, you need to fork this repository and clone it to your local machine.

- You can use any IDE or text editor you want. We recommend using [Visual Studio Code](https://code.visualstudio.com/).

- We use "JavaScript", "XHTML" & "CSS" for writing code. If you want to know about these languages, please see the following links.

    - [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

    - [XHTML](https://www.w3schools.com/xml)

    - [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

- Firefox uses legacy technologies. Mozilla call it "XUL". If you want to know about XUL, please see the following links.

    - [XUL](https://www.xul.fr/en-xml-xul.php)

- If you want to know about Floorp's code, please see the following links.

    - [Firefox Source Docs](https://firefox-source-docs.mozilla.org/)

    - [Firefox Source Code](https://github.com/mozilla/gecko-dev)

    - [Searchfox](https://searchfox.org/)

- If you want to build Floorp Browser, please see the [Building](#building) section.

### 📝 Translating

- We want to support as many languages as possible. If you want to translate Floorp Browser, please clone [l10n-central](https://github.com/Floorp-Projects/l10n-Central) repository.

- Floorp's language file is located in: `browser/browser/floorp.ftl`

- English is the main language. If you want to translate Floorp Browser, please translate from English (en-US)

- Floorp's English file is located in here: [floorp.ftl](./floorp/browser/locales/en-US/floorp.ftl)

### 🐛 Reporting Bugs

- If you find a bug, please report it to the [Issues](https://github.com/Floorp-Projects/Floorp/issues) page or using [Official Support Site](https://support.ablaze.one/contact).

---

## 🗜️ Building

### 📦 Requirements

- Windows:
  - [Mozilla Build Shell](https://ftp.mozilla.org/pub/mozilla/libraries/win32/MozillaBuildSetup-Latest.exe)
  - [git](https://git-scm.com/download/win)

- macOS:
    - [Xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12)
    - [git](https://git-scm.com/download/mac)

- Linux:
    - [git](https://git-scm.com/download/linux)
    - curl `sudo apt install curl`
    - python3 `sudo apt install python3`
    - pip3 `sudo apt install python3-pip`
    - Mercurial `python3 -m pip install --user mercurial`

## 🧨 Bootstrap, Build & run

- Windows (on Mozilla Build Shell: `C:\mozilla-build\start-shell.bat`)
- macOS & Linux (on Terminal)

```bash
$ cd /path/to/your/Floorp/repository

**set mozconfig**
$ echo 'ac_add_options --with-app-name=floorp' >> mozconfig
$ echo 'ac_add_options --with-app-basename=Floorp' >> mozconfig
$ echo 'ac_add_options --with-branding=browser/branding/official' >> mozconfig


** Bootstrap Source code**
$ ./mach bootstrap

** Build Floorp Browser **
$ ./mach build

** Run Floorp Browser **
$ ./mach run
```

## 📄 Floorp License Notices 📄

Floorp uses some open source projects. Below is the list of open-source projects used in Floorp.

Some of the listed software is not included in Floorp itself, but is downloaded from the Internet. Also listed are add-ons that Floorp recommends installing.

### 🦊 Mozilla Firefox

- [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/)
- [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/)
- Authers: [Mozilla & Contributors](https://www.mozilla.org/credits/)

### 💧 Waterfox

- [Waterfox](https://www.waterfox.net/)
- [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/)
- Author: [MrAlex94](https://github.com/MrAlex94)

Notice: Floorp is not based on Waterfox. The structure is a reference and has nothing to do with Waterfox.

### 🎨 Firefox UI FIX (Lepton)

- [Firefox UI FIX (Lepton)](https://github.com/black7375/Firefox-UI-Fix)
- [Mozilla Public License 2.0](https://github.com/black7375/Firefox-UI-Fix/blob/master/LICENSE)
- Author: [black7375](https://github.com/black7375)

### 🎨 Edge-Frfox

- [Edge-Fox](https://github.com/bmFtZQ/edge-frfox)
- [MIT](https://github.com/bmFtZQ/edge-frfox/blob/main/LICENSE)
- Author: [bmFtZQ](https://github.com/bmFtZQ)

### 🎨 Firefox-csshacks

- [Firefox-csshacks](https://github.com/MrOtherGuy/firefox-csshacks)
- [Mozilla Public License 2.0](https://github.com/MrOtherGuy/firefox-csshacks/blob/master/LICENSE)
- Author: [MrOtherGuy](https://github.com/MrOtherGuy)

### 🎨 Material-Fox

- [Material-Fox](https://github.com/muckSponge/MaterialFox)
- [MIT](https://github.com/muckSponge/MaterialFox/blob/master/LICENSE)
- Author: [muckSponge](https://github.com/muckSponge)

### 🎨 firefox-gnome-theme

- [Firefox-Gnome-Theme](https://github.com/rafaelmardojai/firefox-gnome-theme/blob/master/LICENSE)
- [The Unlicense](https://github.com/rafaelmardojai/firefox-gnome-theme/blob/master/LICENSE)
- Author: [rafaelmardojai](https://github.com/rafaelmardojai)

### 📦 userChromeCSS Loader

- [userChromeCSS Loader](floorp/browser/base/content/browser-chromeCSS.js)
- [MIT](floorp/browser/base/content/browser-chromeCSS.js)
- Author: Griever

NOTICE: If you are "userChromeCSS Loader" developer, please contact us. We add the site of your name.

### 📦 userChromeJS Loader

- [userChromeJS Loader](https://github.com/xiaoxiaoflood/firefox-scripts/)
- [Mozilla Public License 2.0](https://github.com/xiaoxiaoflood/firefox-scripts/blob/master/LICENSE)
- Author: [Alice0775](https://github.com/Alice0775/), Endor8, TroudhuK, Izheil, Merci-chao, [xiaoxiaoflood](https://github.com/xiaoxiaoflood/)

Notice: If you are "userChromeJS Loader" developer & doesn't list your name, please contact us. We add the site of your name.

### 📦 Paxmod

- [Paxmod](https://github.com/numirias/paxmod)
- [MIT](https://github.com/numirias/paxmod/blob/master/LICENSE)
- Author: [numirias](https://github.com/numirias/)

Notice: Paxmod is used for reference material and multi-level tab implementation of vertical tabs.

### 📦 showdown

- [showdown](https://github.com/showdownjs/showdown)
- [MIT](https://github.com/showdownjs/showdown/blob/master/LICENSE)
- Author: [SyntaxRules](https://github.com/SyntaxRules)

Notice: If you are "showdown" developer & doesn't list your name, please contact us. We add the site of your name.

### 📄 Betterfox

- [Betterfox](https://github.com/yokoffing/Betterfox)
- [MIT](https://github.com/yokoffing/Betterfox/blob/main/LICENSE)
- Author: [yokoffing](https://github.com/yokoffing)

Notice: Betterfox is not included in Floorp itself, but is downloaded from the Internet.


## Repository View Counter

<div align='center'><a href='https://www.websitecounterfree.com'><img src='https://www.websitecounterfree.com/c.php?d=9&id=38248&s=1' border='0' alt='Free Website Counter'></a><br/><small>
<a href='https://www.websitecounterfree.com'>Free Website Counter: Since 2023 7/22</a></small></div>
