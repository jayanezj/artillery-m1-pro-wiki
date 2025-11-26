---
title: Instalación de parches comunitarios
description: Guía para la instalación de parches comunitarios
published: true
date: 2025-11-26T19:22:15.694Z
tags: 
editor: markdown
dateCreated: 2025-11-24T21:06:14.554Z
---

# Antes de comenzar

> ¡No intentes utilizar el parcheador automático en una versión de Firmware diferente a las esperadas, tu impresora puede convertirse en un ladrillo y entonces tendrás que volver a instalar el sistema base!
{.is-danger}

> Modificar el firmware de la impresora anulará la garantía y puede causar potenciales problemas, lee la información proporcionada en el parcheador antes de comenzar.
{.is-danger}

* Versiones actualmente soportadas:
  * [V1.00.12.0](https://wiki.artillery3d.com/m1/manual/m1-firmware-release-history#v1001200-20251104)
  * [V1.00.11.0](https://wiki.artillery3d.com/m1/manual/m1-firmware-release-history#v1001100-20250829)
  

# Vídeo guía

https://odysee.com/$/embed/@ArtilleryM1ProCommunity:6/printer-patcher-guide:f

# Guía

## Dirección IP

* Nuestra impresora debe de estar en la misma red que el ordenador/dispositivo Android que utilizaremos.
* Podemos consultar la dirección IP desde la pantalla de la impresora en el cuarto botón del menú izquierdo (Ajustes) -> Pestaña WiFi.

## Software de parches comunitarios

* [Repositorio Printer Patcher](https://github.com/pijalu/printer-patcher/releases)

Descargamos la aplicación en función de nuestro dispositivo.

> En Mac OS debemos permitir la ejecución de la aplicación mediante un comando incluido en el fichero readme.txt. Si no lo hacemos aparecerá un error de que la aplicación está dañada porque no tiene certificado de firma de Apple. Es seguro utilizarla.
{.is-info}

Desde el Printer Patcher podremos:
  * Recuperar la interfaz [Fluidd](https://docs.fluidd.xyz/).
  * Instalar los parches de la comunidad.
  * Recuperar registros de [Klipper](https://www.klipper3d.org/Debugging.html), Moonraker, puerto de serie, USB.

1. Introducimos la dirección de nuestra impresora obtenida anteriormente.
1. Recuperamos la interfaz Fluidd e instalamos los parches de la comunidad.

> Cuando instalemos los parches de la comunidad, aunque la instalación desde Printer Patcher se complete, la impresora estará instalado actualizaciones de Moonraker durante al menos 10 minutos más. **No debemos desconectar la impresora** para que la actualización se complete correctamente.
{.is-warning}

> Al terminar completamente la instalación de paquetes podremos ver nuestra impresora con Fluidd funcionando en <kbd>http://direccion_impresora:8078</kbd>
> 
> También puedes ver Mainsail en <kbd>http://direccion_impresora</kbd>
{.is-success}

> Créditos a [@pijalu](https://github.com/pijalu) por desarrollar la herramienta para parchear la impresora, así como los perfiles comunitarios y las modificaciones firmware.

