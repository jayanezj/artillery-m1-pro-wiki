---
title: Extrusor flojo
description: Guía para apretar el extrusor
published: true
date: 2025-12-14T15:50:02.826Z
tags: 
editor: markdown
dateCreated: 2025-12-14T15:50:02.826Z
---

# Problema

El extrusor se afloja, lo que provoca que baile sobre la guía lineal. Si el extrusor tiene juego sobre la guía lineal podemos encontrarnos:

<center>
  <video width="640" height="360" autoplay loop muted>
    <source src="/media/video/extruder-loose.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</center>

<table>
<tr>
  <th>Problema</th>
  <th>Ejemplo</th>
</tr>
<tr>
  <td>
  - **Vibraciones y marcas en la impresión**. El juego puede traducirse en defectos superficiales, como líneas o bandas debido a vibraciones y movimientos imprecisos[^1].
  </td>
  <td>

  ![trouble-banding.webp](/media/images/trouble-banding.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>
  - **Desplazamientos pequeños y capas irregulares**. Aunque el firmware y el slicer estén bien, el cabezal puede moverse ligeramente fuera de posición durante los movimientos rápidos, lo que provocará imprecisiones en dimensiones y bordes.[^2].
  </td>
  <td>

  ![trouble-layer-shift.webp](/media/images/trouble-layer-shift.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>
  - **Pérdida de precisión en movimientos combinados**. En impresoras CoreXY, movimientos diagonales y combinados dependen mucho de que el carruaje esté rígido. Un poco de “juego” puede traducirse en líneas curvas o artefactos.[^3].
  </td>
  <td>

  ![trouble-layer-wobble.webp](/media/images/trouble-layer-wobble.webp =640x){.align-center}
    
  </td>
</tr>
</table>


# Solución

## Útiles necesarios

<table>
<tr>
  <th>Pieza</th>
  <th>Imagen</th>
</tr>
<tr>
  <td>

- **Herramienta de desensamblado del tubo PTFE:** Esta herramienta nos permite extraer el tubo PTFE del extrusor.
  - Está disponible en la tarjeta MicroSD de la impresora.
  - [STL de la herramienta.](/media/stl/official_disassembling_ptfe_tool.zip)

  </td>
  <td>
  
![ptfe-tool.webp](/media/images/ptfe-tool.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>

- **Fijatornillos:** El líquido fijatornillos impedirá que los tornillos vuelvan a aflojarse con facilidad. **Puedes utilizar cualquiera para este propósito siempre que pueda resistir las temperaturas que se pueden llegar a alcanzar dentro de la impresora, cercanas a 70 grados**.
  - [Fijatornillos Weiconlock en Amazon.](https://www.amazon.es/Weicon-30243110/dp/B004Z0MEMI)
  - [Fijatornillos LOOLIFL en Aliexpress.](https://es.aliexpress.com/item/1005009045272509.html)

  </td>
  <td>
  
![threadlock-glue.webp](/media/images/threadlock-glue.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>

- **Pinzas/Alicates:** Esta herramienta nos permite coger los tornillos del carro fácilmente y aplicarles el fijatornillos.
  - [Alicates en Aliexpress.](https://es.aliexpress.com/item/1005009648884992.html)
  - [Juego de pinzas de precisión en Aliexpress.](https://es.aliexpress.com/item/1005009930790317.html)

  </td>
  <td>
  
![pliers-tweezers.webp](/media/images/pliers-tweezers.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>

- **Llave hexagonal H2.0:** Alrededor de la mitad de los tornillos utilizan este cabezal.
  - La impresora trae consigo una llave H2.0.
  - [Juego de llaves Wera en Amazon.](https://www.amazon.es/dp/B009ODV0OE)
  - [Juego de llaves Wera en Aliexpress.](https://es.aliexpress.com/item/1005008153293657.html)
  - [Juego de llaves barato en Aliexpress.](https://es.aliexpress.com/item/1005009357733341.html)

  </td>
  <td>
  
![h2-wrench.webp](/media/images/h2-wrench.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>

- **Llave hexagonal H1.5:** Alrededor de la mitad de los tornillos utilizan este cabezal.
  - La impresora trae consigo una llave H2.0.
  - [Juego de llaves Wera en Amazon.](https://www.amazon.es/dp/B009ODV0OE)
  - [Juego de llaves Wera en Aliexpress.](https://es.aliexpress.com/item/1005008153293657.html)
  - [Juego de llaves barato en Aliexpress.](https://es.aliexpress.com/item/1005009357733341.html)

  </td>
  <td>
  
![h1.5-wrench.webp](/media/images/h1.5-wrench.webp =640x){.align-center}
    
  </td>
</tr>
</table>

## Video Guía


https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/extruder_loose_fix:0

## Guía


### Pasos previos

Debemos sacar el filamento antes de comenzar y desconectar la máquina de la corriente.
  
### Extracción del extrusor

<table>
<tr>
  <th>Paso</th>
  <th>Imagen (Click para ver expandida)</th>
</tr>
<tr>
  <td>

1. Ayudándonos con la herramienta de extracción sacamos el tubo del extrusor.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-2.webp" target="_blank">![change-ptfe-tube-step-2.webp](/media/images/change-ptfe-tube-step-2.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

2. Separamos la tapa frontal imantada tirando de ella un poco hacia arriba y hacia fuera. Tenemos que tener cuidado con el cortador de filamento.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-1.webp" target="_blank">![/media/images/extruder-disasembly-step-1.webp](/media/images/extruder-disasembly-step-1.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

3. Una vez pasado el cortador de filamento retiramos totalmente la tapa frontal teniendo cuidado con el cable del ventilador de capa, que desconectaremos.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-2.webp" target="_blank">![/media/images/extruder-disasembly-step-2.webp](/media/images/extruder-disasembly-step-2.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

4. Quitamos los conectores de los ventiladores del hotend, auxiliares, el nivelador de cama y el hotend.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-1.webp" target="_blank">![/media/images/extruder-disasembly-step-1.webp](/media/images/extruder-disasembly-step-1.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

5. Quitamos los tornillos hexagonales M3*10 de cabeza redondeada con una llave H2.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-4.webp" target="_blank">![/media/images/extruder-disasembly-step-4.webp](/media/images/extruder-disasembly-step-4.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

6. Quitamos los tornillos hexagonales M2*6 de cabeza cilíndrica y los M2.5*6 de cabeza plana con una llave H1.5.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-5.webp" target="_blank">![/media/images/extruder-disasembly-step-5.webp](/media/images/extruder-disasembly-step-5.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

7. Quitamos los tornillos hexagonales M2.5*10 de cabeza plana y el M2.5*8 de cabeza plana con una llave H1.5.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-6.webp" target="_blank">![/media/images/extruder-disasembly-step-6.webp](/media/images/extruder-disasembly-step-6.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

8. Sacamos el extrusor del carro.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-7.webp" target="_blank">![/media/images/extruder-disasembly-step-7.webp](/media/images/extruder-disasembly-step-7.webp =640x){.align-center}</a>
    
  </td>
</tr>
</table>

### Ajuste del carro

<table>
<tr>
  <th>Paso</th>
  <th>Imagen (Click para ver expandida)</th>
</tr>
<tr>
  <td>

6. Quitamos los tornillos hexagonales M3*10 de cabeza plana con una llave H2.

  </td>
  <td>

<a href="/media/images/carriage-tighten-step-1.webp" target="_blank">![carriage-tighten-step-1.webp](/media/images/carriage-tighten-step-1.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

2. Aplicamos fijatornillos al tornillo para evitar que vuelva a aflojarse.

  </td>
  <td>

<a href="/media/images/carriage-tighten-step-2.webp" target="_blank">![carriage-tighten-step-2.webp](/media/images/carriage-tighten-step-2.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

3. Volvemos a colocar el tornillo y lo apretamos.

  </td>
  <td>

<a href="/media/images/carriage-tighten-step-3.webp" target="_blank">![carriage-tighten-step-3.webp](/media/images/carriage-tighten-step-3.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

4. Comprobamos que el carro está correctamente fijado. Deberemos esperar un tiempo a que el fijatornillos esté seco antes de volver a utilizar la impresora (los fijatornillos suelen secar por completo en unas horas, depende del que utilices).

  </td>
  <td>

<a href="/media/images/carriage-tighten-step-4.webp" target="_blank">![carriage-tighten-step-4.webp](/media/images/carriage-tighten-step-4.webp =640x){.align-center}</a>
    
  </td>
</tr>
</table>

### Colocación del extrusor

<table>
<tr>
  <th>Paso</th>
  <th>Imagen (Click para ver expandida)</th>
</tr>
<tr>
  <td>

1. Volvemos a colocar el extrusor en el carro.

  </td>
  <td>

<a href="/media/images/extruder-asembly-step-1.webp" target="_blank">![/media/images/extruder-asembly-step-1.webp](/media/images/extruder-asembly-step-1.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

2. Colocamos los tornillos hexagonales M2.5*10 de cabeza plana y el M2.5*8 de cabeza plana con una llave H1.5.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-6.webp" target="_blank">![/media/images/extruder-disasembly-step-6.webp](/media/images/extruder-disasembly-step-6.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

3. Colocamos los cables en sus respectivos conectores de vuelta.

  </td>
  <td>

<a href="/media/images/extruder-asembly-step-3.webp" target="_blank">![/media/images/extruder-asembly-step-3.webp](/media/images/extruder-asembly-step-3.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

4. Colocamos de nuevo el hotend y ponemos los tornillos hexagonales M3*10 de cabeza redondeada con una llave H2.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-4.webp" target="_blank">![/media/images/extruder-disasembly-step-4.webp](/media/images/extruder-disasembly-step-4.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

6. Conectamos el cable del ventilador frontal y volvemos a colocar el frontal teniendo cuidado con el cortador de filamento.

  </td>
  <td>

<a href="/media/images/extruder-asembly-step-6.webp" target="_blank">![/media/images/extruder-asembly-step-6.webp](/media/images/extruder-asembly-step-6.webp =640x){.align-center}</a>

    
  </td>
</tr>
</table>

[^1]:https://all3dp.com/2/z-banding-z-wobble-fix
[^2]:https://help.prusa3d.com/es/article/desplazamiento-de-capas_2020
[^3]:https://www.reddit.com/r/3Dprinting/comments/1mj5cqa/having_this_strange_issue_with_my_corexy_printer