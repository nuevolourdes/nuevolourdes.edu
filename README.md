# Sitio Oficial Nuevo Lourdes

Esta es una guia basica para la edición y publicación de contenido en este sitio web, los resultados seran visibles en la siguiente URL https://nuevolourdes.github.io/sitio/.

## Obteniendo Archivos del Sitio

Para obtener los archivos del sitio para modificarlo, es necesario tener la ultima versión de `git` instalada en su computadora, a continuación se presentan guías para hacerlo en distintos sistemas operativos, el sistema recomendado es Ubuntu.

* Windows: [Descargar aquí](https://git-scm.com/download/win)
* Ubuntu: [Seguir guia](https://git-scm.com/book/es/v1/Empezando-Instalando-Git#Instalando-en-Linux)

Luego de seguir estos pasos, luego de instalar `git` deberíamos de tener una consola especial llamada `git Bash` en el caso de Windows, en Linux se puede utilizar la consola usual para los siguientes pasos, deberá ejecutar los siguientes comandos (cada linea es un comando distinto):


``` bash
git clone https://github.com/nuevolourdes/sitio
```

Luego de eso, se tendrá un folder cuya estructura se verá parecida a lo siguiente:

``` 
├── archetypes
│   └── default.md
├── config.toml
├── content
│   ├── acercade.md
│   └── noticias
│       ├── entreganotas.md
│       ├── intramuros.md
│       └── nuevopost.md
├── data
│   ├── carousel
│   │   ├── confiable.yaml
│   │   └── valores.yaml
│   └── features
│       ├── ambiente.yaml
│       ├── educacion.yaml
│       └── valores.yaml
├── layouts
    └── shortcodes
        └── md.html
```

