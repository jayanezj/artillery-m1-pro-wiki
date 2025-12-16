---
title: M1PRO S1 - Optimized Extruder
description: Installation guide for the optimized extruder for M1 PRO S1
published: true
date: 2025-12-16T16:26:35.455Z
tags:
editor: markdown
dateCreated: 2025-12-16T16:25:20.814Z
---

# Changes from V1

<a href="/media/images/extruder-housing-maintenance-step-2.webp" target="_blank">![/media/images/extruder-housing-maintenance-step-2.webp](/media/images/extruder-housing-maintenance-step-2.webp =640x){.align-center}</a>

## Reason for the Upgrade

- The coupling of the original extruder gear was too tight due to the original spring, increasing the likelihood of filament tangling in the gears.
- Occasional feeding jams could occur during extrusion.

## Solution

- Optimize the spring and spring mounting parameters. Tests show that filament tangling incidents are now rare during normal printing.
- Replace the top extruder housing assembly to ensure smoother filament feeding.

## Official Artillery Guide

- [Official Artillery guide available on their Wiki](https://wiki.artillery3d.com/m1/maintenance/m1-pro-upgrade-guide/m1-pro-s1-optimized-extruder-installation-guide)
  - [Reference copy on Archive.org](https://web.archive.org/web/20251216172245/https://wiki.artillery3d.com/m1/maintenance/m1-pro-upgrade-guide/m1-pro-s1-optimized-extruder-installation-guide)
  - [Reference copy on Archive Today](http://archive.today/DiU06)

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

- **Isopropanol / Contact Cleaner:** Ensures proper cleaning of components without leaving residues or damaging plastics or metals. **Any cleaner that evaporates quickly and leaves no residue is fine.**
  - **[EQM - ECO-301](https://www.ecosolucionesquimicas.es/en/producto/alcohol-isopropilico-eqm-999-pureza/)**: It is a high-purity (99.9%) isopropyl alcohol from the brand EQM Soluciones Químicas, a Spanish supplier of technical chemical products used for specialized cleaning of delicate surfaces. Its additive-free formula evaporates quickly without leaving residue, making it suitable for cleaning dirt, grease, and filament or adhesive residues before adjusting or lubricating parts, promoting smoother operation and reducing the accumulation of contaminants that could affect performance without damaging metals or plastics.
    - [Eco 🇪🇸](https://www.ecosolucionesquimicas.es/fr/producto/alcohol-isopropilico-eqm-999-pureza/) - [Eco 🇫🇷](https://www.ecosolucionesquimicas.es/fr/producto/alcohol-isopropilico-eqm-999-pureza) - [Eco 🇬🇧](https://www.ecosolucionesquimicas.es/en/producto/alcohol-isopropilico-eqm-999-pureza/)
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B07SH9FY7G) - [Amazon 🇩🇪](https://www.amazon.de/dp/B07SH9FY7G) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B07SH9FY7G) - [Amazon 🇮🇹](https://www.amazon.it/dp/B07SH9FY7G) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B07SH9FY7G) - [Amazon 🇺🇸](https://www.amazon.com/dp/B00DT52Y98)

  - **[Sonax - 04603000](https://www.sonax.com/en/care-products/electronicscontact-cleaner-with-easyspray-400-ml-04603000)**: It is a contact and electronic component cleaner from the German brand SONAX, renowned for its high-quality technical cleaning and maintenance products “made in Germany.” This cleaner is formulated to remove dirt, oil, silicone residues, and oxidation from electrical contacts, connectors, and other components without leaving any residue, thanks to its extremely fast evaporation and compatibility with plastics and metals. It is useful for cleaning gears, extruders, and electrical contacts before maintenance or adjustment, improving current flow and ensuring smooth operation of mechanical and electronic parts; its EasySpray system allows precise application even in tight spaces.
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B077GSVN4C) - [Amazon 🇩🇪](https://www.amazon.de/dp/B077GSVN4C) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B077GSVN4C) - [Amazon 🇮🇹](https://www.amazon.it/dp/B077GSVN4C)

  - **[WD-40 Specialist Contact Cleaner](https://www.wd40.com/products/contact-cleaner/)**: It is a dielectric contact cleaner spray from the WD‑40 Specialist line, a globally well-known brand for its technical maintenance products and cleaning and lubrication solutions. This cleaner is formulated to remove oil, dust, dirt, condensation, and flux residues from sensitive electrical and electronic components without leaving any residue, as it evaporates quickly and is non-conductive. It is useful for cleaning gears, connectors, electrical contacts, and parts of the extruder before maintenance or adjustments, helping to restore good contact and smooth operation of mechanical and electronic parts; its applicator also allows precise access to tight spaces without damaging plastics or metals.
    - [Amazon 🇪🇸](http://amazon.es/dp/B01N4554M2) - [Amazon 🇩🇪](https://www.amazon.de/dp/B0987C5CMR) - [Amazon 🇫🇷](http://amazon.fr/dp/B01MTD0594) - [Amazon 🇮🇹](https://www.amazon.it/dp/B00GTV24JE) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B00KPUBO2S) - [Amazon 🇺🇸](https://www.amazon.com/dp/B00AF0OFVU)
  </td>
  <td>

![isopropanol-contact-cleaner-tool.webp](/media/images/isopropanol-contact-cleaner-tool.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>

- **Oil lubricant:** To ensure smooth operation of the extruder gears, prevent squeaking, and extend the lifespan of internal components, we must lubricate the gears and bearings. **You can use any lubricant as long as it has a high degree of slipperiness and is compatible with the plastics and metals of the extruder components**.

  - **[Superlube 51004](https://www.super-lube.com/wp-content/uploads/2025/06/Technical_Data_Sheet_Multi_Use_Oil_w_Syncolon.pdf)**: It is a high-quality synthetic oil from the brand Super Lube®, a manufacturer specialized in industrial and maintenance lubricants with PTFE particles that reduce friction, wear, rust, and corrosion on moving components. Its synthetic base formula with PTFE adheres well to metal and plastic surfaces and offers broad compatibility and an operating temperature range of approximately –43 °C to +232 °C, allowing safe use for lubricating rods, linear guides, bearings, and other moving mechanisms, improving sliding and reducing wear compared to generic oils. It is valued by many users for its stable performance and durability in 3D printer maintenance.
    - [SuperLube 🇪🇺](https://super-lube.eu/en/oils/44-51004-multi-use-synthetic-oil-with-ptfe-118-ml-0082353510047.html) - [SuperLube 🇩🇪](https://super-lube.eu/de/oele/44-51004-super-lube-synthetisches-mehrzweckoel-mit-ptfe-118-ml-0082353510047.html) - [SuperLube 🇫🇷](https://super-lube.eu/fr/huiles/44-51004-huile-synthetique-polyvalente-avec-ptfe-118-ml-0082353510047.html)
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005009944982308.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005009944982308.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005009944982308.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005009944982308.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256808495252837.html)
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B000UKUHXK) - [Amazon 🇩🇪](https://www.amazon.de/dp/B000UKUHXK) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B000UKUHXK) - [Amazon 🇮🇹](https://www.amazon.it/dp/B000UKUHXK)
    - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B000UKUHXK) - [Amazon 🇺🇸](https://www.amazon.com/dp/B000UKUHXK)

  - **Sikezhan 3D Printer Lubricant**: It is a formulation promoted in online stores with claims about dry film lubrication with molybdenum disulfide (MoS₂) and noise and wear reduction, but **there are no independent references to the brand or verifiable technical documentation supporting these claims.** It is generally preferable to use lubricants with clear specifications and backing from recognized manufacturers or community-recommended products, as generic products without technical data may offer unpredictable performance and compatibility with 3D printer parts and materials. It is a cheap alternative to Super Lube that seems to work well according to buyer feedback.
    - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005010363007211.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005010332562884.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005010363007211.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005010363007211.html) - [Aliexpress 🇬🇧](https://www.aliexpress.us/item/3256810176692459.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256810176692459.html)

  - **[Sonax - 03483000](https://www.sonax.com/en/care-products/silicone-spray-with-easyspray-400-ml-03483000)**: It is a silicone spray lubricant from the German brand SONAX, internationally recognized for its automotive cleaning, care, and maintenance products with a strong reputation for “made in Germany” quality and widespread presence in workshops and home use. This spray is formulated to lubricate, protect, and care for rubber, plastic, and metal parts, leaving a durable, water-repellent lubricating film that eliminates squeaks and facilitates the movement of moving parts. Documentation confirms that it is safe for plastics and metals, indicating it can be applied cautiously on 3D-printed plastic parts or steel and aluminum structures without degrading these surfaces. This type of spray is useful for lubricating mechanical components such as guides, hinges, or moving parts not subjected to heavy loads, reducing friction and noise; however, for precision components like screws, bearings, or gears under continuous load and movement, many users and technicians prefer specialized greases with higher adhesion (e.g., with PTFE or ceramics) to ensure longer-lasting and controlled lubrication.
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B072BZZ41R) - [Amazon 🇩🇪](https://www.amazon.de/dp/B072BZZ41R) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B072BZZ41R) - [Amazon 🇮🇹](https://www.amazon.it/dp/B072BZZ41R)

  - **[WD-40 Specialist Lubricante de Silicona](https://www.wd40.com/products/silicone-lubricant/)**: It is a silicone spray lubricant from the WD‑40 Specialist line, a brand with a solid international track record in maintenance, protection, and technical lubrication products for multiple applications. Its silicone-based formula is designed to lubricate, waterproof, and protect both metallic and non-metallic surfaces—including plastic and rubber—without leaving sticky residues, forming a clear film that does not attract dirt and helps keep moving mechanisms smooth and protected. Documentation confirms that it is safe for plastics and metals, indicating that it can be applied cautiously on 3D-printed plastic parts or steel and aluminum structures without degrading these surfaces. This type of spray is useful for lubricating mechanical components such as guides, hinges, or moving parts not subjected to heavy loads, reducing friction and noise; however, for precision components like screws, bearings, or gears under continuous load and movement, many users and technicians prefer specialized greases with higher adhesion (e.g., with PTFE or ceramics) to ensure longer-lasting and controlled lubrication.
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B01N56KX44) - [Amazon 🇩🇪](https://www.amazon.de/dp/B0913B5NBF) - [Amazon 🇫🇷](https://www.amazon.fr/dp/B0081SMLR8) - [Amazon 🇮🇹](https://www.amazon.it/dp/B00GTV25D4) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B006UCNI38) - [Amazon 🇺🇸](https://www.amazon.com/dp/B00631GSSI)

  </td>
  <td>

![oil-lubricant-tool.webp](/media/images/oil-lubricant-tool.webp =640x){.align-center}

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
<tr>
  <td>

- **Phillips PH0 screwdriver:** The screws on the extruder mainboard are of this type.
  - The printer comes with a PH0 screwdriver.
  - The Artillery M1 Pro S1 upgrade kit also includes a PH0 screwdriver.
  - **iFixit Minnow Precision Bit Set**: A compact precision screwdriver bit set from the well-known brand iFixit, specialized in tools for electronics and delicate repairs. It includes several small Phillips bits (000, 0, and 1) made of durable S2 steel, ideal for screwing and unscrewing mechanical components of 3D printers such as gears, extruders, or frames without damaging screw heads, offering precision and durability for maintenance and fine adjustments.
    - [IFixit 🇪🇺](https://www.ifixit.com/en-eu/products/minnow-driver-kit) - [IFixit 🇩🇪](https://www.ifixit.com/de-de/products/minnow-driver-kit) - [IFixit 🇫🇷](https://www.ifixit.com/fr-fr/products/minnow-driver-kit) - [IFixit 🇮🇹](https://www.ifixit.com/it-it/products/minnow-driver-kit) - [IFixit 🇬🇧](https://www.ifixit.com/en-gb/products/minnow-driver-kit) - [IFixit 🇺🇸](https://www.ifixit.com/products/minnow-driver-kit)
    - [Amazon 🇪🇸](https://www.amazon.es/dp/B08NWJH6TD) - [Amazon 🇩🇪](http://amazon.de/dp/B08NWJH6TD) - [Amazon 🇫🇷](http://amazon.fr/dp/B08NWJH6TD) - [Amazon 🇮🇹](https://www.amazon.it/dp/B08NWJH6TD) - [Amazon 🇬🇧](https://www.amazon.co.uk/dp/B08NWJH6TD) - [Amazon 🇺🇸](https://www.amazon.com/dp/B08NWJH6TD)

  </td>
  <td>

![ph0-screwdriver.webp](/media/images/ph0-screwdriver.webp =640x){.align-center}

  </td>
</tr>
</table>

# Optional Tools

<table width="100%">
<tr>
  <th>Part</th>
  <th>Image</th>
</tr>
<tr>
  <td colspan="2">

- **Links to the official Artillery stores with all spare parts available for M1 Pro**.
  - [Artillery 🇪🇺](https://eu.artillery3d.com/collections/spare-parts-for-m1-series?filter=m1+series)
  - [Artillery 🇺🇸](https://www.artillery3d.com/collections/spare-parts-for-m1-series)
  - [Aliexpress principal](https://artillery.aliexpress.com/store/1100983046/pages/all-items.html?sortType=bestmatch_sort&SearchText=m1&shop_sortType=bestmatch_sort)
  - [Aliexpress secundaria](https://aliexpress.com/store/1101459703/pages/all-items.html?sortType=bestmatch_sort&SearchText=m1&shop_sortType=bestmatch_sort)

  </td>
</tr>
<tr>
  <td>

- **Gear Set**: This is a replacement kit for the extruder gears. Artillery designed these gears so that, in the event of a major jam, the gears break instead of the motor (which is a more expensive replacement). A gear with broken teeth will cause skipped steps, which can be problematic for our prints.
  - [Artillery 🇪🇺](https://eu.artillery3d.com/products/drive-idler-gear-set-extruder-m1) - [Artillery 🇺🇸](https://www.artillery3d.com/products/drive-idler-gear-set-extruder-m1)
  - [Aliexpress 🇪🇸](https://es.aliexpress.com/item/1005010180596582.html) - [Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005010180596582.html) - [Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005010180596582.html) - [Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005010180596582.html) - [Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005010180596582.html) - [Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256809994281830.html)
  - [Alternative Aliexpress 🇪🇸](http://es.aliexpress.com/item/1005010185029344.html) - [Alternative Aliexpress 🇩🇪](https://de.aliexpress.com/item/1005010185029344.html) - [Alternative Aliexpress 🇫🇷](https://fr.aliexpress.com/item/1005010185029344.html) - [Alternative Aliexpress 🇮🇹](https://it.aliexpress.com/item/1005010185029344.html) - [Alternative Aliexpress 🇬🇧](https://www.aliexpress.com/item/1005010185029344.html) - [Alternative Aliexpress 🇺🇸](https://www.aliexpress.us/item/3256809998714592.html)

  </td>
  <td>

![extruder-housing-maintenance-step-1.webp](/media/images/extruder-housing-maintenance-step-1.webp =640x){.align-center}

  </td>
</tr>
</table>

# Video Guide


https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/extruder_v2_upgrade:3

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

## Disassembly of the Extruder Housing

<table width="100%">
<tr>
  <th>Step</th>
  <th>Image (Click to expand)</th>
</tr>
<tr>
  <td>

1. Disconnect the extruder motor terminal.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-1.webp" target="_blank">![extruder-housing-disasembly-step-1.webp](/media/images/extruder-housing-disasembly-step-1.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

2. Remove the three M2*5 flat head Phillips PH1 screws.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-2.webp" target="_blank">![extruder-housing-disasembly-step-2.webp](/media/images/extruder-housing-disasembly-step-2.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

3. Disconnect the terminals of the filament cutter. Since the V2 housing comes with a new cable along with the electronic boards and the cutter itself, you can either disconnect the cable from the main board (recommended, as the new cable is attached to the V2 housing boards) or keep the old cable and connect it to the electronic boards of the V2 housing (the cable is compatible).

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-3.webp" target="_blank">![extruder-housing-disasembly-step-3.webp](/media/images/extruder-housing-disasembly-step-3.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

4. Remove the four M2.5*8 flat head hex screws using an H1.5 hex key.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-4.webp" target="_blank">![extruder-housing-disasembly-step-4.webp](/media/images/extruder-housing-disasembly-step-4.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

5. Remove the M3*8 countersunk hex screw using an H1.5 hex key.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-5.webp" target="_blank">![extruder-housing-disasembly-step-5.webp](/media/images/extruder-housing-disasembly-step-5.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

6. Open the housing by pulling each side in opposite directions. **It is very likely that the spring retention bracket will pop out when opening the housing**.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-6.webp" target="_blank">![extruder-housing-disasembly-step-6.webp](/media/images/extruder-housing-disasembly-step-6.webp =640x){.align-center}</a>

  </td>
</tr>
</table>

## Replacement and Maintenance of the Extruder Housing

<table width="100%">
<tr>
  <th>Step</th>
  <th>Image (Click to view enlarged)</th>
</tr>
<tr>
  <td>

1. The first thing we will do is check the general condition of the gears. If we detect any issues, Artillery provides a kit for replacement, indicated in the tools section.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-1.webp" target="_blank">![extruder-housing-maintenance-step-1.webp](/media/images/extruder-housing-maintenance-step-1.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

2. Retrieve the bearing from the V1 housing if it has remained attached (which will likely be the case), or take one from the replacement kit.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-3.webp" target="_blank">![extruder-housing-maintenance-step-3.webp](/media/images/extruder-housing-maintenance-step-3.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

3. Carefully inspect the condition of the gear wheel that attaches to the motor. Artillery designed this gear in plastic so that a jam does not burn the motor (which is a more expensive component to replace than the gear), so the teeth may be damaged if there have been jams.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-4.webp" target="_blank">![extruder-housing-maintenance-step-4.webp](/media/images/extruder-housing-maintenance-step-4.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

4. Clean all dirt from the gear with isopropanol or contact cleaner.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-5.webp" target="_blank">![extruder-housing-maintenance-step-5.webp](/media/images/extruder-housing-maintenance-step-5.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

5. Lubricate the bearing to ensure smooth movement and clean off any excess lubricant.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-6.webp" target="_blank">![extruder-housing-maintenance-step-6.webp](/media/images/extruder-housing-maintenance-step-6.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

6. Place the clean and lubricated bearing into the V2 housing.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-7.webp" target="_blank">![extruder-housing-maintenance-step-7.webp](/media/images/extruder-housing-maintenance-step-7.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

7. Check that the bearing is properly seated and fixed in the V2 housing while its inner part rotates freely.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-8.webp" target="_blank">![extruder-housing-maintenance-step-8.webp](/media/images/extruder-housing-maintenance-step-8.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

8. Clean all dirt from the motor housing and its gear with isopropanol or contact cleaner.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-9.webp" target="_blank">![extruder-housing-maintenance-step-9.webp](/media/images/extruder-housing-maintenance-step-9.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

9. Lubricate the bearing in the housing to ensure smooth movement and wipe off any excess lubricant. You can remove the bearing first if you want to clean and grease it more thoroughly. Remember to check afterwards that it remains fixed in position and rotates freely on the inner part.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-10.webp" target="_blank">![extruder-housing-maintenance-step-10.webp](/media/images/extruder-housing-maintenance-step-10.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

10. Install the gear into the motor housing.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-11.webp" target="_blank">![extruder-housing-maintenance-step-11.webp](/media/images/extruder-housing-maintenance-step-11.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

11. Check that the gear rotates correctly with the motor and that no steps are lost.

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-12.webp" target="_blank">![extruder-housing-maintenance-step-12.webp](/media/images/extruder-housing-maintenance-step-12.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

12. Recheck that the gear is in good condition. **Disassembling this gear is a tedious process, so it’s better to double-check everything now than to lose steps later due to a damaged gear.**

  </td>
  <td>

<a href="/media/images/extruder-housing-maintenance-step-13.webp" target="_blank">![extruder-housing-maintenance-step-13.webp](/media/images/extruder-housing-maintenance-step-13.webp =640x){.align-center}</a>

  </td>
</tr>
</table>

## Assembling the Extruder Housing

<table width="100%">
<tr>
  <th>Step</th>
  <th>Image (Click to enlarge)</th>
</tr>
<tr>
  <td>

1. On one side, we have the V2 housing with only the bearing installed. (If you have the metal rod that serves as the axis for the clip on this side, remove it to move it to the other side).

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-1.webp" target="_blank">![extruder-housing-asembly-step-1.webp](/media/images/extruder-housing-asembly-step-1.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

2. On the other side, we have the housing with the motor, the metal rod, and the bearing.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-2.webp" target="_blank">![extruder-housing-asembly-step-2.webp](/media/images/extruder-housing-asembly-step-2.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

3. Place the gear on the extruder side (if it was removed for maintenance and checks).

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-3.webp" target="_blank">![extruder-housing-asembly-step-3.webp](/media/images/extruder-housing-asembly-step-3.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

4. Insert the extruder gear clip through its axle rod.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-4.webp" target="_blank">![extruder-housing-asembly-step-4.webp](/media/images/extruder-housing-asembly-step-4.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

5. Check that the gears through which the filament will pass rotate correctly.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-5.webp" target="_blank">![extruder-housing-asembly-step-5.webp](/media/images/extruder-housing-asembly-step-5.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

6. Place the V2 spring with its V2 retainer between the motor housing and the clip. **If you have trouble** installing it, you can remove the clip from the axle rod, place the side of the clip with the spring against the motor housing first, put the metal rod directly over the clip, and then position the rod in the housing. **This procedure is detailed in the [video guide](https://odysee.com/@ArtilleryM1ProCommunity:6/extruder_v2_upgrade:3?r=Fj5J5CAzCxrWwoBoZxuvw3RdPZar3veY&t=515)**.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-6.webp" target="_blank">![extruder-housing-asembly-step-6.webp](/media/images/extruder-housing-asembly-step-6.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

7. Check the proper alignment of the filament gears with the spring installed.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-7.webp" target="_blank">![extruder-housing-asembly-step-7.webp](/media/images/extruder-housing-asembly-step-7.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

8. Pass the motor wiring through the slot in the V2 housing.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-8.webp" target="_blank">![extruder-housing-asembly-step-8.webp](/media/images/extruder-housing-asembly-step-8.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

9. Close the housing, making sure everything stays in place, especially the filament extrusion clip spring.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-9.webp" target="_blank">![extruder-housing-asembly-step-9.webp](/media/images/extruder-housing-asembly-step-9.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

10. Install the M3*8 countersunk hex screw with an H1.5 wrench.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-5.webp" target="_blank">![extruder-housing-disasembly-step-5.webp](/media/images/extruder-housing-disasembly-step-5.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

11. If we choose to use the new filament cutter wiring that comes with the V2 housing, we must remove the old wiring. To do this, carefully pull the wires through the slot in the board (if you have difficulty, you can separate them individually for easier handling) and disconnect the terminal (which may come with a fixing paste) from the board.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-10.webp" target="_blank">![extruder-housing-asembly-step-10.webp](/media/images/extruder-housing-asembly-step-10.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

12. Pass the new wiring through the slot in the board. Again, if it is difficult, you can separate the cable harness to pass them individually; the important thing is not to damage the harness or the board. Connect the terminal to the board.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-11.webp" target="_blank">![extruder-housing-asembly-step-11.webp](/media/images/extruder-housing-asembly-step-11.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

13. Connect the terminal to the board.

  </td>
  <td>

<a href="/media/images/extruder-housing-asembly-step-12.webp" target="_blank">![extruder-housing-asembly-step-12.webp](/media/images/extruder-housing-asembly-step-12.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

14. Install the four M2.5*8 flat head hex screws with an H1.5 wrench.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-4.webp" target="_blank">![extruder-housing-disasembly-step-4.webp](/media/images/extruder-housing-disasembly-step-4.webp =640x){.align-center}</a>

  </td>
</tr>  
<tr>
  <td>

15. Install the three M2*5 flat head Phillips PH1 screws.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-2.webp" target="_blank">![extruder-housing-disasembly-step-2.webp](/media/images/extruder-housing-disasembly-step-2.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

16. Connect the extruder motor terminal.

  </td>
  <td>

<a href="/media/images/extruder-housing-disasembly-step-1.webp" target="_blank">![extruder-housing-disasembly-step-1.webp](/media/images/extruder-housing-disasembly-step-1.webp =640x){.align-center}</a>

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
