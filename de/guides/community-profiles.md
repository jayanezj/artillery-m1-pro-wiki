---
title: Installation von Community-Profilen
description: Anleitung zur Installation von Community-Profilen
published: true
date: 2025-11-26T19:17:08.087Z
tags:
editor: markdown
dateCreated: 2025-11-24T22:26:26.154Z
---

# Vor Beginn

> Versuche nicht, diese Community-Profile zu verwenden, ohne zuvor die Firmware des Druckers modifiziert zu haben. Beginne mit der [Anleitung zur Installation von Community-Patches](/de/guides/community-fixes)
{.is-danger}

* [GitHub mit Community-Profilen](https://github.com/pijalu/artillery-m1-orca)

# Video-Anleitung

## OrcaSlicer (Empfohlen)

https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/community-profiles-Guide:6

# Anleitung

## OrcaSlicer (Empfohlen)

* Lade die Community-Profile von [GitHub](https://github.com/pijalu/artillery-m1-orca/releases) herunter.
* Öffne OrcaSlicer und navigiere zu ``Datei -> Importieren -> Konfigurationen importieren...``.
* Wähle die ``.zip``-Datei aus; alle Profile werden automatisch geladen.
* In der Sektion ``Vorbereiten -> Drucker`` siehst du nun die importierten Profile.
* Wenn du auf das WiFi-Symbol klickst, kannst du die Remote-Verbindung konfigurieren:
  * Host-Typ: ``Octo/Klipper``
  * Hostname, IP oder URL: ``DRUCKER_IP:8078`` ([Fluidd](https://docs.fluidd.xyz/)) oder ``DRUCKER_IP`` ([Mainsail](https://docs.mainsail.xyz/))
* In der Sektion ``Gerät`` siehst du den Drucker.

## Artillery Studio (Nicht empfohlen)

> Artillery Studio unterstützt Community-Profile nicht direkt. Da es auf OrcaSlicer basiert, ist es besser, direkt OrcaSlicer zu verwenden. Außerdem verlieren wir die Möglichkeit, Fluidd/Mainsail vom Geräte-Panel aus zu sehen (über den Browser bleibt es zugänglich).
{.is-warning}

* Lade die Community-Profile von [GitHub](https://github.com/pijalu/artillery-m1-orca/releases) herunter.
* Entpacke die heruntergeladene ``.zip``-Datei. Sie enthält für jedes Profil eine ``.json``-Datei.
* Suche den Inhalt von ``machine_start_gcode`` in der ``.json``-Datei des gewählten Profils und kopiere ihn.
* Öffne Artillery Studio.
* In der Sektion ``Vorbereiten -> Drucker`` klicke auf Konfigurieren beim Profil Artillery M1 Pro.
* Aktiviere die erweiterten Optionen (falls nicht bereits aktiviert) über den Button oben rechts.
* Gehe zum Tab ``Machine G-Code`` und ersetze den Inhalt von ``Start G-Code`` durch den zuvor kopierten Code aus der ``.json``.

> Credits an [@pijalu](https://github.com/pijalu) für die Entwicklung des Tools zum Patchen des Druckers sowie der Community-Profile und Firmware-Modifikationen.
