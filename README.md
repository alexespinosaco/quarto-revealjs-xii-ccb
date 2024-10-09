# Quarto Revealjs XII Congrego Colombiano de Botánica theme

Una extensión de [Quarto](https://quarto.org) para crear presentaciones Reveal.js para el [XII Congreso Colombiano de Botánica](http://congresobotanica.org) hecha por [Álex Espinosa-Correa](https://alexespinosaco.github.io) basada en la presentación sugerida por los organizadores.

## Instalación

### En un proyecto nuevo

En la terminal ejecute:

```bash
quarto use template alexespinosaco/quarto-revealjs-xii-ccb
```

Esto instalará la extensión y creará varios archivos: 
-  `_extesion`: carpeta donde se instala la extesión.
-  `*.qmd`: archivo que puede utilizar como punto de partida para su presentación.
-  `*.Rproj`: archivo de configuración de los proyectos de RStudio. 

#### ¡Importante!

Si está usando el `*.qmd` proporcionado como ejemplo, para el correcto renderizado de este, es **muy importante** que dentro de la carpeta `_extesion` mueva la carpeta `xii-ccb` fuera de la carpeta `alexespinosaco`.

### En un proyecto existente

Desde el directorio del proyecto o documento Quarto, ejecute el siguiente comando:

```bash
quarto add alexespinosaco/quarto-revealjs-xii-ccb
```

Este formato puede ser utilizado con un proyecto o documento Quarto existente. Esto instalará sólo los archivos en la carpeta `_extension` y no instalará los archivos por encima de eso (los archivos de demostración). Esta es también la forma de actualizar la extensión si ha habido cambios.

```bash
quarto add alexespinosaco/quarto-revealjs-xii-ccb
```

Ahora puede usar `xii-ccb-revealjs` como formato:

```yml
---
title: "XII Congreso Colombiano de Botánica"
author: "Álex Espinosa-Correa"
format: xii-ccb-revealjs:
---
````

## Más información

-  [Guía de Quarto para presentaciones en Revealjs](https://quarto.org/docs/presentations/revealjs/)
-  [Guía de Quarto para formatos personalizados](https://quarto.org/docs/extensions/formats.html)
