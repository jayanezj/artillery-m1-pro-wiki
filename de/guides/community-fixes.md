---
title: Installation von Community-Patches
description: Anleitung zur Installation von Community-Patches
published: true
date: 2025-11-26T19:22:15.694Z
tags:
editor: markdown
dateCreated: 2025-11-24T21:06:14.554Z
---

# Vor Beginn

> Versuche nicht, den automatischen Patcher auf einer anderen Firmware-Version als erwartet zu verwenden – dein Drucker könnte unbrauchbar werden und du müsstest das Basissystem neu installieren!
{.is-danger}

> Das Modifizieren der Drucker-Firmware führt zum Erlöschen der Garantie und kann potenzielle Probleme verursachen. Lies die Informationen des Patchers, bevor du beginnst.
{.is-danger}

* Derzeit unterstützte Versionen:
  * [V1.00.12.0](https://wiki.artillery3d.com/m1/manual/m1-firmware-release-history#v1001200-20251104)
  * [V1.00.11.0](https://wiki.artillery3d.com/m1/manual/m1-firmware-release-history#v1001100-20250829)

# Video-Anleitung

https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/printer-patcher-guide:f

# Anleitung

## IP-Adresse

* Dein Drucker muss im selben Netzwerk wie der Computer/Android-Gerät sein, das du verwenden wirst.
* Du kannst die IP-Adresse am Bildschirm des Druckers im vierten Button des linken Menüs (Einstellungen) -> Reiter WiFi überprüfen.

## Community-Patch-Software

* [Printer Patcher Repository](https://github.com/pijalu/printer-patcher/releases)

Lade die Anwendung passend zu deinem Gerät herunter.

> Unter macOS musst du die Ausführung der Anwendung über einen im readme.txt enthaltenen Befehl erlauben. Wenn du dies nicht tust, erscheint ein Fehler, dass die App beschädigt sei, da sie kein Apple-Signaturzertifikat besitzt. Die Nutzung ist sicher.
{.is-info}

Mit Printer Patcher kannst du:
* Die [Fluidd](https://docs.fluidd.xyz/) Schnittstelle wiederherstellen.
* Community-Patches installieren.
* Logs von [Klipper](https://www.klipper3d.org/Debugging.html), Moonraker, seriellen Port und USB abrufen.

1. Gib die zuvor ermittelte IP-Adresse deines Druckers ein.
1. Stelle die Fluidd-Schnittstelle wieder her und installiere die Community-Patches.

> Beim Installieren der Community-Patches wird der Drucker, selbst wenn Printer Patcher den Prozess abschließt, noch mindestens 10 Minuten Moonraker-Updates installieren. **Trenne den Drucker nicht**, damit die Aktualisierung korrekt abgeschlossen wird.
{.is-warning}

> Nach vollständigem Abschluss der Paketinstallationen kannst du deinen Drucker mit Fluidd unter <kbd>http://drucker_adresse:8078</kbd> sehen.
>
> Du kannst auch Mainsail unter <kbd>http://drucker_adresse</kbd> aufrufen.
{.is-success}

> Credits an [@pijalu](https://github.com/pijalu) für die Entwicklung des Tools zum Patchen des Druckers sowie der Community-Profile und Firmware-Modifikationen.
