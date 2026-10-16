# Infosolucions · Descargas

Instaladores oficiales y versiones estables de nuestras herramientas.

## [Abrir el centro de descargas](https://obielkenovi.github.io/Infosolucions-Descargas/)

Descarga pública y directa, sin cuenta de GitHub.

| Programa | Versión y sistema | Descarga |
| --- | --- | --- |
| **Movento Migrador** | 7.1.1 · Windows x64 | [**Descargar instalador**](https://github.com/Obielkenovi/Infosolucions-Descargas/releases/download/movento-migrador-v7.1.1/MoventoMigrador-Windows-x64-Setup.exe) · [Detalles](https://github.com/Obielkenovi/Infosolucions-Descargas/releases/tag/movento-migrador-v7.1.1) |

### Instalación

1. Descarga el instalador `.exe` desde el enlace de tu programa.
2. Ejecuta el asistente. No requiere permisos de administrador.
3. Abre Movento Migrador desde Inicio; su interfaz se abre en el navegador local.

Cierra el programa y guarda una copia privada de tus datos antes de actualizar.
La desinstalación conserva los datos en `%LOCALAPPDATA%\MoventoMigrador`.
El instalador actual no tiene firma Authenticode; Windows puede indicar editor desconocido.
La distribución comienza sin inventario ni credenciales. Configura tus sedes y perfiles.

### Versiones e integridad

Cada programa dispone de sus propias releases `programa-vX.Y.Z`, instalador,
`SHA256SUMS.txt` y `manifest.json`. [Consultar todas las versiones](https://github.com/Obielkenovi/Infosolucions-Descargas/releases).
Para comprobar un archivo en PowerShell: `Get-FileHash .\MoventoMigrador-Windows-x64-Setup.exe -Algorithm SHA256`.

Este repositorio contiene únicamente instaladores e información de distribución.
Los archivos «Source code» generados por GitHub contienen esta información pública;
no contienen el código fuente de las aplicaciones y no son el instalador.

Las futuras versiones estables se publican mediante el proceso privado de construcción,
pruebas Windows y verificación de integridad. El catálogo y esta portada se actualizan
por programa; las versiones anteriores conservan sus enlaces.
