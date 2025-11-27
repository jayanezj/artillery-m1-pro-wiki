---
title: Remplacement du tube PTFE
description: Guide pour le remplacement du tube PTFE
published: true
date: 2025-11-26T13:38:16.232Z
tags:
editor: markdown
dateCreated: 2025-11-26T13:37:30.907Z
---

# Le tube PTFE
Ce tube sert à guider le filament depuis la bobine jusqu'à l'extrudeur.

## Pièces nécessaires
<table>
<tr>
  <th>Pièce</th>
  <th>Image</th>
</tr>
<tr>
  <td>

- **Connecteur unidirectionnel :** Ce connecteur empêche le tube de bouger vers l'extérieur de l'extrudeur.
  - Vous pouvez réutiliser celui du tube PTFE d'origine.
  - Des connecteurs de rechange sont inclus dans le [kit Artillery](https://artillery3d.com/products/ptfe-tube-m1).
  - Vous pouvez obtenir un connecteur compatible sur [Aliexpress (ptfe embedded bowden collect)](https://aliexpress.com/item/1005009105267126.html).

  </td>
  <td>

![ptfe-collector.webp](/media/images/ptfe-collector.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>

- **Collier sur le manchon en silicone :** Assure le passage du filament de l'intérieur vers l'extérieur de la machine. Le diamètre extérieur du tube en silicone avec le PTFE à l'intérieur est d'environ 5,3 mm.
  - Vous pouvez réutiliser celui installé d'origine.
  - Un remplacement compatible peut être trouvé sur [Aliexpress (White Hose Clamps 5~5.5mm)](https://aliexpress.com/item/1005005697827712.html).

  </td>
  <td>

![ptfe-hose-clamp.webp](/media/images/ptfe-hose-clamp.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>

- **Tube PTFE :** Ce tube guide le filament depuis la bobine jusqu'à l'extrudeur, il est donc conseillé d'utiliser un tube avec un diamètre intérieur (2,5~3,0 mm) légèrement supérieur à celui du système Bowden (1,9~2,2 mm).
  - [Tube de remplacement fourni par Artillery](https://artillery3d.com/products/ptfe-tube-m1)
  - [Tube de remplacement Capricorn](https://www.captubes.com/shop/#!/Filament-Guide/c/173671010) (diamètre intérieur 3, diamètre extérieur 4). Meilleur PTFE du marché.
  - [Tube de remplacement Mellow](https://aliexpress.com/item/1005008268651680.html) (diamètre intérieur 3, diamètre extérieur 4). Qualité éprouvée.
  - [Tube Mellow basse friction en étoile](https://aliexpress.com/item/1005010202912335.html) (diamètre intérieur 2,2, diamètre extérieur 4). Bien que conçu pour Bowden, sa forme en étoile réduit la friction, mais **il n’est pas recommandé pour TPU ou matériaux abrasifs** (le design en étoile peut créer plus de friction qu’un tube conventionnel pour ce type de filament)[^1].

  </td>
  <td>

![ptfe-tube.webp](/media/images/ptfe-tube.webp =640x){.align-center}

  </td>
</tr>
<tr>
  <td>

- **Outil de désassemblage du tube PTFE :** Permet de retirer le tube PTFE de l'extrudeur.
  - Disponible sur la carte MicroSD de l'imprimante.
  - [STL de l’outil](/media/stl/official_disassembling_ptfe_tool.zip)

  </td>
  <td>

![ptfe-tool.webp](/media/images/ptfe-tool.webp =640x){.align-center}

  </td>
</tr>
</table>

## Vidéo guide

https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/change_ptfe_tube_guide:e

## Guide

> Artillery propose un [tutoriel sur son Wiki](https://wiki.artillery3d.com/m1/maintenance/add-the-ptfe-connector-assembly) pour le remplacement du tube.
{.is-info}

### Étapes préalables

Retirez le filament avant de commencer et débranchez l'imprimante.

### Retrait du tube PTFE

<table>
<tr>
  <th>Étape</th>
  <th>Image (Cliquez pour agrandir)</th>
</tr>
<tr>
  <td>

1. Retirez la pince blanche fixée sur le manchon à l’extérieur de l’imprimante.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-1.webp" target="_blank">![change-ptfe-tube-step-1.webp](/media/images/change-ptfe-tube-step-1.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

2. À l'aide de l'outil de retrait, extrayez le tube de l'extrudeur.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-2.webp" target="_blank">![change-ptfe-tube-step-2.webp](/media/images/change-ptfe-tube-step-2.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

3. Déconnectez les pinces de connexion et retirez la bride près de l'extrudeur (si encore présente).

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-3.webp" target="_blank">![change-ptfe-tube-step-3.webp](/media/images/change-ptfe-tube-step-3.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

4. Retirez le clip du connecteur unidirectionnel et extrayez-le par le côté extrudeur.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-4.webp" target="_blank">![change-ptfe-tube-step-4.webp](/media/images/change-ptfe-tube-step-4.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

5. Faites passer le tube PTFE de l'intérieur vers l'extérieur. Le connecteur unidirectionnel à l’extrémité du tube ne permet l’extraction que dans ce sens, **ne forcez pas dans l'autre sens** (risque d'endommager le tube).

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-5.webp" target="_blank">![change-ptfe-tube-step-5.webp](/media/images/change-ptfe-tube-step-5.webp =640x){.align-center}</a>

  </td>
</tr>
</table>

### Installation du tube PTFE

<table>
<tr>
  <td>

6. Insérez le connecteur unidirectionnel à l’intérieur de l’imprimante. La zone du clip bleu est la plus proche de la paroi de l’imprimante.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-6.webp" target="_blank">![change-ptfe-tube-step-6.webp](/media/images/change-ptfe-tube-step-6.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

7. Insérez le tube PTFE dans l'extrudeur et ajustez la longueur en déplaçant l'extrudeur sur toute la surface du lit.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-7.webp" target="_blank">![change-ptfe-tube-step-7.webp](/media/images/change-ptfe-tube-step-7.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

8. Placez les pinces de connexion et fixez le connecteur unidirectionnel avec le clip bleu.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-8.webp" target="_blank">![change-ptfe-tube-step-8.webp](/media/images/change-ptfe-tube-step-8.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

9. Connectez la pince blanche sur le manchon en silicone. **Ne serrez pas trop, juste assez pour que le tube PTFE ne bouge pas.**

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-9.webp" target="_blank">![change-ptfe-tube-step-9.webp](/media/images/change-ptfe-tube-step-9.webp =640x){.align-center}</a>

  </td>
</tr>
<tr>
  <td>

10. Faites passer le tube PTFE dans le connecteur unidirectionnel final.

  </td>
  <td>

<a href="/media/images/change-ptfe-tube-step-10.webp" target="_blank">![change-ptfe-tube-step-10.webp](/media/images/change-ptfe-tube-step-10.webp =640x){.align-center}</a>

  </td>
</tr>
</table>

[^1]: https://forum.bambulab.com/t/star-shaped-ptfe-tube/190829
