---
layout: blog
title: '**Hemos cambiado el código**'
date: 2020-02-02T02:49:48.510Z
---
**Hemos cambiado el código predete**rminado de Sapper de dos maneras:

1. Buscamos texto del servidor en lugar de JSON
2. Dividimos ese texto en metadatos y contenido, y renderizamos el contenido.

Cuando volvemos a unir los metadatos y el contenido, pasamos al resto del componente Svelte los mismos datos que esperaba obtener de la`[slug].json.js`ruta del servidor anterior, ¡y ahora todo se procesa!

![ensalada](/uploads/ensalada.jpg "tomaco")
