# MatchDesk

Monitorización de conexión, overlay e información de partidos de eFootball para Windows y Android.

[Português](README.md) · [English](README.en-US.md) · [Español](README.es-ES.md)

[Sitio oficial](https://mixdev-br.github.io/MatchDesk/) · [Descargas](DOWNLOADS.md#español) · [Soporte](SUPPORT.md#español)

## Estamos preparando algo nuevo

MatchDesk está adoptando su nueva identidad. Las nuevas versiones de las aplicaciones siguen en preparación. El sitio completo se publicará junto con las aplicaciones actualizadas; hasta entonces, la dirección oficial muestra un avance.

**Todavía no hay paquetes MatchDesk disponibles en este repositorio.** Las publicaciones y descargas de las marcas anteriores se han retirado. Consulta [Descargas y disponibilidad](DOWNLOADS.md#español) para conocer el estado de la distribución oficial.

## Aplicaciones

| Aplicación | Plataforma | Finalidad |
| --- | --- | --- |
| **MatchDesk Pro** | Windows 10/11, 64 bits | Monitor de conexión, overlay, central de servidores, regiones e historial de partidos. |
| **MatchDesk Scout** | Windows 10/11, 64 bits | Información disponible del rival y del partido, como aplicación independiente o integrada en Pro. |
| **MatchDesk Mobile** | Android con router OpenWrt compatible | Monitorización de un PC, PlayStation o Xbox en la red local, usando el móvil como panel. |
| **MatchDesk Trial** | Windows 10/11, 64 bits | Edición de evaluación de la aplicación principal. La disponibilidad y las condiciones se anunciarán con su publicación. |

En PC se contempla eFootball para Steam y Xbox PC. Consulta las notas de cada versión para comprobar funciones, requisitos y compatibilidad. Scout funciona exclusivamente en Windows; la monitorización de consolas requiere Mobile y un router compatible.

## Antes de instalar

- La captura directa de red en Windows con Pro utiliza [Npcap](https://npcap.com/#download), instalado desde su fuente oficial. Scout no necesita Npcap.
- Mobile requiere un router con OpenWrt. El firmware original del fabricante no es suficiente. Consulta la [guía de configuración en portugués](OPENWRT_MOBILE_GUIDE.md).
- Las ediciones comerciales requieren la licencia correspondiente. La licencia de una aplicación no concede automáticamente acceso a las demás.
- Sigue las instrucciones del paquete publicado y extrae todo el contenido de los archivos ZIP.

La aplicación muestra los datos que facilitan la sesión y la plataforma. Las mediciones de latencia, las estimaciones de ubicación y la identificación de rivales tienen limitaciones; seleccionar una región no garantiza un resultado del matchmaking.

## Descargas y actualizaciones

Las nuevas versiones se publicarán mediante los canales oficiales de [DOWNLOADS.md](DOWNLOADS.md#español), con versión, plataforma, notas e información de integridad. No utilices copias de terceros ni archivos renombrados para aparentar una nueva versión.

Durante la transición, el manifiesto de actualización de las versiones retiradas deja de publicarse. La ausencia de un manifiesto no significa que haya una nueva versión disponible.

## Ayuda y seguridad

- [Soporte y diagnóstico](SUPPORT.md#español)
- [Guía de Mobile y OpenWrt en portugués](OPENWRT_MOBILE_GUIDE.md)
- [Comunicar un problema](https://github.com/MixDev-br/MatchDesk/issues/new/choose)
- [Comunicar una vulnerabilidad en privado](SECURITY.md)
- [Historial público](CHANGELOG.md)

No publiques claves de licencia, contraseñas, tokens, códigos completos de dispositivo ni capturas con datos personales. Los canales de soporte existentes siguen disponibles durante la transición.

## Sobre este repositorio

Este es el repositorio público de documentación y distribución de MatchDesk, mantenido por MixDev. El código fuente de las aplicaciones es propietario y no se publica aquí. El uso de las aplicaciones se rige por los términos incluidos con cada producto; el acceso público a este repositorio no concede una licencia de código abierto.

MatchDesk es un proyecto independiente, sin afiliación, patrocinio ni aprobación de KONAMI. eFootball y las demás marcas citadas pertenecen a sus respectivos titulares.
