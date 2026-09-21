# utec-shell

Repositorio de ejercicios de Shell realizados en Ubuntu 22.04 LTS.

## permissions

Scripts relacionados con permisos, propietarios, grupos y usuarios en Linux.

| Script                         | Descripción                                                                                                                         |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------- |
| `0-iam_betty`                  | Cambia el usuario actual al usuario `betty`.                                                                                        |
| `1-who_am_i`                   | Imprime el nombre del usuario efectivo actual.                                                                                      |
| `2-groups`                     | Imprime todos los grupos a los que pertenece el usuario actual.                                                                     |
| `3-new_owner`                  | Cambia el propietario del archivo `hello` al usuario `betty`.                                                                       |
| `4-empty`                      | Crea un archivo vacío llamado `hello`.                                                                                              |
| `5-execute`                    | Agrega permiso de ejecución al propietario del archivo `hello`.                                                                     |
| `6-multiple_permissions`       | Agrega permisos de ejecución al propietario y al grupo, y permiso de lectura a otros usuarios en `hello`.                           |
| `7-everybody`                  | Agrega permiso de ejecución al propietario, al grupo y a otros usuarios en `hello`.                                                 |
| `8-James_Bond`                 | Establece los permisos de `hello` para que el propietario y el grupo no tengan permisos y otros usuarios tengan todos los permisos. |
| `9-John_Doe`                   | Establece los permisos de `hello` a `-rwxr-x-wx`.                                                                                   |
| `10-mirror_permissions`        | Hace que `hello` tenga los mismos permisos que el archivo `olleh`.                                                                  |
| `11-directories_permissions`   | Agrega permiso de ejecución a todos los subdirectorios del directorio actual sin modificar los archivos regulares.                  |
| `12-directory_permissions`     | Crea el directorio `my_dir` con permisos `751`.                                                                                     |
| `13-change_group`              | Cambia el grupo propietario del archivo `hello` a `school`.                                                                         |
| `14-change_owner_and_group`    | Cambia el propietario a `vincent` y el grupo a `staff` de los archivos y directorios del directorio actual.                         |
| `15-symbolic_link_permissions` | Cambia el propietario y grupo propietario del enlace simbólico `_hello` a `vincent` y `staff`.                                      |
| `16-if_only`                   | Cambia el propietario de `hello` a `vincent` únicamente si su propietario actual es `guillaume`.                                    |
