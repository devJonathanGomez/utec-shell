# Basics

Ejercicios básicos de Shell y Bash. Los scripts practican comandos fundamentales para trabajar con directorios, archivos y enlaces simbólicos.

## Scripts

| Archivo                       | Descripción                                                                                                                                             |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `0-current_working_directory` | Muestra la ruta absoluta del directorio de trabajo actual.                                                                                              |
| `1-listit`                    | Muestra el contenido del directorio actual.                                                                                                             |
| `2-bring_me_home`             | Cambia el directorio de trabajo al directorio home del usuario.                                                                                         |
| `3-listfiles`                 | Muestra el contenido del directorio actual utilizando formato largo.                                                                                    |
| `4-listmorefiles`             | Muestra el contenido del directorio actual, incluidos los archivos ocultos, utilizando formato largo.                                                   |
| `5-listfilesdigitonly`        | Muestra el contenido del directorio actual, incluidos los archivos ocultos, en formato largo y utilizando identificadores numéricos de usuario y grupo. |
| `6-firstdirectory`            | Crea el directorio `my_first_directory` dentro de `/tmp`.                                                                                               |
| `7-movethatfile`              | Mueve el archivo `betty` desde `/tmp` hasta `/tmp/my_first_directory`.                                                                                  |
| `8-firstdelete`               | Elimina el archivo `betty` de `/tmp/my_first_directory`.                                                                                                |
| `9-firstdirdeletion`          | Elimina el directorio `/tmp/my_first_directory`.                                                                                                        |
| `10-back`                     | Cambia el directorio de trabajo al directorio anterior.                                                                                                 |
| `11-lists`                    | Muestra en formato largo los contenidos del directorio actual, su directorio padre y `/boot`, incluidos los archivos ocultos.                           |
| `12-file_type`                | Muestra el tipo del archivo `/tmp/iamafile`.                                                                                                            |
| `13-symbolic_link`            | Crea un enlace simbólico llamado `__ls__` que apunta a `/bin/ls`.                                                                                       |
| `14-copy_html`                | Copia al directorio padre los archivos `.html` nuevos o que no existan allí.                                                                            |
| `15-lets_move`                | Mueve al directorio `/tmp/u` los archivos cuyo nombre comienza con una letra mayúscula.                                                                 |
| `16-clean_emacs`              | Elimina los archivos del directorio actual cuyos nombres terminan en `~`.                                                                               |
| `17-tree`                     | Crea la estructura de directorios `welcome/to/school`.                                                                                                  |

## Entorno

Los scripts están diseñados para ejecutarse en:

* Ubuntu 22.04 LTS
* Bash

Los archivos utilizan `#!/bin/bash` como intérprete.
