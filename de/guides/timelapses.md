---
title: Timelapses
description: Anleitung zur Konfiguration unserer Timelapses
published: true
date: 2025-12-05T20:04:56.151Z
tags:
editor: markdown
dateCreated: 2025-12-05T19:50:40.491Z
---

# 📸 Was ist ein *Timelapse* im 3D-Druck?

Ein **Timelapse** ist eine beschleunigte Aufnahmetechnik, die es ermöglicht, **den gesamten Herstellungsprozess eines Teils in nur wenigen Sekunden oder Minuten** zu zeigen, obwohl dieser in Wirklichkeit Stunden dauern kann. Es ist eine der visuell beeindruckendsten Ressourcen in der Welt des 3D-Drucks und wird sowohl für Dokumentation als auch für künstlerische oder pädagogische Inhalte verwendet.

## 🧩 Wie funktioniert ein Timelapse?

Die Idee ist einfach:  
Anstatt ein traditionelles Video aufzunehmen, **nimmt die Kamera in festgelegten Zeitintervallen ein Foto auf** (oder bei einem bestimmten Ereignis, z. B. „jedes Mal, wenn eine Schicht fertiggestellt ist“). Später werden all diese Bilder zu einem schnellen Video zusammengesetzt.

Auf diese Weise:

- Ein **8-Stunden-Druck** → wird zu einem **8–20 Sekunden Video**.
- Der Fortschritt des Teils wird flüssig, dynamisch und anschaulich dargestellt.

## 🎥 Arten von Timelapses, die wir mit unserer Artillery M1 Pro verwenden können

### 1. **Intervall-Timelapse – Hyperlapse –**
Die Kamera nimmt alle *X* Sekunden ein Foto auf.  
Es ist einfach, kann aber plötzliche oder unvorhersehbare Bewegungen des Druckkopfs zeigen, da die Fotos während des Druckvorgangs aufgenommen werden.

- ✔️ Einfach einzurichten.
- ❌ Der Druckkopf kann vor dem Druckobjekt „kreuzen“.

> Dies ist die Art von Timelapse, die mit der Stock-Firmware durchgeführt wird. Sie kann auch mit der Community-Firmware verwendet werden.
{.is-info}

### 2. **Schicht-Timelapse (am beliebtesten)**
Die Kamera nimmt **am Ende jeder Schicht** ein Foto auf, normalerweise wenn der Druckkopf sich kurz entfernt oder auf eine feste Position bewegt.

Diese Methode erzeugt die berühmten *„kopflose Timelapses“*, bei denen es so aussieht, als würde das Teil wie von Zauberhand wachsen.

- ✔️ Sehr sauberes Video.
- ✔️ Der Druckkopf steht nie im Weg.
- ❌ Erfordert Firmware- oder Software-Unterstützung (in unserem Fall, dass die Community-Patches aktiviert sind).
- ❌ Die Druckzeit wird merklich länger, da der Extruder sich bei jeder Schicht entfernen muss, um das Bild aufzunehmen.

## Timelapse-Beispiele

<table width="100%">
  <thead>
    <th>Verwendete Einstellungen</th>
    <th>Timelapse</th>
    <th>Druckzeiten</th>
  </thead>
  <tr>
    <td>
      <ul>
        <li>Modus: Layer Macro</li>
        <li>Park Head: Aktiviert</li>
        <li>Park Time: 100ms</li>
        <li>Park Travel Speed: 400mm/s</li>
        <li>Park Position: Back Left</li>
        <li>Park Position Z-Hop: 0.2 mm</li>
        <li>Firmware-Retraktion verwenden: Deaktiviert</li>
        <li>Park Retraction Distance: 1mm</li>
        <li>Park Retraction Speed: 15mm/s</li>
        <li>Park Extrude Distance: 1mm</li>
        <li>Park Extrude Speed: 15mm/s</li>
        <li>Delay Compensation: 50ms</li>
      </ul>
    </td>
    <td>
      <center>
        <video width="320" height="240" autoplay loop muted>
          <source src="/media/video/timelapse-layer.mp4" type="video/mp4">
          Ihr Browser unterstützt das Video-Tag nicht.
        </video>
      </center>
    </td>
    <td>
      4 Stunden 59 Minuten.
    </td>
  </tr>
  <tr>
    <td>
      <ul>
        <li>Modus: Hyperlapse</li>
        <li>Hyperlapse-Zyklus: 90s</li>
        <li>Park Head: Deaktiviert</li>
        <li>Delay Compensation: 50ms</li>
      </ul>
    </td>
    <td>
      <center>
        <video width="320" height="240" autoplay loop muted>
          <source src="/media/video/timelapse-hyperlapse.mp4" type="video/mp4">
          Ihr Browser unterstützt das Video-Tag nicht.
        </video>
      </center>
    </td>
    <td>
      4 Stunden 51 Minuten.
    </td>
  </tr>
</table>

> Sie können den Ordner, in dem Timelapses in Fluidd gespeichert werden, konfigurieren, indem Sie die Datei ``moonraker.conf`` bearbeiten. Wenn Sie sie z. B. auf der Micro-SD-Karte im Ordner ``timelapse`` speichern möchten:
>
> ```
> [timelapse]
> output_path: /home/mks/printer_data/gcodes/sda1/timelapse
> ```

> Mit der Community-Firmware können Sie, falls gewünscht, auch den Extruder in eine Ecke parken lassen, um die Aufnahmen zu machen, was bei einigen Drucken nützlich sein kann, wenn Sie mit den Aufnahmezeiten spielen möchten, um mehrere Frames pro Schicht zu erhalten.
{.is-info}
