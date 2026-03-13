+++
date = '2025-09-30T14:50:38+01:00'
draft = false
title = 'Mirror de Archlinux'
[params]
    subtitle = 'Servicio especial para los usuarios de ArchLinux de España'
+++

Gracias a la colaboración de la Escuela Politécnica Superior, desde la **Asociación LIMA** 🍋‍🟩 ofrecemos un servicio de _mirror_ de paquetes de ArchLinux colocalizado dentro de la red institucional de la Universidad Autónoma de Madrid.

Esto significa que cualquier usuario en la zona geográfica general de Madrid y los alrededores podrá disfrutar de una velocidad de descarga rápida a la hora de actualizar su sistema ArchLinux.
Espacialmente aquellos dentro de la red institucional de la UAM.

## ¿Cómo lo uso?

Añade la siguiente línea al principio del archivo `/etc/pacman.d/mirrorlist`:
```
Server = https://lima.ii.uam.es/mirror/archlinux/$repo/os/$arch
```

Podéis consultar más información sobre el funcionamiento de _Pacman_ y _mirrors_ en la página de la [ArchWiki](https://wiki.archlinux.org/title/Pacman).

{{< notice >}}
Este servicio está actualmente en **pruebas**, puede que haya caídas momentáneas inesperadas.
Se avisará siempre con antelación a la hora de programar y realizar mantenimiento periódico.
{{< /notice >}}

[← volver al inicio](/) \
[← volver a eventos](/eventos)
