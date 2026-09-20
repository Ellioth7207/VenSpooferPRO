<div align="center">
  <img src="https://i.ibb.co.com/NRBtBj7/file-00000000d96481fdb3b007c0e3483aee.png" alt="VenSpooferPRO" width="100%">
</div>

<div align="center">

<a href="https://sfl.gl/7BzbALC"><img src="https://img.shields.io/badge/Download-TapHere-0A84FF?style=flat-square&logo=android&logoColor=white" alt="Download VenSpooferPRO" style="border:2px solid #0A84FF;border-radius:8px;padding:2px;"></a>
<a href="https://t.me/Vennec"><img src="https://img.shields.io/badge/Telegram-@VENNEC-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Support Channel" style="border:2px solid #0A84FF;border-radius:8px;padding:2px;"></a>

</div>

<p align="center"><sub>Interactive device &amp; Spoofer for Unlock GAME Graphic & Fps.</sub></p>

## What It Does

VenSpooferPRO is a module that spoofs your device's `ro.product.*` and `ro.soc.*` build properties to match a real, higher-spec phone. Many games gate high-refresh-rate graphics and FPS options behind a device allow-list — by presenting your device as one of those allow-listed models, VenSpooferPRO unlocks those graphics/FPS settings.

At install time you pick a target device with your volume keys — no manual editing required. The selection is saved and silently re-applied on every boot.

## Features

- **Interactive device picker** — cycle profiles with **Volume Down**, confirm with **Volume Up**, right on the flash screen (180s selection timeout)
- **Persistent spoofing** — the chosen profile is re-applied on every boot via `resetprop`, no re-flash needed
- **Boot notification** — shows the currently active spoofed device once boot completes
- **Safe validation** — install aborts cleanly if the device menu can't run (no `getevent`) or the selected profile is missing, instead of leaving the device half-configured

## Available Spoofing

| # | Device | Chipset |
| --- | --- | --- |
| 1 | Infinix GT 50 Pro | Dimensity 8400 Ultra |
| 2 | RedMagic 11 Pro+ | Snapdragon 8 Elite Gen 5 |
| 3 | Realme P3 5G | Snapdragon 6 Gen 4 |
| 4 | Xiaomi 14T | Dimensity 8300 Ultra |
| 5 | Galaxy S25 Ultra | Snapdragon 8 Elite |
| 6 | **Mi 11T Pro** ⭐ *Recommended* | Snapdragon 888 |

## Requirements

- Rooted device running Root Manager.
- `getevent` available on-device (used to read volume-key input during install).

## Installation

1. Flash the module ZIP from your root manager's app.
2. During install, use **Volume Down** to cycle through devices and **Volume Up** to confirm your pick.
3. Reboot. The spoof is re-applied automatically on every subsequent boot.

> **Note:** If a game's graphics/FPS don't unlock after spoofing, clear that game's data (or reinstall it) so it re-reads the device info fresh.

## Changelog

**Stable-2026**
- Added **Mi 11T Pro** as a new spoof profile, marked **Recommended** in the device selection menu

---

## Attribution and Redistribution Policy

Re-uploading, mirroring, or redistributing VenSpooferPRO is permitted under the following terms.

**Attribution is required.** Every redistribution must clearly and visibly credit the original source:

> Source: @vennec

This attribution must not be removed, hidden, or replaced.

**Not permitted:**

- Claiming VenSpooferPRO as original work
- Removing, hiding, or replacing the `@vennec` attribution
- Presenting an unofficial build as an official VenSpooferPRO release
- Removing the original source or download information
- Changing, shortening, redirecting, or hiding the official links without authorization
- Using modified links in a way that misleads users about the project's origin

## Link Policy

Official links associated with VenSpooferPRO (download, source, and release links) must not be changed, replaced, shortened, redirected, or hidden without prior written permission from [Telegram : @ellioth7207](https://github.com/ellioth7207). This applies to links in redistribution posts and repackaged copies of the module alike.

## Disclaimer

VenSpooferPRO modifies Android system properties (device identity and display refresh-rate/FPS-unlock properties). The author assumes no responsibility for bootloops, system instability, data loss, device malfunction, incompatibility with specific devices, conflicts with other modules, or any other damage resulting from use of this module. Install and use at your own risk.

## Credits

| Role | Handle |
| --- | --- |
| Development and maintenance | [@vennec](https://t.me/Vennec) |
| Link authorization | [@ellioth7207](https://t.me/ellioth7207) |

<hr>

<p align="center"><sub>Copyright ©VENNEC . All attribution and link‑policy terms above apply to any redistribution of this project.</sub></p>

<div align="center">

<a href="https://i.ibb.co.com/TxNqw4c4/qr-ID1026576754000-03-09-26-1788411437-1788411438034.jpg"><img src="https://img.shields.io/badge/Donate-QRIS-FF9500?style=flat-square" alt="Donate" style="border:2px solid #0A84FF;border-radius:8px;padding:2px;"></a>

</div>
