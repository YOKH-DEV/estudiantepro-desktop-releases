# Descargas de EstudiantePro Desktop

Este repositorio público contiene solo instaladores versionados y el manifiesto firmado del canal estable. El código fuente del producto vive en un repositorio privado separado.

## Descarga

La página de EstudiantePro mostrará los instaladores disponibles para cada sistema operativo. El archivo `stable.json` contiene el catálogo vigente para el actualizador de Windows y Ubuntu/Debian.

El actualizador verifica la firma Ed25519 del manifiesto y el tamaño y SHA-256 del instalador antes de aplicar una nueva versión. La huella SHA-256 de la clave pública de este canal es `20671a6abee010fbbc5ed58d9d19c2d419b7287e8e06a736cce645f1d6d599d9`.

macOS requiere un instalador probado y firmado antes de ofrecerlo como descarga general. Las versiones antiguas que no contienen la URL de este canal necesitan una instalación manual inicial.

## Archivos

- `stable.json`: manifiesto firmado que se actualiza solo después de subir y comprobar los instaladores de la versión nueva.
- Releases `vX.Y.Z`: instaladores inmutables y sus sumas SHA-256.

No se guardan claves privadas, sesiones ni datos de usuarios aquí.
