# Sitio Oficial Nuevo Lourdes

Esta es una guia basica para la edición y publicación de contenido en este sitio web, los resultados seran visibles en la siguiente URL https://nuevolourdes.github.io/.

## Obteniendo Archivos del Sitio

Para obtener los archivos del sitio para modificarlo, es necesario tener la ultima versión de `git` instalada en su computadora, a continuación se presentan guías para hacerlo en distintos sistemas operativos, el sistema recomendado es Ubuntu.

* Windows: [Descargar aquí](https://git-scm.com/download/win)
* Ubuntu: [Seguir guia](https://git-scm.com/book/es/v1/Empezando-Instalando-Git#Instalando-en-Linux)

Luego de seguir estos pasos, luego de instalar `git` deberíamos de tener una consola especial llamada `git Bash` en el caso de Windows, en Linux se puede utilizar la consola usual para los siguientes pasos, deberá ejecutar los siguientes comandos (cada $ es un comando distinto, no incluirlo al digitar los comandos):


``` bash
$ git clone https://github.com/nuevolourdes/sitio
$ cd sitio
$ git submodule add -b master \
https://github.com/nuevolourdes/nuevolourdes.github.io.git public
```

## Corriendo el servidor local

``` bash
$ hugo serve
```

Esto hara que podamos ver los resultados de nuestras ediciones antes de subir el resultado.


## Subiendo cambios

Subir los cambios es muy sencillo, solo se requiere ejecutar el siguiente comando:

``` bash
$ bash ./deploy.sh
```

## Más documentación

referirse a [este documento](./doc/reporte.pdf)
