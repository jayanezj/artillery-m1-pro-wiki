---
title: Timelapses
description: Guide pour configurer nos Timelapses
published: true
date: 2025-12-05T20:04:56.151Z
tags:
editor: markdown
dateCreated: 2025-12-05T19:50:40.491Z
---

# 📸 Qu'est-ce qu'un *Timelapse* en impression 3D ?

Un **timelapse** est une technique d'enregistrement accéléré qui permet de **montrer en quelques secondes ou minutes** tout le processus de fabrication d'une pièce qui, en réalité, peut prendre des heures. C'est l'une des ressources visuelles les plus frappantes dans le monde de l'impression 3D, utilisée à la fois pour la documentation et pour du contenu artistique ou éducatif.

## 🧩 Comment fonctionne un timelapse ?

L'idée est simple :  
Au lieu d'enregistrer une vidéo traditionnelle, la caméra **capture une photo à un intervalle de temps défini** (ou lors d'un événement spécifique, comme « à chaque fois qu'une couche est terminée »). Ensuite, toutes ces images sont combinées pour former une vidéo à grande vitesse.

Ainsi :

- Une impression de **8 heures** → devient une vidéo de **8–20 secondes**.
- L'avancement de la pièce est montré de manière fluide, dynamique et visuelle.

## 🎥 Types de timelapses que nous pouvons utiliser sur notre Artillery M1 Pro

### 1. **Timelapse par intervalle – Hyperlapse –**
La caméra prend une photo toutes les *X* secondes.  
C'est simple, mais cela peut montrer des mouvements brusques ou imprévisibles de la tête d'impression, car les photos sont prises pendant que l'imprimante fonctionne.

- ✔️ Facile à configurer.
- ❌ La tête d'impression peut passer devant la pièce.

> C'est le type de Timelapse réalisé avec le Firmware Stock. Il peut également être utilisé avec le Firmware communautaire.
{.is-info}

### 2. **Timelapse par couche (le plus populaire)**
La caméra prend la photo **à la fin de chaque couche**, généralement lorsque la tête d'impression s'éloigne momentanément ou se déplace à une position fixe.

Cette méthode génère les célèbres *« timelapses sans tête »*, où il semble que la pièce grandisse par magie.

- ✔️ Vidéo très propre.
- ✔️ La tête d'impression ne gêne jamais.
- ❌ Nécessite le support du firmware ou du logiciel (dans notre cas, que vous ayez les patchs communautaires activés).
- ❌ Le temps d'impression sera sensiblement plus long, car l'extrudeur doit s'éloigner à chaque couche pour prendre la photo.

## Exemples de Timelapse

<table width="100%">
  <thead>
    <th>Paramètres utilisés</th>
    <th>Timelapse</th>
    <th>Temps d'impression</th>
  </thead>
  <tr>
    <td>
      <ul>
        <li>Mode : Layer Macro</li>
        <li>Park Head : Activé</li>
        <li>Park Time : 100ms</li>
        <li>Park Travel Speed : 400mm/s</li>
        <li>Park Position : Back Left</li>
        <li>Park Position Z-Hop : 0.2 mm</li>
        <li>Use Firmware retraction : Désactivé</li>
        <li>Park Retraction Distance : 1mm</li>
        <li>Park Retraction Speed : 15mm/s</li>
        <li>Park Extrude Distance : 1mm</li>
        <li>Park Extrude Speed : 15mm/s</li>
        <li>Delay Compensation : 50ms</li>
      </ul>
    </td>
    <td>
      <center>
        <video width="320" height="240" autoplay loop muted>
          <source src="/media/video/timelapse-layer.mp4" type="video/mp4">
          Votre navigateur ne supporte pas la balise vidéo.
        </video>
      </center>
    </td>
    <td>
      4 heures 59 minutes.
    </td>
  </tr>
  <tr>
    <td>
      <ul>
        <li>Mode : Hyperlapse</li>
        <li>Hyperlapse Cycle : 90s</li>
        <li>Park Head : Désactivé</li>
        <li>Delay Compensation : 50ms</li>
      </ul>
    </td>
    <td>
      <center>
        <video width="320" height="240" autoplay loop muted>
          <source src="/media/video/timelapse-hyperlapse.mp4" type="video/mp4">
          Votre navigateur ne supporte pas la balise vidéo.
        </video>
      </center>
    </td>
    <td>
      4 heures 51 minutes.
    </td>
  </tr>
</table>

> Vous pouvez configurer le dossier où les Timelapses seront stockés dans Fluidd en modifiant le fichier ``moonraker.conf``. Par exemple, si vous souhaitez qu'ils soient enregistrés dans ``timelapse`` sur la carte Micro SD :
>
> ```
> [timelapse]
> output_path: /home/mks/printer_data/gcodes/sda1/timelapse
> ```

> Avec le Firmware communautaire, si vous le souhaitez, vous pouvez également faire en sorte que Hyperlapse gare l'extrudeur dans un coin pour prendre les captures, ce qui peut être utile pour certaines impressions où vous voulez jouer avec le timing des captures pour obtenir plusieurs images par couche.
{.is-info}
