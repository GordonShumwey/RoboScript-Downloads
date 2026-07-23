# RoboScript — Descargas oficiales

Este repositorio público contiene exclusivamente las **versiones descargables oficiales de RoboScript**, la aplicación educativa del proyecto **El Origen**.

El código fuente y el historial de desarrollo no se publican en este repositorio.

## RoboScript

RoboScript es una aplicación para diseñar, ejecutar y analizar actividades de pensamiento computacional mediante un robot que se desplaza sobre un tablero. Utiliza **BotScript 1.3**, el lenguaje educativo del proyecto.

## Descarga

Las versiones oficiales se publican en la sección **Releases** de este repositorio.

Cada versión incluye:

- paquete portable para Windows de 64 bits;
- archivo SHA-256 para verificar la integridad de la descarga;
- licencia de uso de RoboScript;
- avisos y licencias de componentes de terceros.

## Instalación

RoboScript no requiere instalación ni Python en el computador de destino.

1. Descarga el archivo ZIP desde Releases.
2. Descomprime el contenido completo en una carpeta con permisos de escritura.
3. Conserva juntos todos los archivos y carpetas incluidos.
4. Ejecuta `RoboScript.exe`.

No ejecutes el programa directamente desde el ZIP.

## Uso gratuito

RoboScript puede utilizarse gratuitamente con fines personales, educativos e institucionales conforme a la [Licencia de uso](LICENCIA_DE_USO_ROBOSCRIPT.txt).

La gratuidad no implica que RoboScript sea software de código abierto. Los componentes de terceros conservan sus propias licencias.

## Componentes de terceros

RoboScript utiliza Python, Qt for Python/PySide6, Shiboken6 y otros componentes. Sus condiciones se describen en [Avisos y licencias de terceros](AVISOS_Y_LICENCIAS_DE_TERCEROS.txt).

## Integridad de las descargas

Para comprobar el archivo descargado en PowerShell:

```powershell
Get-FileHash .\RoboScript_1.7.0_Windows_x64.zip -Algorithm SHA256
```

El resultado debe coincidir con el archivo `.sha256.txt` publicado junto a la versión.

## Limitación visual conocida

En algunas configuraciones de baja resolución o escalado elevado de Windows, ciertos elementos pueden superponerse. Esto no afecta el motor BotScript ni la ejecución de los ejercicios.

## Proyecto El Origen

**Piensa. Diseña. Resuelve.**
