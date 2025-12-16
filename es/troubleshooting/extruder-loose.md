---
title: Extrusor flojo
description: Guía para apretar el extrusor
published: true
date: 2025-12-16T12:05:31.891Z
tags: 
editor: markdown
dateCreated: 2025-12-14T15:50:02.826Z
---

## Problema

El extrusor se afloja, lo que provoca que baile sobre la guía lineal.

<center>
  <video width="640" height="360" autoplay loop muted>
    <source src="/media/video/extruder-loose.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</center>

Si el extrusor tiene juego sobre la guía lineal podemos encontrarnos:

<table width="100%">
<tr>
  <th>Problema</th>
  <th>Ejemplo</th>
</tr>
<tr>
  <td>
    
- **Vibraciones y marcas en la impresión:** El juego puede traducirse en defectos superficiales, como líneas o bandas debido a vibraciones y movimientos imprecisos[^1].
    
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


# Útiles necesarios

<table width="100%">
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

- **Fijatornillos:** El líquido fijatornillos impedirá que los tornillos vuelvan a aflojarse con facilidad. **Puedes utilizar cualquiera para este propósito siempre que pueda resistir las temperaturas que se pueden llegar a alcanzar dentro de la impresora**. También tienes que tener en cuenta que el tiempo de secado final de estos productos suele superar la hora, espera a que seque antes de volver a utilizar la impresora para asegurar una buena fijación.
  - **Weiconlock AN 302-43**: pertenece a la línea de adhesivos anaeróbicos WEICONLOCK, conocida por su fiabilidad en aplicaciones industriales de fijación y sellado. Este fijatornillos de fuerza media y mayor viscosidad evita que los tornillos se aflojen por vibraciones y permite desmontaje con herramientas normales. Su resistencia térmica, con temperaturas de ‑60 °C a +200 °C, lo hace adecuado para impresoras 3D.
    - [Weicon 🇪🇸](https://www.weicon.es/weiconlock-an-302-43-fijacion-de-tornillos-resistencia-media-mayor-viscosidad-con-aprobacion-de-agua-potable/10045974) - [Weicon 🇩🇪](https://www.weicon.de/weiconlock-an-302-43-schraubensicherung-mittelfest-hoeherviskos-mit-trinkwasserzulassung/10016419) - [Weicon 🇫🇷](https://www.weicon.fr/weiconlock-an-302-42-frein-filet-resistance-moyenne-homologue-pour-l-eau-potable/10017324) - [Weicon 🇮🇹](https://www.weicon.it/weiconlock-an-302-43-frenafiletti-media-resistenza-alta-viscosita-con-omologazione-per-acqua-potabile/10046605)
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B004Z0MEMI) - [Amazon 🇩🇪](https://www.amazon.de/dp/B004Z0MEMI) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B004Z0MEMI) - [Amazon 🇮🇹](https://www.amazon.it/dp/B004Z0MEMI) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B004Z0MEMI) - [Amazon 🇺🇸](https://www.amazon.com/dp/B004Z0MEMI)
  - **[Henkel Loctite 243](https://next.henkel-adhesives.com/es/es/products/industrial-adhesives/central-pdp.html/loctite-243/BP000000316211.html)**: De la reconocida marca LOCTITE (Henkel), es un fijador de roscas de fuerza media diseñado para evitar que tornillos y tuercas se aflojen por vibraciones, incluso sobre superficies ligeramente aceitosas como acero inoxidable o aluminio. Su curado anaeróbico permite uniones seguras pero desmontables con herramientas normales, y soporta temperaturas de ‑55 °C a +180 °C, lo que lo hace adecuado para impresoras 3D. La reputación de LOCTITE en adhesivos industriales garantiza una fijación duradera y predecible frente a vibraciones y cambios térmicos.
    - [Amazon 🇪🇸](http://amazon.es/dp/B017L9LGBY) - [Amazon 🇩🇪](https://www.amazon.de/dp/B00B23VAZI) - [Amazon 🇫🇷](http://amazon.fr/dp/B017L9LHLI) - [Amazon 🇮🇹](https://www.amazon.it/dp/B017L9LHLI) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B071RCNVFJ) - [Amazon 🇺🇸](https://www.amazon.com/dp/B009I2UC3Q)
  - **LOOLIFL 243**: Adhesivo fijador de roscas anaeróbico de resistencia media diseñado para evitar que tornillos y tuercas se aflojen por vibraciones o choque mecánico y al mismo tiempo sellar la unión. A diferencia de marcas industriales consolidadas, LOOLIFL suele ser un producto genérico/sin marca fuerte que se encuentra a muy bajo precio, con formulación básica similar a otros fijadores 243, pero con calidad y consistencia que pueden variar según el lote y proveedor, y sin el mismo respaldo técnico o certificaciones que productos de fabricantes reconocidos.
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005009045272509.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005009045272509.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005009045272509.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005009045272509.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005009045272509.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256808858957757.html)

  </td>
  <td>
  
![threadlock-glue.webp](/media/images/threadlock-glue.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>

- **Pinzas/Alicates:** Esta herramienta nos permite coger los tornillos del carro fácilmente y aplicarles el fijatornillos.
  - **[XURON 170-II](https://xuron.com/blog/170-ii-series-micro-shear-flush-cutters-in-four-configurations/)**: De la reconocida marca estadounidense Xuron, es un alicate de corte de precisión tipo flush cutter diseñado para cortar filamento y restos plásticos de impresoras 3D con cortes limpios y sin rebabas. Fabricado en acero de alta calidad con mango ergonómico y muelle de retorno, ofrece durabilidad y control superiores a los alicates genéricos, siendo ideal para trabajos de detalle en impresión 3D y modelismo.
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B002N1OXKC) - [Amazon 🇩🇪](http://amazon.de/dp/B002N1OXKC) - [Amazon 🇫🇷](http://amazon.fr/dp/B002N1OXKC) - [Amazon 🇮🇹](https://www.amazon.it/dp/B002N1OXKC) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B002N1OXKC) - [Amazon 🇺🇸](https://www.amazon.com/dp/B000IBSFAI)

  - **iViTC 170**: Es un alicate/cortador lateral tipo “Model 170” (similar a los flush cutters) que se vende mucho en sitios como AliExpress y está diseñado para cortar cables, filamento plástico o pequeñas piezas con un corte limpio y preciso gracias a su hoja afilada. Aunque no tiene el respaldo de una marca técnica conocida como Xuron o Hakko, es una herramienta económica y funcional para tareas en impresoras 3D y comparte la forma y función de los cutters de tipo 170 que se usan habitualmente.
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005009648884992.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005009648884992.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005009648884992.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005009648884992.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005009648884992.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/1005009648884992.html)
  - **iFixit Precision Tweezers Set**: Es un juego de pinzas de precisión de la reconocida marca iFixit, especializada en herramientas para reparación y mantenimiento de electrónica y dispositivos delicados. Fabricadas en acero inoxidable de alta calidad, las pinzas ofrecen punta fina y agarre preciso, ideales para manipular filamento, retirar restos de soporte o ajustar piezas pequeñas en impresoras 3D. Su durabilidad y acabado profesional las hacen mucho más fiables que pinzas genéricas, convirtiéndolas en una herramienta esencial para trabajos de detalle en impresión 3D y modelismo.

    - [IFixit 🇪🇺](https://www.ifixit.com/en-eu/products/precision-tweezers-set) - [IFixit 🇩🇪](https://www.ifixit.com/de-de/products/precision-tweezers-set) - [IFixit 🇫🇷](https://www.ifixit.com/fr-fr/products/precision-tweezers-set) - [IFixit 🇮🇹](https://www.ifixit.com/it-it/products/precision-tweezers-set) - [IFixit 🇬🇧](https://www.ifixit.com/en-gb/products/precision-tweezers-set) - [IFixit 🇺🇸](https://www.ifixit.com/products/precision-tweezers-set)
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B079K874CQ) - [Amazon 🇩🇪](http://amazon.de/dp/B079K874CQ) - [Amazon 🇫🇷](http://amazon.fr/dp/B079K874CQ) - [Amazon 🇮🇹](https://www.amazon.it/dp/B079K874CQ) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B079K874CQ) - [Amazon 🇺🇸](https://www.amazon.com/dp/B079K874CQ)


  - **Precision ESD anti-static tweezers set**: Es un kit genérico de pinzas de precisión antiestáticas en acero inoxidable. Las herramientas del set son de acero inoxidable con acabado anti‑estático/ESD y no magnético, lo que ayuda a reducir el riesgo de descargas electrostáticas cuando se manipulan componentes sensibles, aunque al ser genéricas no hay certificaciones oficiales claras ni marca reconocida detrás.
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005009930790317.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005009930790317.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005009930790317.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005009930790317.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005009930790317.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256809744475565.html)

  </td>
  <td>
  
![pliers-tweezers.webp](/media/images/pliers-tweezers.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>

- **Llave hexagonal H2.0:** Alrededor de la mitad de los tornillos utilizan este cabezal.
  - La impresora trae consigo una llave H2.0.
  - **[Wera 05073593001](https://www.weraspain.com/herramientas/950-9-hex-plus-multicolour-1-sb-juego-de-llaves-acodadas-metricas-blacklaser)**: Es un juego de 9 llaves hexagonales métricas en forma de L de la marca alemana Wera, reconocida por producir herramientas manuales de alta calidad para profesionales y aficionados exigentes. Este set utiliza la tecnología Hex‑Plus, que aumenta la superficie de contacto con los tornillos para reducir el desgaste y facilitar la aplicación de par sin dañar las cabezas, y cuenta con mangos codificados por color y tratamiento BlackLaser para una cómoda identificación y gran resistencia a la corrosión. Este tipo de llaves es ideal para montar y ajustar componentes como extrusores, marcos o piezas impresas con tornillos hexagonales, ofreciendo más precisión y durabilidad que llaves allen genéricas, lo que mejora la experiencia de mantenimiento y ajuste de la impresora.
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B009ODV0OE) - [Amazon 🇩🇪](https://www.amazon.de/dp/B009ODV0OE) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B009ODV0OE) - [Amazon 🇮🇹](https://www.amazon.it/dp/B009ODV0OE) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B009ODV0OE) - [Amazon 🇺🇸](https://www.amazon.com/dp/B009ODV0OE)
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005008153293657.html)
    - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256807966978905.html)
    
  - **RIDERACE set 9 piezas**: es un juego de llaves hexagonales tipo L de la marca Riderace, un fabricante que suele aparecer en herramientas económicas para bicicletas y reparaciones básicas, generalmente con acero CR‑V o S2 y acabados coloreados para facilitar la identificación de tamaños. Aunque Riderace no tiene la misma reputación o respaldo técnico que marcas especializadas de herramientas como Wera o Park Tool, muchos usuarios encuentran estas llaves funcionales y suficientes para tareas de mantenimiento, ofreciendo versatilidad y portabilidad a bajo coste.
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005008298259316.html)
    - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256808111944564.html)

  </td>
  <td>
  
![h2-wrench.webp](/media/images/h2-wrench.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>

- **Llave hexagonal H1.5:** Alrededor de la mitad de los tornillos utilizan este cabezal.
  - La impresora trae consigo una llave H1.5.
  - **[Wera 05073593001](https://www.weraspain.com/herramientas/950-9-hex-plus-multicolour-1-sb-juego-de-llaves-acodadas-metricas-blacklaser)**: Es un juego de 9 llaves hexagonales métricas en forma de L de la marca alemana Wera, reconocida por producir herramientas manuales de alta calidad para profesionales y aficionados exigentes. Este set utiliza la tecnología Hex‑Plus, que aumenta la superficie de contacto con los tornillos para reducir el desgaste y facilitar la aplicación de par sin dañar las cabezas, y cuenta con mangos codificados por color y tratamiento BlackLaser para una cómoda identificación y gran resistencia a la corrosión. Este tipo de llaves es ideal para montar y ajustar componentes como extrusores, marcos o piezas impresas con tornillos hexagonales, ofreciendo más precisión y durabilidad que llaves allen genéricas, lo que mejora la experiencia de mantenimiento y ajuste de la impresora.
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B009ODV0OE) - [Amazon 🇩🇪](https://www.amazon.de/dp/B009ODV0OE) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B009ODV0OE) - [Amazon 🇮🇹](https://www.amazon.it/dp/B009ODV0OE) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B009ODV0OE) - [Amazon 🇺🇸](https://www.amazon.com/dp/B009ODV0OE)
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256807966978905.html)
    
  - **RIDERACE set 9 piezas**: es un juego de llaves hexagonales tipo L de la marca Riderace, un fabricante que suele aparecer en herramientas económicas para bicicletas y reparaciones básicas, generalmente con acero CR‑V o S2 y acabados coloreados para facilitar la identificación de tamaños. Aunque Riderace no tiene la misma reputación o respaldo técnico que marcas especializadas de herramientas como Wera o Park Tool, muchos usuarios encuentran estas llaves funcionales y suficientes para tareas de mantenimiento, ofreciendo versatilidad y portabilidad a bajo coste.
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256808111944564.html)

  </td>
  <td>
  
![h1.5-wrench.webp](/media/images/h1.5-wrench.webp =640x){.align-center}
    
  </td>
</tr>
</table>

# Video Guía


https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/extruder_loose_fix:0

# Guía


## Pasos previos

Debemos sacar el filamento antes de comenzar y desconectar la máquina de la corriente.
  
## Extracción del extrusor

<table width="100%">
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

## Ajuste del carro

<table width="100%">
<tr>
  <th>Paso</th>
  <th>Imagen (Click para ver expandida)</th>
</tr>
<tr>
  <td>

1. Quitamos los tornillos hexagonales M3*10 de cabeza plana con una llave H2.

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

## Colocación del extrusor

<table width="100%">
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