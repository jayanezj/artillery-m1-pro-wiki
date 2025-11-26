---
title: Cambio de tubo PTFE
description: Guía para la sustitución del tubo PTFE
published: true
date: 2025-11-26T13:37:30.907Z
tags: 
editor: markdown
dateCreated: 2025-11-26T13:37:30.907Z
---

# El tubo PTFE
Este tubo sirve para guiar el filamento desde la bobina hasta el extrusor.

## Piezas necesarias
<table>
<tr>
  <th>Pieza</th>
  <th>Imagen</th>
</tr>
<tr>
  <td>

- **Conector de un sentido:** Este conector previene que el tubo se mueva desde hacia fuera del extrusor.
  - Puedes reutilizar el que tiene el tubo PTFE original.
  - En el [kit de Artillery](https://artillery3d.com/products/ptfe-tube-m1) vienen conectores de repuesto.
  - Puedes conseguir un conector compatible en [Aliexpress (ptfe embedded bowden collect)](https://aliexpress.com/item/1005009105267126.html).

  </td>
  <td>

![ptfe-collector.webp](/media/images/ptfe-collector.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>
  
- **Abrazadera en el manguito de silicona:** Asegura el paso del interior al exterior de la máquina. El diámetro exterior del tubo de silicona con el PTFE dentro ronda los 5.3mm.
  - Puedes reutilizar la que viene instalada de serie.
  - Puedes conseguir un repuesto compatible en [Aliexpress (White Hose Clamps 5~5.5mm)](https://aliexpress.com/item/1005005697827712.html).

  </td>
  <td>

![ptfe-hose-clamp.webp](/media/images/ptfe-hose-clamp.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>

- **Tubo PTFE:** Este tubo guía el filamento desde la bobina hasta el extrusor, por lo que debemos utilizar un tubo con un diámetro interior (2.5~3.0mm) algo superior al que se utiliza en el sistema Bowden (1.9~2.2mm).
  - [Tubo de repuesto suministrado por Artillery.](https://artillery3d.com/products/ptfe-tube-m1)
  - [Tubo de repuesto Capricorn](https://www.captubes.com/shop/#!/Filament-Guide/c/173671010) (diámetro interno 3, diámetro externo 4). Los mejores PTFE del mercado.
  - [Tubo de repuesto Mellow](https://aliexpress.com/item/1005008268651680.html) (diámetro interno 3, diámetro externo 4). Buena calidad contrastada.
  - [Tubo de repuesto Mellow baja fricción estrellado](https://aliexpress.com/item/1005010202912335.html) (diámetro interno 2.2, diámetro externo 4). Aunque tiene diámetro interno específico de sistema Bowden su diseño estrellado proporciona menos fricción, en cualquier caso **no parece recomendable para utilizar con TPU o materiales abrasivos** (el diseño estrellado puede acabar causando más fricción que un diseño convencional con este tipo de filamentos)[^1].

  </td>
  <td>
  
![ptfe-tube.webp](/media/images/ptfe-tube.webp =640x){.align-center}
    
  </td>
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
</table>
  
## Vídeo guía

https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/change_ptfe_tube_guide:f

## Guía

> Artillery proporciona un [tutorial en su Wiki](https://wiki.artillery3d.com/m1/maintenance/add-the-ptfe-connector-assembly) para el cambio de tubo.
{.is-info}

### Pasos previos

Debemos sacar el filamento antes de comenzar y desconectar la máquina de la corriente.
  
### Extracción del tubo PTFE

<table>
<tr>
  <th>Paso</th>
  <th>Imagen (Click para ver expandida)</th>
</tr>
<tr>
  <td>

1. Quitamos la pinza blanca que se asegura en el manguito en el exterior de la impresora.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-1.webp" target="_blank">![change-ptfe-tube-step-1.webp](/media/images/change-ptfe-tube-step-1.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

2. Ayudándonos con la herramienta de extracción sacamos el tubo del extrusor.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-2.webp" target="_blank">![change-ptfe-tube-step-2.webp](/media/images/change-ptfe-tube-step-2.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

3. Desconectamos las pinzas de conexión y quitamos la brida cercana al extrusor (si aún la tenemos).

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-3.webp" target="_blank">![change-ptfe-tube-step-3.webp](/media/images/change-ptfe-tube-step-3.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

4. Quitamos el clip del conector de un sentido y lo sacamos apretando por el lado del extrusor.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-4.webp" target="_blank">![change-ptfe-tube-step-4.webp](/media/images/change-ptfe-tube-step-4.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

5. Sacamos el tubo PTFE desde dentro hacia fuera. Tanto el conector de un sentido que se encuentra justo al final del tubo PTFE en el exterior solo permite la extracción desde el extrusor hacia fuera, así que **no debemos forzar el sentido inverso** (dañaremos el tubo).

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-5.webp" target="_blank">![change-ptfe-tube-step-5.webp](/media/images/change-ptfe-tube-step-5.webp =640x){.align-center}</a>
    
  </td>
</tr>
</table>

### Colocación del tubo PTFE

<table>
<tr>
  <td>

6. Introducimos el conector de un sentido que irá dentro de la impresora. La zona donde se pone el clip azul es la que queda más cercana a la pared de la impresora.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-6.webp" target="_blank">![change-ptfe-tube-step-6.webp](/media/images/change-ptfe-tube-step-6.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

7. Introducimos el tubo PTFE en el extrusor y ajustamos la distancia del tubo moviendo el extrusor por toda la cama.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-7.webp" target="_blank">![change-ptfe-tube-step-7.webp](/media/images/change-ptfe-tube-step-7.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

8. Colocamos las pinzas de conexión y aseguramos con el clip azul el conector de un sentido.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-8.webp" target="_blank">![change-ptfe-tube-step-8.webp](/media/images/change-ptfe-tube-step-8.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

9. Conectamos la pinza blanca en el pasador de silicona. **No debemos apretar mucho la pinza blanca, lo justo para que no se mueva el tubo PTFE.**

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-9.webp" target="_blank">![change-ptfe-tube-step-9.webp](/media/images/change-ptfe-tube-step-9.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

10. Pasamos el tubo PTFE por el conector de un sentido final.**

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-10.webp" target="_blank">![change-ptfe-tube-step-10.webp](/media/images/change-ptfe-tube-step-10.webp =640x){.align-center}</a>
    
  </td>
</tr>
</table>


  
[^1]:https://forum.bambulab.com/t/star-shaped-ptfe-tube/190829