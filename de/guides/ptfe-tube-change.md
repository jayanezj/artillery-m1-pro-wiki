---
title: PTFE-Schlauch Austausch
description: Anleitung zum Austausch des PTFE-Schlauchs
published: true
date: 2025-11-26T13:38:16.232Z
tags:
editor: markdown
dateCreated: 2025-11-26T13:37:30.907Z
---

# Der PTFE-Schlauch
Dieser Schlauch führt das Filament von der Spule zum Extruder.

## Benötigte Teile
<table>
<tr>
  <th>Teil</th>
  <th>Bild</th>
</tr>
<tr>
  <td>

- **Einweg-Verbinder:** Dieser Verbinder verhindert, dass sich der Schlauch vom Extruder nach außen bewegt.
  - Du kannst den Verbinder des originalen PTFE-Schlauchs wiederverwenden.
  - Ersatzverbinder sind im [Artillery-Kit](https://artillery3d.com/products/ptfe-tube-m1) enthalten.
  - Ein kompatibler Verbinder ist auch auf [Aliexpress (ptfe embedded bowden collect)](https://aliexpress.com/item/1005009105267126.html) erhältlich.

  </td>
  <td>

![ptfe-collector.webp](/media/images/ptfe-collector.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>

- **Silikon-Manschetten-Klemme:** Sichert den Schlauch vom Inneren zum Äußeren der Maschine. Der Außendurchmesser des Silikonschlauchs mit PTFE liegt bei ca. 5,3 mm.
  - Du kannst die werkseitig installierte Klemme wiederverwenden.
  - Kompatible Ersatzklemmen gibt es auf [Aliexpress (White Hose Clamps 5~5.5mm)](https://aliexpress.com/item/1005005697827712.html).

  </td>
  <td>

![ptfe-hose-clamp.webp](/media/images/ptfe-hose-clamp.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>

- **PTFE-Schlauch:** Dieser Schlauch führt das Filament von der Spule zum Extruder, daher sollte der Innendurchmesser (2,5~3,0 mm) etwas größer sein als im Bowden-System (1,9~2,2 mm) üblich.
  - [Ersatzschlauch von Artillery](https://artillery3d.com/products/ptfe-tube-m1)
  - [Capricorn Ersatzschlauch](https://www.captubes.com/shop/#!/Filament-Guide/c/173671010) (Innendurchmesser 3, Außendurchmesser 4). Die besten PTFE-Schläuche auf dem Markt.
  - [Mellow Ersatzschlauch](https://aliexpress.com/item/1005008268651680.html) (Innendurchmesser 3, Außendurchmesser 4). Bewährte Qualität.
  - [Mellow Niedrig-Reibung Stern-Schlauch](https://aliexpress.com/item/1005010202912335.html) (Innendurchmesser 2,2, Außendurchmesser 4). Obwohl er einen Bowden-spezifischen Innendurchmesser hat, sorgt das sternförmige Design für weniger Reibung; **für TPU oder abrasive Materialien wird er jedoch nicht empfohlen** (das sternförmige Design kann mit diesen Filamenten mehr Reibung erzeugen als ein konventioneller Schlauch)[^1].

  </td>
  <td>

![ptfe-tube.webp](/media/images/ptfe-tube.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>

- **PTFE-Schlauch Demontage-Werkzeug:** Dieses Werkzeug erlaubt das Entfernen des PTFE-Schlauchs aus dem Extruder.
  - Verfügbar auf der MicroSD-Karte des Druckers.
  - [STL des Werkzeugs.](/media/stl/official_disassembling_ptfe_tool.zip)

  </td>
  <td>

![ptfe-tool.webp](/media/images/ptfe-tool.webp =640x){.align-center}

  </td>
</tr>
</table>

## Video-Anleitung

https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/change_ptfe_tube_guide:e

## Anleitung

> Artillery bietet ein [Tutorial in ihrem Wiki](https://wiki.artillery3d.com/m1/maintenance/add-the-ptfe-connector-assembly) zum Schlauchwechsel.
{.is-info}

### Vorbereitung

Entferne das Filament vor Beginn und trenne den Drucker vom Stromnetz.

### PTFE-Schlauch entfernen

<table>
<tr>
  <th>Schritt</th>
  <th>Bild (zum Vergrößern klicken)</th>
</tr>
<tr>
  <td>

1. Entferne die weiße Klemme, die die Manschette außen am Drucker sichert.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-1.webp" target="_blank">![change-ptfe-tube-step-1.webp](/media/images/change-ptfe-tube-step-1.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

2. Ziehe mit dem Extraktionswerkzeug den Schlauch aus dem Extruder.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-2.webp" target="_blank">![change-ptfe-tube-step-2.webp](/media/images/change-ptfe-tube-step-2.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

3. Trenne die Verbindungsklemmen und entferne die Klemme in der Nähe des Extruders (falls noch vorhanden).

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-3.webp" target="_blank">![change-ptfe-tube-step-3.webp](/media/images/change-ptfe-tube-step-3.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

4. Entferne den Clip vom Einweg-Verbinder und ziehe ihn von der Extruder-Seite heraus.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-4.webp" target="_blank">![change-ptfe-tube-step-4.webp](/media/images/change-ptfe-tube-step-4.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

5. Ziehe den PTFE-Schlauch von innen nach außen. Der Einweg-Verbinder am Ende des Schlauchs erlaubt nur das Herausziehen von der Extruder-Seite, **nicht in die entgegengesetzte Richtung** (beschädigt sonst den Schlauch).

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-5.webp" target="_blank">![change-ptfe-tube-step-5.webp](/media/images/change-ptfe-tube-step-5.webp =640x){.align-center}</a>

  </td>
</tr>
</table>

### PTFE-Schlauch einsetzen

<table>
<tr>
  <td>

6. Setze den Einweg-Verbinder ein, der im Inneren des Druckers sitzt. Die Stelle, an der der blaue Clip sitzt, ist der Wand des Druckers am nächsten.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-6.webp" target="_blank">![change-ptfe-tube-step-6.webp](/media/images/change-ptfe-tube-step-6.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

7. Führe den PTFE-Schlauch in den Extruder ein und passe die Schlauchlänge an, indem du den Extruder über das Druckbett bewegst.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-7.webp" target="_blank">![change-ptfe-tube-step-7.webp](/media/images/change-ptfe-tube-step-7.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

8. Befestige die Verbindungsklemmen und sichere den Einweg-Verbinder mit dem blauen Clip.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-8.webp" target="_blank">![change-ptfe-tube-step-8.webp](/media/images/change-ptfe-tube-step-8.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

9. Befestige die weiße Klemme am Silikon-Pin. **Nicht zu fest anziehen, gerade so, dass der PTFE-Schlauch gehalten wird.**

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-9.webp" target="_blank">![change-ptfe-tube-step-9.webp](/media/images/change-ptfe-tube-step-9.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

10. Führe den PTFE-Schlauch durch den finalen Einweg-Verbinder.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-10.webp" target="_blank">![change-ptfe-tube-step-10.webp](/media/images/change-ptfe-tube-step-10.webp =640x){.align-center}</a>

  </td>
</tr>
</table>

[^1]: https://forum.bambulab.com/t/star-shaped-ptfe-tube/190829
