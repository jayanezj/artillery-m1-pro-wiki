---
title: Instalación de Perfiles Comunitarios
description: Tutorial para la instalación de perfiles comunitarios
published: true
date: 2025-11-25T14:27:46.970Z
tags: 
editor: markdown
dateCreated: 2025-11-24T22:26:26.154Z
---

# Antes de comezar

> No intentes utilizar estos perfiles comunitarios sin haber modificado el Firmware de la impresora antes. Pasa primero por la [guía de instalación de parches comunitarios](/es/guides/community-fixes)
{.is-danger}

* [GitHub con perfiles comunitarios](https://github.com/pijalu/artillery-m1-orca)

# Videotutorial

## OrcaSlicer (Recomendado)

https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/community-profiles-Guide:6

# Tutorial

## OrcaSlicer (Recomendado)

* Descargamos los perfiles comunitarios de [GitHub](https://github.com/pijalu/artillery-m1-orca/releases).
* Abrimos OrcaSlicer y navegamos en ``Archivo -> Importar -> Importar Configuraciones...``.
* Seleccionamos el fichero ``.zip`` y atomáticamente se cargarán todos los perfiles.
* Ahora en la Sección ``Preparar -> Impresora`` tendremos los perfiles importados.
* Si pulsamos sobre el icono de WiFi podremos configurar la conexión remota:
  * Tipo de Host: ``Octo/Klipper``
  * Nombre de host, IP o URL: ``DIRECCIÓN_IP:8078`` ([Fluidd](https://docs.fluidd.xyz/)) o ``DIRECCIÓN_IP`` ([Mainsail](https://docs.mainsail.xyz/))
* Si vamos a la Sección ``Dispositivo`` veremos la impresora.

## Artillery Studio (No recomendado)

> Artillery Studio no es compatible directamente con los perfiles comunitarios, y dado que se basa en OrcaSlicer es mejor utilizar OrcaSlicer directamente. Además perdemos la posibilidad de visualizar Fluidd/Mainsail desde el panel de dispositivo (aunque siempre podemos acceder desde un navegador).
{.is-warning}

* Descargamos los perfiles comunitarios de [GitHub](https://github.com/pijalu/artillery-m1-orca/releases).
* Descomprimimos el ``.zip`` descargado. Contiene ficheros con extensión ``.json`` de cada uno de los perfiles.
* Localizamos y copiamos el contenido de ``machine_start_gcode`` en el ``.json`` del perfil que escojamos.
* Abrimos Artillery Studio.
* En la Sección ``Preparar -> Impresora`` pulsamos en configurar en el perfil de Artillery M1 Pro.
* Habilitamos las opciones avanzadas (si no lo están) pulsando en el botón de la zona superior derecha.
* Vamos a la pestaña ``G-Code de la máquina`` y sustituimos el contenido de ``G-Code de inicio`` por el código del ``.json`` anterior.


