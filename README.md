# GasPilot OTA

Repositorio público de actualizaciones de firmware para el dispositivo GasPilot.

## Archivos

- ersion.json — Manifiesto de versión actual
- irmware/ — Binarios compilados para OTA

## Uso

El dispositivo GasPilot consulta ersion.json en cada arranque.
Si detecta una versión nueva, notifica a la app móvil y espera confirmación del usuario.
