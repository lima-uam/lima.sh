+++
date = '2026-02-27T17:42:33+01:00'
draft = false
title = 'Servidor Minecraft CE-EPS LIMA'
aliases = ["/mc/"]
[params]
    subtitle = 'La escuela ya cuenta con servidor de minecraft propio, abierto a todos los miembros de la comunidad.'
+++

{{< figure src="./images/mc_social_logo.png" width="20%" alt="Cara de creeper simplificada representativa del videojuego Minecraft" >}}

Con motivo de la celebración del día de la EPS 2026 nace el servidor de minecraft oficial de la EPS.

El **Consejo de Estudiantes** en colaboración con la **Asociación LIMA** 🍋‍🟩 ofrecemos un servidor vanilla disponible a todos los estudiantes de la EPS durante todas las horas del día.

## Información básica

- Versión del juego: vanilla `1.21.11`, con actualizaciones cuando salgan versiones posteriores.
- Soporte para [Voice Chat](https://modrinth.com/plugin/simple-voice-chat) para hablar directamente desde el juego y [Distant Horizons](https://modrinth.com/mod/distanthorizons) para incrementar la distancia de renderizado.
- Aparte de los anteriores se **permite** el uso de mods de cliente y packs de texturas siempre que entren dentro de las **siguientes categorías**:
  - mods de optimización.
  - fullbright, `gamma:10.0`, no-fog, etc.
  - overlays de desgaste de armadura, tiempo restante de efectos, etc.
  - previews de shulker boxes.
- Quedan explícitamente **prohibidos** mods de tipo x-ray, mini-mapa, ESP, etc.
  Preguntar en caso de duda 😄.
- Se aplicarán normas básicas de comportamiento como por ejemplo: no destruir construcciones ajenas sin permiso, atacar a desconocidos, robar, máquinas de lag, etc.
  En cualquier caso nos reservamos el derecho de retirar acceso al servidor si consideramos que vuestro comportamiento está siendo negativo para el servidor o sus jugadores.

## ¿Cómo me conecto?

El servicio está reservado para miembros de la Escuela Politécnica Superior.
Para conectarte debes seguir los siguientes pasos:
1. Manda un correo electrónico desde tu **dirección institucional** (@\*.uam.es) a [whitelist.mc.ceeps@lima.sh](mailto:whitelist.mc.ceeps@lima.sh?subject=Whitelist%20MC%20EPS%20LIMA&body=IGN) con los siguientes datos:
    - asunto: `Whitelist MC EPS LIMA`,
    - cuerpo: `<nombre de usuario minecraft>`.
1. Espera medio minuto.
1. Ya puedes jugar a través de `mc.ceeps.lima.sh`.

**Nota:** el sistema de _whitelist_ por correo electrónico es automático, por lo que el cuerpo y asunto deben coincidir exactamente con lo especificado para que funcione 🤓.
También se comprueba la dirección del remitente para limitarlo a miembros de la comunidad.
_Usad únicamente el correo institucional_.

{{< notice >}}
Este servicio está actualmente en pruebas.
Estamos trabajando para mejorar las prestaciones de la máquina y los juegos que ofrecemos.
Por el momento el número máximo de jugadores concurrentes estará limitado a **20**.
{{< /notice >}}

## Detalles técnicos

- VPS: AMD EPYC CPU con 4 vCores @ 3.0GHz y 8GB RAM.
- Servidor fabric con mods de optimización detrás de un proxy velocity.
- Distancia de renderizado y procesado del servidor dinámica en función de la carga.

En caso de cualquier incidencia escribir a [lima.asociacion@uam.es](mailto:lima.asociacion@uam.es)

## Lista de cambios

- **26/02/2026**: apertura inicial del servidor.
- **01/03/2026**: implementación funcional de _whitelist_ automática y _mods_ VoiceChat y DistantHorizons para mejor experiencia de cliente.
- **13/03/2026**: eliminación de soporte para cuentas no-prémium por falta de demanda y excesiva complejidad de implementación con la _whitelist_ automática y sistema de inicio de sesión.

[← volver al inicio](/) \
[← volver a eventos](/eventos)
