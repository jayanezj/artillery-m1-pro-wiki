---
title: M1PRO S1 - Extrusor Optimizado
description: Guía de instalación del extrusor optimizado para M1 PRO S1
published: true
date: 2025-12-16T16:26:35.455Z
tags: 
editor: markdown
dateCreated: 2025-12-16T16:25:20.814Z
---

# Cambio respecto a V1

<a href="/media/images/extruder-housing-maintenance-step-2.webp" target="_blank">![/media/images/extruder-housing-maintenance-step-2.webp](/media/images/extruder-housing-maintenance-step-2.webp =640x){.align-center}</a>

## Motivo de la mejora

- El acoplamiento del engranaje del extrusor original estaba demasiado apretado por el resorte original, aumentando la probabilidad de que el filamento se enredara en los engranajes.
- Ocasionalmente podrían producirse atascos de alimentación durante la extrusión.

## Solución

- Optimizar el resorte y los parámetros de montaje del resorte. Las pruebas muestran que los incidentes de enredos del filamento son ahora raros durante la impresión normal.
- Reemplazar el conjunto de la carcasa superior del extrusor para asegurar un alimentado del filamento más suave.

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

- **Isopropanol/limpiacontactos:** Para asegurar la correcta limpieza de los componentes sin dejar residuos ni dañar los plásticos ni metales. **Puedes utilizar cualquier limpiador siempre que se evapore rápidamente y no deje residuos**.
  - **[EQM - ECO-301](https://www.ecosolucionesquimicas.es/producto/alcohol-isopropilico-eqm-999-pureza/)**: Es un alcohol isopropílico de alta pureza (99,9%) de la marca EQM Soluciones Químicas, un proveedor español de productos químicos técnicos utilizados para limpieza especializada de superficies delicadas. Su fórmula sin aditivos se evapora rápidamente sin dejar residuos, lo que lo hace adecuado para limpiar suciedad, grasa y residuos de filamento o adhesivo antes de ajustar o lubricar piezas, facilitando un funcionamiento más suave y reduciendo la acumulación de contaminantes que pueden afectar al rendimiento sin dañar metales o plásticos. 
    - [Eco 🇪🇸](https://www.ecosolucionesquimicas.es/fr/producto/alcohol-isopropilico-eqm-999-pureza/) - [Eco 🇫🇷](https://www.ecosolucionesquimicas.es/fr/producto/alcohol-isopropilico-eqm-999-pureza) - [Eco 🇬🇧](https://www.ecosolucionesquimicas.es/en/producto/alcohol-isopropilico-eqm-999-pureza/)
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B07SH9FY7G) - [Amazon 🇩🇪](https://www.amazon.de/dp/B07SH9FY7G) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B07SH9FY7G) - [Amazon 🇮🇹](https://www.amazon.it/dp/B07SH9FY7G) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B07SH9FY7G) - [Amazon 🇺🇸](https://www.amazon.com/dp/B00DT52Y98)

  - **[Sonax - 04603000](https://www.sonax.com/es/productos-de-cuidado/limpiador-para-la-electronicacontactos-con-easyspray-400-ml-04603000)**: Es un spray limpiacontactos y para componentes electrónicos de la marca alemana SONAX, reconocida por sus productos de limpieza y mantenimiento técnicos de alta calidad “made in Germany”. Este limpiador está formulado para eliminar suciedad, aceite, residuos de silicona y oxidación de contactos eléctricos, conectores y otros componentes sin dejar residuos, gracias a su evaporación extremadamente rápida y compatibilidad con plásticos y metales. Es útil para limpiar engranajes, extrusores y contactos eléctricos antes de mantenimiento o ajuste, mejorando el flujo de corriente y el funcionamiento suave de piezas mecánicas y electrónicas; su sistema EasySpray permite una aplicación dirigida incluso en espacios reducidos.
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B077GSVN4C) - [Amazon 🇩🇪](https://www.amazon.de/dp/B077GSVN4C) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B077GSVN4C) - [Amazon 🇮🇹](https://www.amazon.it/dp/B077GSVN4C)

  - **[WD-40 Specialist Limpiador de Contactos](https://wd40.es/producto/wd-40-specialist-limpiador-de-contactos/)**: Es un spray limpiacontactos dieléctrico de la gama Specialist de WD-40, una marca muy conocida internacionalmente por sus productos de mantenimiento técnico y soluciones de limpieza y lubricación. Este limpiador está formulado para eliminar aceite, polvo, suciedad, condensación y residuos de fundente de componentes eléctricos y electrónicos sensibles sin dejar residuos, ya que se evapora rápidamente y es no conductor. Es útil para limpiar engranajes, conectores, contactos eléctricos y partes del extrusor antes de mantenimiento o ajustes, ayudando a restaurar un buen contacto y funcionamiento suave de piezas mecánicas y electrónicas; su aplicador también permite llegar a espacios reducidos de forma precisa sin dañar plásticos o metales.
    - [Amazon 🇪🇸](http://amazon.es/dp/B01N4554M2) - [Amazon 🇩🇪](https://www.amazon.de/dp/B0987C5CMR) - [Amazon 🇫🇷](http://amazon.fr/dp/B01MTD0594) - [Amazon 🇮🇹](https://www.amazon.it/dp/B00GTV24JE) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B00KPUBO2S) - [Amazon 🇺🇸](https://www.amazon.com/dp/B00AF0OFVU)

  </td>
  <td>
  
![isopropanol-contact-cleaner-tool.webp](/media/images/isopropanol-contact-cleaner-tool.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>

- **Lubricante líquido:** Para asegurar un funcionamiento suave de los engranajes del extrusor, evitar chirridos y aumentar la vida útil de los componentes internos debemos lubricar los engranajes y rodamientos. **Puedes utilizar cualquier lubricante siempre que sea de un alto grado de deslizamiento y compatible con los plásticos y metales de los componentes del extrusor**.
  - **[Superlube 51004](https://www.super-lube.com/wp-content/uploads/2025/06/Technical_Data_Sheet_Multi_Use_Oil_w_Syncolon-Spanish.pdf)**: Es un aceite sintético de alta calidad de la marca Super Lube®, un fabricante especializado en lubricantes industriales y de mantenimiento con partículas de PTFE que reducen la fricción, el desgaste, el óxido y la corrosión en componentes móviles. Su fórmula de base sintética con PTFE se adhiere bien a superficies metálicas y plásticas y ofrece una amplia compatibilidad y un rango de temperatura de funcionamiento de aproximadamente –43 °C a +232 °C, lo que permite su uso seguro para lubricar varillas, guías lineales, rodamientos y otros mecanismos móviles, mejorando el deslizamiento y reduciendo el desgaste con respecto a aceites genéricos, y es valorado por muchos usuarios por su rendimiento estable y durabilidad en mantenimiento de impresoras 3D. 
    - [SuperLube 🇪🇺](https://super-lube.eu/en/oils/44-51004-multi-use-synthetic-oil-with-ptfe-118-ml-0082353510047.html) - [SuperLube 🇩🇪](https://super-lube.eu/de/oele/44-51004-super-lube-synthetisches-mehrzweckoel-mit-ptfe-118-ml-0082353510047.html) - [SuperLube 🇫🇷](https://super-lube.eu/fr/huiles/44-51004-huile-synthetique-polyvalente-avec-ptfe-118-ml-0082353510047.html)
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005009944982308.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005009944982308.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005009944982308.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005009944982308.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256808495252837.html)
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B000UKUHXK) - [Amazon 🇩🇪](https://www.amazon.de/dp/B000UKUHXK) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B000UKUHXK) - [Amazon 🇮🇹](https://www.amazon.it/dp/B000UKUHXK)
    - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B000UKUHXK) - [Amazon 🇺🇸](https://www.amazon.com/dp/B000UKUHXK)

  - **Sikezhan 3D Printer Lubricant**: Es una formulación promocionada en tiendas online con afirmaciones sobre lubricación de película seca con disulfuro de molibdeno (MoS₂) y reducción de ruido y desgaste, pero **no se encuentran referencias independientes sobre la marca ni documentación técnica verificable que respalde esas afirmaciones.** Suele ser preferible usar lubricantes con especificaciones claras y respaldo de fabricantes reconocidos o recomendados por la comunidad, ya que los productos genéricos sin datos técnicos pueden ofrecer rendimiento y compatibilidad impredecibles con las piezas y materiales de una impresora 3D. Es una alternativa barata a Super Lube que parece funcionar bien según los comentarios de los compradores.
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005010363007211.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005010332562884.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005010363007211.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005010363007211.html) - [Aliexpress 🇬🇧](https://www.aliexpress.us/item/3256810176692459.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256810176692459.html)

  - **[Sonax - 03483000](https://www.sonax.com/es/productos-de-cuidado/silicona-en-spray-con-easyspray-400-ml-03483000)**: es un lubricante de silicona en aerosol de la marca alemana SONAX, reconocida internacionalmente por sus productos de limpieza, cuidado y mantenimiento automotriz con buena reputación de calidad “made in Germany” y presencia amplia en talleres y uso doméstico. Este spray está formulado para lubricar, proteger y cuidar piezas de goma, plástico y metal, dejando una película lubricante duradera y repelente al agua que elimina chirridos y facilita el movimiento de partes móviles. La documentación confirma que es seguro para plásticos y metales, lo que indica que puede aplicarse con precaución en partes impresas en 3D de plástico o estructuras de acero y aluminio sin degradar estas superficies. Este tipo de spray es útil para lubricar componentes mecánicos como guías, bisagras o partes móviles no sometidas a cargas altas, reduciendo rozamientos y ruidos; sin embargo, en componentes de precisión como husillos, rodamientos o engranajes sujetos a cargas y movimiento continuo, muchos usuarios y técnicos prefieren grasas específicas de mayor adherencia (por ejemplo con PTFE o cerámicas) para asegurar una lubricación más duradera y controlada.
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B072BZZ41R) - [Amazon 🇩🇪](https://www.amazon.de/dp/B072BZZ41R) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B072BZZ41R) - [Amazon 🇮🇹](https://www.amazon.it/dp/B072BZZ41R)

  - **[WD-40 Specialist Lubricante de Silicona](https://wd40.es/producto/wd-40-specialist-lubricante-de-silicona/)**: Es un spray lubricante de silicona de la línea Specialist de WD‑40, una marca con una trayectoria internacional sólida en productos de mantenimiento, protección y lubricación técnica para múltiples aplicaciones. Su fórmula basada en silicona está diseñada para lubricar, impermeabilizar y proteger superficies metálicas y no metálicas —incluyendo plástico y caucho— sin dejar residuos pegajosos, formando una película clara que no atrae suciedad y ayuda a mantener mecanismos móviles suaves y protegidos. La documentación confirma que es seguro para plásticos y metales, lo que indica que puede aplicarse con precaución en partes impresas en 3D de plástico o estructuras de acero y aluminio sin degradar estas superficies. Este tipo de spray es útil para lubricar componentes mecánicos como guías, bisagras o partes móviles no sometidas a cargas altas, reduciendo rozamientos y ruidos; sin embargo, en componentes de precisión como husillos, rodamientos o engranajes sujetos a cargas y movimiento continuo, muchos usuarios y técnicos prefieren grasas específicas de mayor adherencia (por ejemplo con PTFE o cerámicas) para asegurar una lubricación más duradera y controlada.
wd40.com
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B01N56KX44) - [Amazon 🇩🇪](https://www.amazon.de/dp/B0913B5NBF) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B0081SMLR8) - [Amazon 🇮🇹](https://www.amazon.it/dp/B00GTV25D4) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B006UCNI38) - [Amazon 🇺🇸](https://www.amazon.com/dp/B00631GSSI)

  </td>
  <td>
  
![oil-lubricant-tool.webp](/media/images/oil-lubricant-tool.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>

- **Pinzas/Alicates:** Esta herramienta nos permite coger los tornillos del extrusor fácilmente.
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
<tr>
  <td>

- **Destornillador Phillips PH0:** Los tornillos de la placa principal del extrusor son de este tipo.
  - La impresora trae consigo un destornillador PH0.
  - El kit de actualización a Artillery M1 Pro S1 trae consigo un destornillador PH0.
  - **iFixit Minnow Precision Bit Set**: Es un kit compacto de puntas de destornillador de precisión de la reconocida marca iFixit, especializada en herramientas para electrónica y reparación delicada. Incluye varias puntas Phillips en tamaños pequeños (000, 0 y 1) fabricadas en acero S2 resistente, ideales para atornillar y desatornillar componentes mecánicos de impresoras 3D como engranajes, extrusores o marcos sin dañar las cabezas de los tornillos, ofreciendo precisión y durabilidad en mantenimiento y ajustes finos.

    - [IFixit 🇪🇺](https://www.ifixit.com/en-eu/products/minnow-driver-kit) - [IFixit 🇩🇪](https://www.ifixit.com/de-de/products/minnow-driver-kit) - [IFixit 🇫🇷](https://www.ifixit.com/fr-fr/products/minnow-driver-kit) - [IFixit 🇮🇹](https://www.ifixit.com/it-it/products/minnow-driver-kit) - [IFixit 🇬🇧](https://www.ifixit.com/en-gb/products/minnow-driver-kit) - [IFixit 🇺🇸](https://www.ifixit.com/products/minnow-driver-kit)
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B08NWJH6TD) - [Amazon 🇩🇪](http://amazon.de/dp/B08NWJH6TD) - [Amazon 🇫🇷](http://amazon.fr/dp/B08NWJH6TD) - [Amazon 🇮🇹](https://www.amazon.it/dp/B08NWJH6TD) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B08NWJH6TD) - [Amazon 🇺🇸](https://www.amazon.com/dp/B08NWJH6TD)

  </td>
  <td>
  
![ph0-screwdriver.webp](/media/images/ph0-screwdriver.webp =640x){.align-center}
    
  </td>
</tr>
</table>

# Útiles opcionales

<table width="100%">
<tr>
  <th>Pieza</th>
  <th>Imagen</th>
</tr>
<tr>
  <td colspan="2">
    
 - **Enlaces a las tiendas oficiales de Artillery con todos los respuestos en venta para M1 Pro**.
   - [Artillery 🇪🇺](https://eu.artillery3d.com/collections/spare-parts-for-m1-series?filter=m1+series)
   - [Artillery 🇺🇸](https://www.artillery3d.com/collections/spare-parts-for-m1-series)
   - [Aliexpress principal](https://artillery.aliexpress.com/store/1100983046/pages/all-items.html?sortType=bestmatch_sort&SearchText=m1&shop_sortType=bestmatch_sort)
   - [Aliexpress secundaria](https://aliexpress.com/store/1101459703/pages/all-items.html?sortType=bestmatch_sort&SearchText=m1&shop_sortType=bestmatch_sort)
    
  </td>
</tr>
<tr>
  <td>

  - **Juego de engranajes**: Es un kit de reemplazo para los engranajes del extrusor. Artillery diseñó estos engranajes para que, frente a un atasco importante, sean los engranajes los que se rompan y no el motor (que es un repuesto más caro). Un engranaje con dientes rotos provocará pérdida de pasos, lo que será un problema en nuestras impresiones.
    - [Artillery 🇪🇺](https://eu.artillery3d.com/products/drive-idler-gear-set-extruder-m1) - [Artillery 🇺🇸](https://www.artillery3d.com/products/drive-idler-gear-set-extruder-m1)
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005010180596582.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005010180596582.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005010180596582.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005010180596582.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005010180596582.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256809994281830.html)
    - [Aliexpress alternativo 🇪🇸](http://es.aliexpress.com/item/1005010185029344.html) - [Aliexpress alternativo 🇩🇪](https://de.aliexpress.com/item/1005010185029344.html) - [Aliexpress alternativo 🇫🇷](https://fr.aliexpress.com/item/1005010185029344.html) - [Aliexpress alternativo 🇮🇹](https://it.aliexpress.com/item/1005010185029344.html) - [Aliexpress alternativo 🇬🇧](https://www.aliexpress.com/item/1005010185029344.html) - [Aliexpress alternativo 🇺🇸](https://www.aliexpress.us/item/3256809998714592.html)

  </td>
  <td>
  
![extruder-housing-maintenance-step-1.webp](/media/images/extruder-housing-maintenance-step-1.webp =640x){.align-center}
    
  </td>
</tr>
</table>

# Video Guía


https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/extruder_v2_upgrade:3

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

## Desensamblado de la carcasa del extrusor

<table width="100%">
<tr>
  <th>Paso</th>
  <th>Imagen (Click para ver expandida)</th>
</tr>
<tr>
  <td>

1. Desconectamos el terminal del motor del extrusor.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-1.webp" target="_blank">![extruder-housing-disasembly-step-1.webp](/media/images/extruder-housing-disasembly-step-1.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

2. Quitamos los tres tornillos M2*5 Phillips PH1 de cabeza plana.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-2.webp" target="_blank">![extruder-housing-disasembly-step-2.webp](/media/images/extruder-housing-disasembly-step-2.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

3.Desconectamos los terminales de la cuchilla de filamento. Dado que la carcasa V2 tra un nuevo cable junto con las placas electrónicas y la propia cuchilla, podemos optar por desconectar el cable de la placa principal (recomendable porque el cable nuevo está pegado en las placas de la carcasa V2) o bien mantener el cable antiguo y conectarlo a las placas electrónicas de la carcasa V2 (el cable es compatible).

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-3.webp" target="_blank">![extruder-housing-disasembly-step-3.webp](/media/images/extruder-housing-disasembly-step-3.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

4. Quitamos los cuatro tornillos hexagonales M2.5*8 de cabeza plana con una llave H1.5.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-4.webp" target="_blank">![extruder-housing-disasembly-step-4.webp](/media/images/extruder-housing-disasembly-step-4.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

5. Quitamos el tornillo hexagonal M3*8 de de cabeza avellanada interior con una llave H1.5.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-5.webp" target="_blank">![extruder-housing-disasembly-step-5.webp](/media/images/extruder-housing-disasembly-step-5.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

6. Abrimos la carcasa tirando de cada lado de forma opuesta. **Es muy posible que el soporte de retención del resorte salga despedido al abrir la carcasa**.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-6.webp" target="_blank">![extruder-housing-disasembly-step-6.webp](/media/images/extruder-housing-disasembly-step-6.webp =640x){.align-center}</a>
    
  </td>
</tr>
</table>

## Sustitución y mantenimiento de la carcasa del extrusor

<table width="100%">
<tr>
  <th>Paso</th>
  <th>Imagen (Click para ver expandida)</th>
</tr>
<tr>
  <td>

1. Lo primero que haremos es comprobar el estado general de los engranajes. Si detectamos problemas Artillery suministra un kit para reemplazarlo, indicado en la sección de útiles.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-1.webp" target="_blank">![extruder-housing-maintenance-step-1.webp](/media/images/extruder-housing-maintenance-step-1.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

2. Recuperamos el rodamiento de la carcasa V1 si se ha quedado fijado en ella (lo que porobablemente ocurra), o bien cogemos uno del kit de reemplazo.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-3.webp" target="_blank">![extruder-housing-maintenance-step-3.webp](/media/images/extruder-housing-maintenance-step-3.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

3. Comprobamos con precaución el estado de la rueda dentada del engranaje que va con el motor. Artillery diseñó este engranaje en plástico para que un atasco no queme el motor (que es un componente más caro de reemplazar que el engranaje), por lo que los dientes pueden estar dañados si hemos tenido atascos.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-4.webp" target="_blank">![extruder-housing-maintenance-step-4.webp](/media/images/extruder-housing-maintenance-step-4.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

4. Limpiamos toda la suciedad del engranaje con isopropanol o limpiacontactos.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-5.webp" target="_blank">![extruder-housing-maintenance-step-5.webp](/media/images/extruder-housing-maintenance-step-5.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

5. Lubricamos el rodamiento para asegurar un movimiento fluído y limpiamos el exceso de lubricante.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-6.webp" target="_blank">![extruder-housing-maintenance-step-6.webp](/media/images/extruder-housing-maintenance-step-6.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

6. Colocamos el rodamiento limpio y lubricado en la carcasa v2.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-7.webp" target="_blank">![extruder-housing-maintenance-step-7.webp](/media/images/extruder-housing-maintenance-step-7.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

7. Comprobamos que el rodamiento queda correctamente asentado y fijo en la carcasa v2 pero su parte interior gira libremente.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-8.webp" target="_blank">![extruder-housing-maintenance-step-8.webp](/media/images/extruder-housing-maintenance-step-8.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

8. Limpiamos toda la suciedad de la carcasa del motor y su engranaje con isopropanol o limpiacontactos.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-9.webp" target="_blank">![extruder-housing-maintenance-step-9.webp](/media/images/extruder-housing-maintenance-step-9.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

9. Lubricamos el rodamiento de la carcasa del para asegurar un movimiento fluído y limpiamos el exceso de lubricante. Puedes retirar primero el rodamiento de la carcasa si quieres limpiarlo y engrasarlo mejor. Recuerda después comprobar que se mantiene fijo en su posición y que gira libremente por la parte interior.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-10.webp" target="_blank">![extruder-housing-maintenance-step-10.webp](/media/images/extruder-housing-maintenance-step-10.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

10. Colocamos el engranaje en la carcasa del motor.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-11.webp" target="_blank">![extruder-housing-maintenance-step-11.webp](/media/images/extruder-housing-maintenance-step-11.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

11. Comprobamos que el engranaje gira correctamente con el motor y no se pierden pasos.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-12.webp" target="_blank">![extruder-housing-maintenance-step-12.webp](/media/images/extruder-housing-maintenance-step-12.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

12. Volvemos a comprobar que el engranaje está en buen estado de salud. **Desmontar este engranaje es un proceso tedioso, así que es mejor asegurarnos varias veces de que todo está en orden a perder pasos posteriormente por un engranaje dañado.**

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-13.webp" target="_blank">![extruder-housing-maintenance-step-13.webp](/media/images/extruder-housing-maintenance-step-13.webp =640x){.align-center}</a>
    
  </td>
</tr>
</table>

## Ensamblado de la carcasa del extrusor

<table width="100%">
<tr>
  <th>Paso</th>
  <th>Imagen (Click para ver expandida)</th>
</tr>
<tr>
  <td>

1. Por un lado tenemos la carcasa V2 con el rodamiento colocado únicamente (Si tienes la barra metálica que sirve de eje para la pinza en este lado sácala para llevarla al otro lado).

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-1.webp" target="_blank">![extruder-housing-asembly-step-1.webp](/media/images/extruder-housing-asembly-step-1.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

2. Por otro lado tenemos la carcasa con el motor, la barra metálica y el rodamiento.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-2.webp" target="_blank">![extruder-housing-asembly-step-2.webp](/media/images/extruder-housing-asembly-step-2.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

3.Colocamos el engranaje en el lado del extrusor (si lo hemos quitado por algún motivo después del mantenimiento y comprobaciones).

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-3.webp" target="_blank">![extruder-housing-asembly-step-3.webp](/media/images/extruder-housing-asembly-step-3.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

4. Introducimos la pinza del engranaje del extrusor a través de su barra de eje.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-4.webp" target="_blank">![extruder-housing-asembly-step-4.webp](/media/images/extruder-housing-asembly-step-4.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

5. Comprobamos que los engranajes por los que pasará el filamento giran correctamente.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-5.webp" target="_blank">![extruder-housing-asembly-step-5.webp](/media/images/extruder-housing-asembly-step-5.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

6. Colocamos el resorte v2 con su retenedor v2 entre la carcasa del motor y la pinza. **Si tienes problemas** para colocarlo puedes sacar la pinza de la barra que actua como eje, colocar primero el lado de la pinza donde se encuentra el resorte contra la carcasa del motor, poner la barra metálica directamente sobre la pinza y después acomodar la barra en la carcasa. **En la [vídeo guía se detalla este procedimiento](https://odysee.com/@ArtilleryM1ProCommunity:6/extruder_v2_upgrade:3?r=Fj5J5CAzCxrWwoBoZxuvw3RdPZar3veY&t=515)**.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-6.webp" target="_blank">![extruder-housing-asembly-step-6.webp](/media/images/extruder-housing-asembly-step-6.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

7. Comprobamos la correcta alineación de los engranajes de filamento con el resorte ya puesto.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-7.webp" target="_blank">![extruder-housing-asembly-step-7.webp](/media/images/extruder-housing-asembly-step-7.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

8. Pasamos el cableado del motor por el hueco en la carcasa v2.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-8.webp" target="_blank">![extruder-housing-asembly-step-8.webp](/media/images/extruder-housing-asembly-step-8.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

9. Cerramos la carcasa prestando atención a que todo siga en su sitio, especialmente el resorte de la pinza de extrusión de filamento.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-9.webp" target="_blank">![extruder-housing-asembly-step-9.webp](/media/images/extruder-housing-asembly-step-9.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

10. Colocamos el tornillo hexagonal M3*8 de de cabeza avellanada interior con una llave H1.5.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-5.webp" target="_blank">![extruder-housing-disasembly-step-5.webp](/media/images/extruder-housing-disasembly-step-5.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

11. Si optamos por utilizar el cableado nuevo del cortador de filamento que viene con la carcasa v2 debemos retirar el cableado antiguo. Para ello, sacamos por la ranura en la placa los cables con cuidado de no dañarlos (si tienes dificultades sacándolos puedes separarlos individualmente para hacerlo con más facilidad) y desconectamos el terminal (que seguramente venga con una pasta de fijación) de la placa.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-10.webp" target="_blank">![extruder-housing-asembly-step-10.webp](/media/images/extruder-housing-asembly-step-10.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

12. Pasamos el nuevo cableado a través de la ranura de la placa. Nuevamente, si tienes dificultades para pasarlos, puedes dividir la manguera de cableado para pasarlos de forma individual, lo importante es no dañar la manguera con la placa. Conectamos el terminal a la placa.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-11.webp" target="_blank">![extruder-housing-asembly-step-11.webp](/media/images/extruder-housing-asembly-step-11.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

13. Conectamos el terminal a la placa.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-12.webp" target="_blank">![extruder-housing-asembly-step-12.webp](/media/images/extruder-housing-asembly-step-12.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

14. Colocamos los cuatro tornillos hexagonales M2.5*8 de cabeza plana con una llave H1.5.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-4.webp" target="_blank">![extruder-housing-disasembly-step-4.webp](/media/images/extruder-housing-disasembly-step-4.webp =640x){.align-center}</a>
    
  </td>
</tr>  
<tr>
  <td>

15. Colocamos los tres tornillos M2*5 Phillips PH1 de cabeza plana.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-2.webp" target="_blank">![extruder-housing-disasembly-step-2.webp](/media/images/extruder-housing-disasembly-step-2.webp =640x){.align-center}</a>
    
  </td>
</tr>
<tr>
  <td>

16. Conectamos el terminal del motor del extrusor.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-1.webp" target="_blank">![extruder-housing-disasembly-step-1.webp](/media/images/extruder-housing-disasembly-step-1.webp =640x){.align-center}</a>
    
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