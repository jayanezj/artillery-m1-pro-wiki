---
title: Installation of Community Patches
description: Guide for installing community patches
published: true
date: 2025-11-26T19:22:15.694Z
tags:
editor: markdown
dateCreated: 2025-11-24T21:06:14.554Z
---

# Before You Begin

> Do not attempt to use the automatic patcher on a different Firmware version than expected — your printer may become bricked and you will need to reinstall the base system!
{.is-danger}

> Modifying the printer’s firmware will void the warranty and may cause potential issues. Read the information provided by the patcher before you begin.
{.is-danger}

* Currently supported versions:
  * [V1.00.12.0](https://wiki.artillery3d.com/m1/manual/m1-firmware-release-history#v1001200-20251104)
  * [V1.00.11.0](https://wiki.artillery3d.com/m1/manual/m1-firmware-release-history#v1001100-20250829)

# Video Guide

https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/printer-patcher-guide:f

# Guide

## IP Address

* Your printer must be on the same network as the computer/Android device you will use.
* You can check the IP address from the printer’s screen in the fourth button of the left menu (Settings) -> WiFi tab.

## Community Patch Software

* [Printer Patcher Repository](https://github.com/pijalu/printer-patcher/releases)

Download the application based on your device.

> On macOS you must allow the application to run using a command included in the readme.txt file. If you do not, an error will appear stating that the app is damaged because it does not have an Apple signature certificate. It is safe to use.
{.is-info}

From Printer Patcher you will be able to:
* Restore the [Fluidd](https://docs.fluidd.xyz/) interface.
* Install community patches.
* Retrieve logs from [Klipper](https://www.klipper3d.org/Debugging.html), Moonraker, serial port, USB.

1. Enter the IP address of your printer obtained earlier.
1. Restore the Fluidd interface and install the community patches.

> When installing community patches, even if Printer Patcher completes the process, the printer will continue installing Moonraker updates for at least 10 more minutes. **Do not disconnect the printer** so the update completes correctly.
{.is-warning}

> Once all package installations finish completely you will be able to see your printer with Fluidd running at <kbd>http://printer_address:8078</kbd>
>
> You can also view Mainsail at <kbd>http://printer_address</kbd>
{.is-success}

> Credits to [@pijalu](https://github.com/pijalu) for developing the tool to patch the printer, as well as the community profiles and firmware modifications.
