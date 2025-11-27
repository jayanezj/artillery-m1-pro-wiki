---
title: Installation des profils communautaires
description: Guide pour l'installation des profils communautaires
published: true
date: 2025-11-26T19:17:08.087Z
tags: 
editor: markdown
dateCreated: 2025-11-24T22:26:26.154Z
---

# Avant de commencer

> N’essayez pas d’utiliser ces profils communautaires sans avoir modifié le firmware de l’imprimante au préalable. Passez d’abord par le [guide d’installation des patches communautaires](/fr/guides/community-fixes)
{.is-danger}

* [GitHub avec profils communautaires](https://github.com/pijalu/artillery-m1-orca)

# Vidéo guide

## OrcaSlicer (Recommandé)

https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/community-profiles-Guide:6

# Guide

## OrcaSlicer (Recommandé)

* Téléchargez les profils communautaires depuis [GitHub](https://github.com/pijalu/artillery-m1-orca/releases).
* Ouvrez OrcaSlicer et naviguez vers ``Fichier -> Importer -> Importer les configurations...``.
* Sélectionnez le fichier ``.zip`` et tous les profils seront chargés automatiquement.
* Dans la section ``Préparer -> Imprimante``, vous trouverez les profils importés.
* Cliquez sur l’icône WiFi pour configurer la connexion à distance :
  * Type d’hôte : ``Octo/Klipper``
  * Nom d’hôte, IP ou URL : ``ADRESSE_IP:8078`` ([Fluidd](https://docs.fluidd.xyz/)) ou ``ADRESSE_IP`` ([Mainsail](https://docs.mainsail.xyz/))
* Dans la section ``Périphérique``, vous verrez l’imprimante.

## Artillery Studio (Non recommandé)

> Artillery Studio n’est pas directement compatible avec les profils communautaires. Comme il est basé sur OrcaSlicer, il est préférable d’utiliser OrcaSlicer directement. De plus, nous perdons la possibilité de visualiser Fluidd/Mainsail depuis le panneau périphérique (mais nous pouvons toujours y accéder depuis un navigateur).
{.is-warning}

* Téléchargez les profils communautaires depuis [GitHub](https://github.com/pijalu/artillery-m1-orca/releases).
* Décompressez le fichier ``.zip`` téléchargé. Il contient des fichiers avec l’extension ``.json`` pour chaque profil.
* Localisez et copiez le contenu de ``machine_start_gcode`` dans le fichier ``.json`` du profil choisi.
* Ouvrez Artillery Studio.
* Dans la section ``Préparer -> Imprimante``, cliquez sur configurer le profil Artillery M1 Pro.
* Activez les options avancées (si ce n’est pas déjà fait) en cliquant sur le bouton en haut à droite.
* Allez à l’onglet ``G-Code de la machine`` et remplacez le contenu de ``G-Code de démarrage`` par le code du fichier ``.json`` précédent.

> Crédits à [@pijalu](https://github.com/pijalu) pour le développement de l’outil de patch de l’imprimante, ainsi que les profils communautaires et les modifications du firmware.
