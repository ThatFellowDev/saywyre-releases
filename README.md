<div align="center">

<img src="assets/saywyre-icon.png" width="96" height="96" alt="Saywyre icon">

# Saywyre

**Talk instead of type.** Hold a shortcut, say it, let go. Your words appear wherever you're typing.

Free for Windows, macOS and Linux.

<a href="https://github.com/ThatFellowDev/saywyre-releases/releases/latest/download/Saywyre-Windows-Setup.exe"><img src="assets/download-windows.svg" width="232" height="56" alt="Download for Windows"></a>
<a href="https://github.com/ThatFellowDev/saywyre-releases/releases/latest/download/Saywyre-macOS.dmg"><img src="assets/download-macos.svg" width="232" height="56" alt="Download for macOS"></a>
<a href="https://github.com/ThatFellowDev/saywyre-releases/releases/latest/download/Saywyre-Linux.AppImage"><img src="assets/download-linux.svg" width="232" height="56" alt="Download for Linux"></a>

<sub>macOS needs an Apple silicon Mac (M1 or newer). Installing on Linux? .AppImage runs anywhere, .deb for Ubuntu/Debian ([get the .deb](https://github.com/ThatFellowDev/saywyre-releases/releases/latest/download/Saywyre-Linux.deb)).</sub>

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stats-dark.png">
  <img src="assets/stats-light.png" width="760" alt="The Saywyre app showing your streak, words per day and top apps">
</picture>

</div>

## What you get

<table>
<tr><td width="56"><img src="assets/icon-talk.svg" width="44" height="44" alt=""></td><td><b>Works in any app.</b> Email, chat, docs, your code editor. If it has a cursor, you can talk into it.</td></tr>
<tr><td><img src="assets/icon-device.svg" width="44" height="44" alt=""></td><td><b>Runs on your computer.</b> Your voice turns into text on your own machine, so it keeps working offline.</td></tr>
<tr><td><img src="assets/icon-clean.svg" width="44" height="44" alt=""></td><td><b>Cleans up as you go.</b> The "um"s and "uh"s come out before the text lands.</td></tr>
<tr><td><img src="assets/icon-words.svg" width="44" height="44" alt=""></td><td><b>Learns your words.</b> Add the names and terms you use, and Saywyre spells them right.</td></tr>
<tr><td><img src="assets/icon-stats.svg" width="44" height="44" alt=""></td><td><b>Shows your progress.</b> Search everything you said and see your words per day, streak and time saved.</td></tr>
</table>

## Install

<details>
<summary><b>Windows</b></summary>

1. [Download the installer](https://github.com/ThatFellowDev/saywyre-releases/releases/latest/download/Saywyre-Windows-Setup.exe) and run it.
2. If Windows says it protected your PC, click **More info**, then **Run anyway**. The installer isn't code-signed yet.

</details>

<details>
<summary><b>Linux</b></summary>

Pick one:

- **Ubuntu or Debian:** [download the .deb](https://github.com/ThatFellowDev/saywyre-releases/releases/latest/download/Saywyre-Linux.deb), then run `sudo apt install ./Saywyre-Linux.deb`.
- **Any distro:** [download the .AppImage](https://github.com/ThatFellowDev/saywyre-releases/releases/latest/download/Saywyre-Linux.AppImage), run `chmod +x Saywyre-Linux.AppImage`, then open it.

Both are for 64-bit Intel and AMD computers. If the AppImage won't open, install libfuse2 (`sudo apt install libfuse2t64` on Ubuntu 24.04).

</details>

<details>
<summary><b>macOS</b></summary>

1. [Download the .dmg](https://github.com/ThatFellowDev/saywyre-releases/releases/latest/download/Saywyre-macOS.dmg) and open it.
2. Drag Saywyre into Applications.

This build is for Apple silicon Macs (M1 or newer).

</details>

<details>
<summary><b>What are the other files on the release page?</b></summary>

- `.sig` files and `.tar.gz` files power auto-update inside the app. You never need to download them.
- `latest.json` tells the app which version is newest.
- "Source code (zip)" and "Source code (tar.gz)" are added by GitHub to every release automatically. This repo holds no app source.

</details>

On first start, Saywyre downloads its speech model. After that, hold **Alt + Shift + Space**, talk, and let go. If another app already uses that shortcut, Saywyre picks a free one and shows it on the Today screen. You can change it any time.

## Your privacy

Your voice is turned into text on your computer. Recordings aren't saved unless you switch on **Keep audio** in Settings, and your history and stats stay on your computer.

## Updates

Saywyre checks this page for new versions and downloads nothing until you click to install. Each update is signed, and Saywyre refuses one whose signature doesn't match. You can also check from **Settings > About**.

---

<div align="center">

Made by [Postwyre](https://postwyre.com)

</div>
