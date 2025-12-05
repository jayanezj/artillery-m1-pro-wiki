---
title: Timelapses
description: Guía para configurar nuestros Timelapses
published: true
date: 2025-12-05T20:04:56.151Z
tags: 
editor: markdown
dateCreated: 2025-12-05T19:50:40.491Z
---

# 📸 ¿Qué es un *Timelapse* en Impresión 3D?

Un **timelapse** es una técnica de grabación acelerada que permite **mostrar en pocos segundos o minutos** todo el proceso de fabricación de una pieza que, en realidad, puede tardar horas. Es uno de los recursos visuales más llamativos dentro del mundo de la impresión 3D, y se utiliza tanto para documentación como para contenido artístico o divulgativo.

## 🧩 ¿Cómo funciona un timelapse?

La idea es simple:  
En lugar de grabar un vídeo tradicional, la cámara **captura una foto cada cierto intervalo de tiempo** (o cada evento específico, como “cada vez que finaliza una capa”). Más tarde, todas esas imágenes se unen para formar un vídeo a alta velocidad.

De este modo:

- Una impresión de **8 horas** → se convierte en un vídeo de **8–20 segundos**.
- Se muestra el avance de la pieza de manera fluida, dinámica y muy visual.

## 🎥 Tipos de timelapse que podemos utilizar en nuestra Artillery M1 Pro

### 1. **Timelapse por intervalo de tiempo – Hyperlapse –**
La cámara toma una foto cada *X* segundos.  
Es sencillo, pero puede mostrar movimientos bruscos o impredecibles del cabezal, porque las fotos se hacen mientras la impresora está trabajando.

- ✔️ Fácil de configurar.
- ❌ El cabezal puede “cruzarse” por delante de la impresión.

> Este es el tipo de Timelapse que se realiza con el Firmware Stock. También se puede utilizar con el Firmware comunitario.
{.is-info}

### 2. **Timelapse por capa (el más popular)**
La cámara toma la foto **al finalizar cada capa**, normalmente cuando el cabezal se retira momentáneamente o se mueve a una posición fija.

Este método genera los famosos *“timelapses sin cabezal”*, donde parece que la pieza crece por arte de magia.

- ✔️ Vídeo muy limpio.
- ✔️ El cabezal no estorba.
- ❌ Requiere soporte del firmware o del software (en nuestro caso que tengas los parches comunitarios activos). 
- ❌ El tiempo de impresión será sensiblemente mayor al tener que retirar el extrusor en cada capa para tomar la imagen. 

## Ejemplos de Timelapse

<table width="100%">
  <thead>
    <th>Ajustes utilizados</th>
    <th>Timelapse</th>
    <th>Tiempos de impresión</th>
  </thead>
  <tr>
    <td>
      <ul>
        <li>Mode: Layer Macro</li>
        <li>Park Head: Activado</li>
        <li>Park Time: 100ms</li>
        <li>Park Travel Speed: 400mm/s</li>
        <li>Park Position: Back Left</li>
        <li>Park Position Z-Hop: 0.2 mm</li>
        <li>Use Firmware retraction: Desactivado</li>
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
          Your browser does not support the video tag.
        </video>
      </center>
    </td>
    <td>
      4 horas 59 minutos.
    </td>
  </tr>
  <tr>
    <td>
      <ul>
        <li>Mode: Hyperlapse</li>
        <li>Hyperlapse Cycle: 90s</li>
        <li>Park Head: Desactivado</li>
        <li>Delay Compensation: 50ms</li>
      </ul>
    </td>
    <td>
      <center>
        <video width="320" height="240" autoplay loop muted>
          <source src="/media/video/timelapse-hyperlapse.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </center>
    </td>
    <td>
      4 horas 51 minutos.
    </td>
  </tr>
</table>

> Puedes configurar la ruta en la que se almacenarán los Timelapses en Fluidd editando el fichero ``moonraker.conf``. Por ejemplo, si quieres que se guarden dentro de ``timelapse`` en la tarjeta Micro SD:
>
> ```
> [timelapse]
> output_path: /home/mks/printer_data/gcodes/sda1/timelapse
> ```

> Con el Firmware comunitario, si lo deseamos, también podemos hacer que el Hyperlase aparque el extrusor en una esquina para tomar las capturas, lo que puede ser interesante en algunas impresiones en las que queramos jugar con los tiempos de captura para tener varios frames por capa.
{.is-info}

