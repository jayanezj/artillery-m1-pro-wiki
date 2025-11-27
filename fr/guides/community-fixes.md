---
title: Installation des patches communautaires
description: Guide pour l'installation des patches communautaires
published: true
date: 2025-11-26T19:22:15.694Z
tags:
editor: markdown
dateCreated: 2025-11-24T21:06:14.554Z
---

# Avant de commencer

> N’essayez pas d’utiliser le patcher automatique sur une version du firmware différente de celles prévues, votre imprimante pourrait devenir inutilisable et vous devrez réinstaller le système de base !
{.is-danger}

> Modifier le firmware de l’imprimante annulera la garantie et peut provoquer des problèmes potentiels. Lisez les informations fournies dans le patcher avant de commencer.
{.is-danger}

* Versions actuellement supportées :
  * [V1.00.12.0](https://wiki.artillery3d.com/m1/manual/m1-firmware-release-history#v1001200-20251104)
  * [V1.00.11.0](https://wiki.artillery3d.com/m1/manual/m1-firmware-release-history#v1001100-20250829)

# Vidéo guide

https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/printer-patcher-guide:f

# Guide

## Adresse IP

* Notre imprimante doit être sur le même réseau que l’ordinateur ou le dispositif Android que nous utiliserons.
* Nous pouvons vérifier l’adresse IP depuis l’écran de l’imprimante en cliquant sur le quatrième bouton du menu gauche (Paramètres) -> Onglet WiFi.

## Logiciel de patches communautaires

* [Répertoire Printer Patcher](https://github.com/pijalu/printer-patcher/releases)

Téléchargez l’application adaptée à votre dispositif.

> Sur Mac OS, il faut autoriser l’exécution de l’application via une commande incluse dans le fichier readme.txt. Sinon, un message d’erreur indiquera que l’application est endommagée car elle n’a pas de certificat Apple. Son utilisation est sûre.
{.is-info}

Depuis Printer Patcher, vous pouvez :
* Restaurer l’interface [Fluidd](https://docs.fluidd.xyz/).
* Installer les patches communautaires.
* Récupérer les logs de [Klipper](https://www.klipper3d.org/Debugging.html), Moonraker, port série, USB.

1. Entrez l’adresse IP de votre imprimante obtenue précédemment.
1. Restaurez l’interface Fluidd et installez les patches communautaires.

> Lorsque nous installons les patches communautaires, même si l’installation via Printer Patcher est terminée, l’imprimante continuera à installer les mises à jour de Moonraker pendant au moins 10 minutes. **Ne déconnectez pas l’imprimante** pour que la mise à jour se termine correctement.
{.is-warning}

> Une fois l’installation complète des packages terminée, vous pourrez voir votre imprimante fonctionner avec Fluidd à <kbd>http://adresse_imprimante:8078</kbd>
>
> Vous pouvez également accéder à Mainsail à <kbd>http://adresse_imprimante</kbd>
{.is-success}

> Crédits à [@pijalu](https://github.com/pijalu) pour le développement de l’outil de patch de l’imprimante, ainsi que pour les profils communautaires et les modifications du firmware.
