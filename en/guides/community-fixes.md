---
title: Setting up community fixes
description: Tutorial for installing community fixes
published: true
date: 2025-11-24T21:14:31.978Z
tags: 
editor: markdown
dateCreated: 2025-11-24T21:14:31.978Z
---

# Before starting

> **Do not attempt to use the automatic patcher on a Firmware version different from the expected ones. Your printer could become bricked and you will need to reinstall the base system!**
> {.is-warning}

* Currently supported versions:

  * [V1.00.12.0](https://wiki.artillery3d.com/m1/manual/m1-firmware-release-history#v1001200-20251104)
  * [V1.00.11.0](https://wiki.artillery3d.com/m1/manual/m1-firmware-release-history#v1001100-20250829)

# Video tutorial

https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/printer-patcher-guide:f

# Tutorial

## IP Address

* Your printer must be on the same network as the computer/Android device you will use.
* You can check the IP address on the printer’s screen under the fourth button on the left menu (Settings) → WiFi tab.

## Community patching software

* [Printer Patcher Repository](https://github.com/pijalu/printer-patcher/releases)

Download the application according to your device.

> On macOS, you must allow the application to run using a command included in the readme.txt file. If not, you will get an error saying the app is damaged because it lacks an Apple signing certificate. It is safe to use.
> {.is-info}

With Printer Patcher you can:

* Restore the [Fluidd](https://docs.fluidd.xyz/) interface.
* Install community patches.
* Retrieve logs from [Klipper](https://www.klipper3d.org/Debugging.html), Moonraker, serial port, and USB.

1. Enter the IP address of your printer obtained earlier.
2. Restore the Fluidd interface and install the community patches.

> When installing the community patches, even if the installation process within Printer Patcher finishes, the printer will still be installing Moonraker updates for at least 10 more minutes. **Do not turn off the printer** so the update can complete correctly.
> {.is-warning}

> Once the package installation is fully completed, you will be able to access your printer with Fluidd at:
> `http://printer_address:8078`
> {.is-success}