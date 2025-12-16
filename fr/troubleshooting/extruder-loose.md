---
title: Loose Extruder
description: Guide to tightening the extruder
published: true
date: 2025-12-16T12:07:04.453Z
tags:
editor: markdown
dateCreated: 2025-12-14T15:50:02.826Z
---

# Problem

The extruder becomes loose, causing it to wobble on the linear rail.

<center>
  <video width="640" height="360" autoplay loop muted>
    <source src="/media/video/extruder-loose.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</center>

## Consequences
If the extruder has play on the linear rail, we may encounter:

<table width="100%">
<tr>
  <th>Problem</th>
  <th>Example</th>
</tr>
<tr>
  <td>

- **Vibrations and print marks:** The play can result in surface defects, such as lines or bands caused by vibrations and imprecise movements.[^1]

  </td>
  <td>

  ![trouble-banding.webp](/media/images/trouble-banding.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>

- **Small shifts and uneven layers:** Even if the firmware and slicer are correct, the print head may move slightly out of position during fast movements, causing inaccuracies in dimensions and edges.[^2]

  </td>
  <td>

![trouble-layer-shift.webp](/media/images/trouble-layer-shift.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>

- **Loss of precision in combined movements:** In CoreXY printers, diagonal and combined movements rely heavily on a rigid carriage. A little “play” can result in curved lines or artifacts.[^3]

  </td>
  <td>

![trouble-layer-wobble.webp](/media/images/trouble-layer-wobble.webp =640x){.align-center}

  </td>
</tr>
</table>

# Required Tools

<table width="100%">
<tr>
  <th>Item</th>
  <th>Image</th>
</tr>
<tr>
  <td>

- **PTFE Tube Disassembly Tool:** This tool allows us to remove the PTFE tube from the extruder.
  - Available on the printer's MicroSD card.
  - [STL of the tool.](/media/stl/official_disassembling_ptfe_tool.zip)

  </td>
  <td>

![ptfe-tool.webp](/media/images/ptfe-tool.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>

- **Threadlocker:** Threadlocker liquid will prevent screws from loosening easily. **You can use any product for this purpose as long as it can withstand the temperatures reached inside the printer.** Keep in mind that the final curing time for these products usually exceeds one hour, so wait for it to dry before using the printer again to ensure proper fixation.
  - **Weiconlock AN 302-43:** Part of the WEICONLOCK anaerobic adhesive line, known for its reliability in industrial fastening and sealing applications. This medium-strength, higher-viscosity threadlocker prevents screws from loosening due to vibrations while allowing disassembly with standard tools. Its thermal resistance, ranging from ‑60 °C to +200 °C, makes it suitable for 3D printers.
    - [Weicon 🇪🇸](https://www.weicon.es/weiconlock-an-302-43-fijacion-de-tornillos-resistencia-media-mayor-viscosidad-con-aprobacion-de-agua-potable/10045974) - [Weicon 🇩🇪](https://www.weicon.de/weiconlock-an-302-43-schraubensicherung-mittelfest-hoeherviskos-mit-trinkwasserzulassung/10016419) - [Weicon 🇫🇷](https://www.weicon.fr/weiconlock-an-302-42-frein-filet-resistance-moyenne-homologue-pour-l-eau-potable/10017324) - [Weicon 🇮🇹](https://www.weicon.it/weiconlock-an-302-43-frenafiletti-media-resistenza-alta-viscosita-con-omologazione-per-acqua-potabile/10046605)
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B004Z0MEMI) - [Amazon 🇩🇪](https://www.amazon.de/dp/B004Z0MEMI) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B004Z0MEMI) - [Amazon 🇮🇹](https://www.amazon.it/dp/B004Z0MEMI) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B004Z0MEMI) - [Amazon 🇺🇸](https://www.amazon.com/dp/B004Z0MEMI)
  - **[Henkel Loctite 243](https://next.henkel-adhesives.com/us/en/products/industrial-adhesives/central-pdp.html/loctite-243/BP000000316211/variation/1330799.html)**: From the well-known brand LOCTITE (Henkel), this is a medium-strength threadlocker designed to prevent screws and nuts from loosening due to vibrations, even on slightly oily surfaces such as stainless steel or aluminum. Its anaerobic curing allows secure yet removable joints using standard tools, and it withstands temperatures from ‑55 °C to +180 °C, making it suitable for 3D printers. LOCTITE's reputation in industrial adhesives ensures durable and predictable fastening against vibrations and thermal changes.
    - [Amazon 🇪🇸](http://amazon.es/dp/B017L9LGBY) - [Amazon 🇩🇪](https://www.amazon.de/dp/B00B23VAZI) - [Amazon 🇫🇷](http://amazon.fr/dp/B017L9LHLI) - [Amazon 🇮🇹](https://www.amazon.it/dp/B017L9LHLI) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B071RCNVFJ) - [Amazon 🇺🇸](https://www.amazon.com/dp/B009I2UC3Q)
  - **LOOLIFL 243**: Medium-strength anaerobic threadlocker adhesive designed to prevent screws and nuts from loosening due to vibrations or mechanical shock while also sealing the joint. Unlike established industrial brands, LOOLIFL is usually a generic/no-name product sold at a very low price, with a basic formulation similar to other 243-type threadlockers, but with quality and consistency that may vary depending on the batch and supplier, and without the same technical support or certifications as products from recognized manufacturers.
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005009045272509.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005009045272509.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005009045272509.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005009045272509.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005009045272509.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256808858957757.html)

  </td>
  <td>
  
![threadlock-glue.webp](/media/images/threadlock-glue.webp =640x){.align-center}
    
  </td>
</tr>
<tr>
  <td>

- **Tweezers/Pliers:** This tool allows us to easily grab the screws of the extruder.
  - **[XURON 170-II](https://xuron.com/blog/170-ii-series-micro-shear-flush-cutters-in-four-configurations/)**: From the renowned American brand Xuron, it is a precision flush cutter designed to cut 3D printer filament and plastic remnants with clean, burr-free cuts. Made of high-quality steel with an ergonomic handle and return spring, it offers superior durability and control compared to generic pliers, making it ideal for detailed work in 3D printing and modeling.
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B002N1OXKC) - [Amazon 🇩🇪](http://amazon.de/dp/B002N1OXKC) - [Amazon 🇫🇷](http://amazon.fr/dp/B002N1OXKC) - [Amazon 🇮🇹](https://www.amazon.it/dp/B002N1OXKC) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B002N1OXKC) - [Amazon 🇺🇸](https://www.amazon.com/dp/B000IBSFAI)

  - **iViTC 170**: It is a “Model 170” type side cutter (similar to flush cutters) widely sold on sites like AliExpress, designed to cut wires, plastic filament, or small parts with a clean and precise cut thanks to its sharp blade. Although it does not have the backing of a well-known technical brand like Xuron or Hakko, it is an affordable and functional tool for 3D printer tasks and shares the shape and function of the commonly used type 170 cutters.
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005009648884992.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005009648884992.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005009648884992.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005009648884992.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005009648884992.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/1005009648884992.html)

  - **iFixit Precision Tweezers Set**: It is a precision tweezers set from the renowned brand iFixit, specialized in tools for the repair and maintenance of electronics and delicate devices. Made from high-quality stainless steel, the tweezers offer fine tips and precise grip, ideal for handling filament, removing support material, or adjusting small parts in 3D printers. Their durability and professional finish make them far more reliable than generic tweezers, making them an essential tool for detailed work in 3D printing and modeling.
    - [IFixit 🇪🇺](https://www.ifixit.com/en-eu/products/precision-tweezers-set) - [IFixit 🇩🇪](https://www.ifixit.com/de-de/products/precision-tweezers-set) - [IFixit 🇫🇷](https://www.ifixit.com/fr-fr/products/precision-tweezers-set) - [IFixit 🇮🇹](https://www.ifixit.com/it-it/products/precision-tweezers-set) - [IFixit 🇬🇧](https://www.ifixit.com/en-gb/products/precision-tweezers-set) - [IFixit 🇺🇸](https://www.ifixit.com/products/precision-tweezers-set)
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B079K874CQ) - [Amazon 🇩🇪](http://amazon.de/dp/B079K874CQ) - [Amazon 🇫🇷](http://amazon.fr/dp/B079K874CQ) - [Amazon 🇮🇹](https://www.amazon.it/dp/B079K874CQ) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B079K874CQ) - [Amazon 🇺🇸](https://www.amazon.com/dp/B079K874CQ)


- **Precision ESD anti-static tweezers set**: It is a generic precision anti-static tweezers kit made of stainless steel. The tools in the set are stainless steel with an anti-static/ESD and non-magnetic finish, which helps reduce the risk of electrostatic discharge when handling sensitive components, although being generic, there are no clear official certifications or a recognized brand behind it.
  - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005009930790317.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005009930790317.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005009930790317.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005009930790317.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005009930790317.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256809744475565.html)

  </td>
  <td>

![pliers-tweezers.webp](/media/images/pliers-tweezers.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>

- **Hex Key H2.0:** About half of the screws use this head.
  - The printer comes with an H2.0 hex key.
  - **[Wera 05073593001](https://www.wera.de/en/tools/950-9-hex-plus-multicolour-1-sb-l-key-set-metric-blacklaser/)**: It is a set of 9 metric L-shaped hex keys from the German brand Wera, renowned for producing high-quality hand tools for professionals and demanding hobbyists. This set uses Hex-Plus technology, which increases the contact surface with screws to reduce wear and allow torque application without damaging the heads. It also features color-coded handles and BlackLaser treatment for easy identification and high corrosion resistance. This type of hex key is ideal for assembling and adjusting components such as extruders, frames, or printed parts with hex screws, offering more precision and durability than generic Allen keys, enhancing the printer's maintenance and adjustment experience.
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B009ODV0OE) - [Amazon 🇩🇪](https://www.amazon.de/dp/B009ODV0OE) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B009ODV0OE) - [Amazon 🇮🇹](https://www.amazon.it/dp/B009ODV0OE) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B009ODV0OE) - [Amazon 🇺🇸](https://www.amazon.com/dp/B009ODV0OE)
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005008153293657.html)
    - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256807966978905.html)

- **RIDERACE 9-piece set**: This is a set of L-shaped hex keys from the brand Riderace, a manufacturer commonly found in budget tools for bicycles and basic repairs, usually made of CR-V or S2 steel with color-coded finishes for easy size identification. Although Riderace does not have the same reputation or technical support as specialized tool brands like Wera or Park Tool, many users find these keys functional and sufficient for maintenance tasks, offering versatility and portability at a low cost.
  - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005008298259316.html)
  - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256808111944564.html)

  </td>
  <td>

![h2-wrench.webp](/media/images/h2-wrench.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>

- **Hex key H1.5:** About half of the screws use this head.
  - The printer comes with an H1.5 hex key.
  - **[Wera 05073593001](https://www.wera.de/en/tools/950-9-hex-plus-multicolour-1-sb-l-key-set-metric-blacklaser/)**: It is a set of 9 metric L-shaped hex keys from the German brand Wera, renowned for producing high-quality hand tools for professionals and demanding hobbyists. This set uses Hex-Plus technology, which increases the contact surface with screws to reduce wear and allow torque application without damaging the heads. It also features color-coded handles and BlackLaser treatment for easy identification and high corrosion resistance. This type of hex key is ideal for assembling and adjusting components such as extruders, frames, or printed parts with hex screws, offering more precision and durability than generic Allen keys, enhancing the printer's maintenance and adjustment experience.
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B009ODV0OE) - [Amazon 🇩🇪](https://www.amazon.de/dp/B009ODV0OE) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B009ODV0OE) - [Amazon 🇮🇹](https://www.amazon.it/dp/B009ODV0OE) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B009ODV0OE) - [Amazon 🇺🇸](https://www.amazon.com/dp/B009ODV0OE)
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005008153293657.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256807966978905.html)

- **RIDERACE 9-piece set**: This is a set of L-shaped hex keys from the brand Riderace, a manufacturer commonly found in budget tools for bicycles and basic repairs, usually made of CR-V or S2 steel with color-coded finishes for easy size identification. Although Riderace does not have the same reputation or technical support as specialized tool brands like Wera or Park Tool, many users find these keys functional and sufficient for maintenance tasks, offering versatility and portability at a low cost.
  - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005008298259316.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256808111944564.html)

  </td>
  <td>

![h1.5-wrench.webp](/media/images/h1.5-wrench.webp =640x){.align-center}

  </td>
</tr>
</table>

# Video Guide


https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/extruder_loose_fix:0

# Guide


## Preliminary Steps

We must remove the filament before starting and unplug the machine from the power source.

## Extruder Removal

<table width="100%">
<tr>
  <th>Step</th>
  <th>Image (Click to view enlarged)</th>
</tr>
<tr>
  <td>

1. Using the extraction tool, remove the extruder tube.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-2.webp" target="_blank">![change-ptfe-tube-step-2.webp](/media/images/change-ptfe-tube-step-2.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

2. Separate the magnetic front cover by pulling it slightly upwards and outwards. Be careful with the filament cutter.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-1.webp" target="_blank">![/media/images/extruder-disasembly-step-1.webp](/media/images/extruder-disasembly-step-1.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

3. Once past the filament cutter, completely remove the front cover, taking care with the layer fan cable, which should be disconnected.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-2.webp" target="_blank">![/media/images/extruder-disasembly-step-2.webp](/media/images/extruder-disasembly-step-2.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

4. Remove the connectors for the hotend fans, auxiliary fans, bed level sensor, and the hotend itself.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-1.webp" target="_blank">![/media/images/extruder-disasembly-step-1.webp](/media/images/extruder-disasembly-step-1.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

5. Remove the M3*10 rounded head hex screws using an H2 wrench.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-4.webp" target="_blank">![/media/images/extruder-disasembly-step-4.webp](/media/images/extruder-disasembly-step-4.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

6. Remove the M2*6 cylindrical head hex screws and the M2.5*6 flat head screws using an H1.5 wrench.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-5.webp" target="_blank">![/media/images/extruder-disasembly-step-5.webp](/media/images/extruder-disasembly-step-5.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

7. Remove the M2.5*10 flat head hex screws and the M2.5*8 flat head screw using an H1.5 wrench.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-6.webp" target="_blank">![/media/images/extruder-disasembly-step-6.webp](/media/images/extruder-disasembly-step-6.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

8. Remove the extruder from the carriage.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-7.webp" target="_blank">![/media/images/extruder-disasembly-step-7.webp](/media/images/extruder-disasembly-step-7.webp =640x){.align-center}</a>

  </td>
</tr>
</table>

## Carriage Adjustment

<table width="100%">
<tr>
  <th>Step</th>
  <th>Image (Click to enlarge)</th>
</tr>
<tr>
  <td>

1. Remove the M3*10 flat-head hex screws using an H2 wrench.

  </td>
  <td>

<a href="/media/images/carriage-tighten-step-1.webp" target="_blank">![carriage-tighten-step-1.webp](/media/images/carriage-tighten-step-1.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

2. Apply threadlocker to the screw to prevent it from loosening again.

  </td>
  <td>

<a href="/media/images/carriage-tighten-step-2.webp" target="_blank">![carriage-tighten-step-2.webp](/media/images/carriage-tighten-step-2.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

3. Reinsert the screw and tighten it.

  </td>
  <td>

<a href="/media/images/carriage-tighten-step-3.webp" target="_blank">![carriage-tighten-step-3.webp](/media/images/carriage-tighten-step-3.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

4. Check that the carriage is properly secured. You should wait until the threadlocker is fully cured before using the printer again (threadlockers usually take a few hours to fully cure, depending on the product you use).

  </td>
  <td>

<a href="/media/images/carriage-tighten-step-4.webp" target="_blank">![carriage-tighten-step-4.webp](/media/images/carriage-tighten-step-4.webp =640x){.align-center}</a>

  </td>
</tr>
</table>

## Installing the Extruder

<table width="100%">
<tr>
  <th>Step</th>
  <th>Image (Click to enlarge)</th>
</tr>
<tr>
  <td>

1. Reinstall the extruder onto the carriage.

  </td>
  <td>

<a href="/media/images/extruder-asembly-step-1.webp" target="_blank">![/media/images/extruder-asembly-step-1.webp](/media/images/extruder-asembly-step-1.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

2. Install the M2.5*10 flat head hex screws and the M2.5*8 flat head screw using an H1.5 wrench.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-6.webp" target="_blank">![/media/images/extruder-disasembly-step-6.webp](/media/images/extruder-disasembly-step-6.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

3. Reconnect the cables to their respective connectors.

  </td>
  <td>

<a href="/media/images/extruder-asembly-step-3.webp" target="_blank">![/media/images/extruder-asembly-step-3.webp](/media/images/extruder-asembly-step-3.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

4. Reinstall the hotend and secure it with the M3*10 rounded head hex screws using an H2 wrench.

  </td>
  <td>

<a href="/media/images/extruder-disasembly-step-4.webp" target="_blank">![/media/images/extruder-disasembly-step-4.webp](/media/images/extruder-disasembly-step-4.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

6. Connect the front fan cable and reinstall the front cover, taking care with the filament cutter.

  </td>
  <td>

<a href="/media/images/extruder-asembly-step-6.webp" target="_blank">![/media/images/extruder-asembly-step-6.webp](/media/images/extruder-asembly-step-6.webp =640x){.align-center}</a>


  </td>
</tr>
</table>

[^1]:https://all3dp.com/2/z-banding-z-wobble-fix
[^2]:https://help.prusa3d.com/article/layer-shifting_2020
[^3]:https://www.reddit.com/r/3Dprinting/comments/1mj5cqa/having_this_strange_issue_with_my_corexy_printer
