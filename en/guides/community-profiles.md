---
title: Installation of Community Profiles
description: Guide for installing community profiles
published: true
date: 2025-11-26T19:17:08.087Z
tags:
editor: markdown
dateCreated: 2025-11-24T22:26:26.154Z
---

# Before You Begin

> Do not attempt to use these community profiles without first modifying the printer’s firmware. Start with the [community patch installation guide](/en/guides/community-fixes)
{.is-danger}

* [GitHub with community profiles](https://github.com/pijalu/artillery-m1-orca)

# Video Guide

## OrcaSlicer (Recommended)

https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/community-profiles-Guide:6

# Guide

## OrcaSlicer (Recommended)

* Download the community profiles from [GitHub](https://github.com/pijalu/artillery-m1-orca/releases).
* Open OrcaSlicer and navigate to ``File -> Import -> Import Configurations...``.
* Select the ``.zip`` file and all profiles will be loaded automatically.
* Now, in the ``Prepare -> Printer`` section, you will see the imported profiles.
* If you click on the WiFi icon, you can configure the remote connection:
  * Host Type: ``Octo/Klipper``
  * Hostname, IP, or URL: ``PRINTER_IP:8078`` ([Fluidd](https://docs.fluidd.xyz/)) or ``PRINTER_IP`` ([Mainsail](https://docs.mainsail.xyz/))
* In the ``Device`` section, you will see the printer.

## Artillery Studio (Not Recommended)

> Artillery Studio does not directly support community profiles, and since it is based on OrcaSlicer, it is better to use OrcaSlicer directly. Additionally, we lose the ability to view Fluidd/Mainsail from the device panel (although it is still accessible via a browser).
{.is-warning}

* Download the community profiles from [GitHub](https://github.com/pijalu/artillery-m1-orca/releases).
* Unzip the downloaded ``.zip`` file. It contains ``.json`` files for each profile.
* Locate and copy the contents of ``machine_start_gcode`` from the ``.json`` of the profile you choose.
* Open Artillery Studio.
* In the ``Prepare -> Printer`` section, click Configure on the Artillery M1 Pro profile.
* Enable advanced options (if not already enabled) by clicking the button in the top-right area.
* Go to the ``Machine G-Code`` tab and replace the ``Start G-Code`` content with the code from the previous ``.json``.

> Credits to [@pijalu](https://github.com/pijalu) for developing the tool to patch the printer, as well as the community profiles and firmware modifications.
