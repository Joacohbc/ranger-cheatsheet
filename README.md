# Ranger Cheatsheet

Aquí unos cuantos shortcuts y comandos de Ranger que son los que encuentro más útiles

**_Referencias:_**

Dentro de `esto` -> Click en esta tecla

Fuera de `esto` -> Escribir lo ingresado

Letras en mayúscula -> `Shift`+Letra

## Schorcuts

### Moverse

| **Comando**  | **Sub-comando** | **Funcion**                                                        |
| ------------ | --------------- | ------------------------------------------------------------------ |
| m + `tecla`  | -               | Crea un bookmark del directorio actual con la tecla seleccionada   |
| um + `tecla` | -               | Borrar un bookmark que se indique con la siguiente tecla           |
| \` + `tecla` | -               | Ir al bookmarks que se indique con la siguiente tecla              |
| \`           | \`              | Ir al directorio anterior en que estuviste                         |
| gg           | -               | Ir al principio                                                    |
| G            | -               | Ir al final                                                        |
| g            | h               | Ir a $HOME                                                         |
| k            | -               | Moverse hacia arriba                                               |
| j            | -               | Moverse hacia abajo                                                |
| h            | -               | Moverse hacia el directorio padre (hacia atras)                    |
| l            | -               | Moverse hacia el subdirectorio o abrir archivo (hacia adelante)    |
| `Flechitas`  | -               | Moverse entre directorios hacia arriba, abajo, izquierda y derecha |

### Tabs

| **Comando** | **Sub-comando**   | **Funcion**                |
| ----------- | ----------------- | -------------------------- |
| g           | T (`Shift`+`Tab`) | Moverse a la anterior tab  |
|             | t (`Tab`)         | Moverse a la siguiente tab |
|             | n                 | Nueva tab                  |
|             | c                 | Cerrar tab                 |
| ut          | -                 | Restaurar una Tab          |

### Seleccionar

| **Comando** | **Sub-comando** | **Funcion**                      |
| ----------- | --------------- | -------------------------------- |
| `Espacio`   | -               | Marcar archivos para usarlos     |
| v           | -               | Seleccionar / Deseleccionar todo |

### Copiar

| **Comando** | **Sub-comando** | **Funcion**                                                          |
| ----------- | --------------- | -------------------------------------------------------------------- |
| y           | y               | Copiar archivo                                                       |
|             | t               | Activar/ Desactivar el copiado                                       |
|             | d               | Copiar ruta del directorio actual                                    |
|             | p               | Copiar ruta del archivo                                              |
|             | n               | Copiar nombre del archivo                                            |
|             | .               | Copiar nombre sin extensión                                          |
|             | gg              | Activar/ Desactivar el copiado sobre todos los archivos hacia arriba |
|             | G               | Activar/ Desactivar el copiado sobre todos los archivos hacia abajo  |

### Cortar

| **Comando** | **Sub-comando** | **Funcion**                                                          |
| ----------- | --------------- | -------------------------------------------------------------------- |
| d           | d               | Cortar archivo                                                       |
|             | t               | Activar/ Desactivar el cortado                                       |
|             | gg              | Activar/ Desactivar el cortado sobre todos los archivos hacia arriba |
|             | G               | Activar/ Desactivar el cortado sobre todos los archivos hacia abajo  |

### Pegar

| **Comando** | **Sub-comando** | **Funcion**             |
| ----------- | --------------- | ----------------------- |
| p           | p               | Pecar archivo           |
|             | P               | Pegar sin sobreescribir |
|             | o               | Pegar sobreescribiendo  |
|             | r               | Pegar como root         |

### Ordenar

| **Comando** | **Sub-comando** | **Funcion**                                    |
| ----------- | --------------- | ---------------------------------------------- |
| o           | n / N           | Por Nombre completo de A → Z / Z → A           |
|             | a / A           | Por Modificacion Nuevo → Viejo / Viejo → Nuevo |
|             | e / E           | Por Extensión de A → Z / Z → A                 |
|             | s / S           | Por Peso de Pesado → Ligero / Ligero → Pesado  |

### Borrar

| **Comando** | **Sub-comando** | **Funcion**                      |
| ----------- | --------------- | -------------------------------- |
| dD          | -               | Borrar archivo (permanentemente) |
| dT          | -               | Mandar a papelera                |

### Otros

| **Comando** | **Sub-comando** | **Funcion**                                                      |
| ----------- | --------------- | ---------------------------------------------------------------- |
| du          | –               | Ver peso de los archivos del directorio                          |
| dU          | -               | Ver peso de los archivos del directorio (Ordenado)               |
| dc          | -               | Ver peso del directorio seleccionado                             |
| S           | -               | Abrir consola en el directorio actual                            |
| a / `F2`    | -               | Renombrar archivo                                                |
| `Ctrl`      | H               | Mostrar / Ocultar archivos ocultos                               |
| ~           | -               | Cambiar la perspectiva (Mostrar +Tab o solo una al mismo tiempo) |
| /           | -               | Buscar un fichero por texto                                      |

## Comandos

| **Comando**        | **Funcion**                               |
| ------------------ | ----------------------------------------- |
| :shell / !         | Ejecutar un comando de Shell              |
| :rename / `F2`     | Cambiar nombre del archivo seleccionado   |
| :delete / `Delete` | Borrar permanentemente                    |
| :trash             | Manda a la papelera                       |
| :edit              | Abre el archivo especificado en el editor |
| :mkdir             | Crear directorio                          |
| :terminal          | Abre un terminal en el directorio actual  |
| :search            | Buscar un fichero por texto               |
