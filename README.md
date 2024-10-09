# Quarto Revealjs XII Congrego Colombiano de Botánica theme

Una extensión [Quarto](https://quarto.org) para crear presentaciones Reveal.js para el [XII Congreso Colombiano de Botánica](http://congresobotanica.org) hecha por [Álex Espinosa-Correa](https://alexespinosaco.github.io)

## Instalación

```bash
quarto use template alexespinosaco/quarto-revealjs-xii-ccb
```

Esto instalará la extensión y creará un archivo qmd de ejemplo que puede utilizar como punto de partida para su presentación.

También puedes utilizar este formato con un proyecto o documento Quarto existente. Esto instalará sólo los archivos en la carpeta `_extension` y no instalará los archivos por encima de eso (los archivos de demostración). Esta es también la forma de actualizar la extensión si ha habido cambios.

Desde el directorio del proyecto o documento Quarto, ejecute el siguiente comando:

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

