# comes-uclm.github.io

Página principal del grupo COMES para enlazar las webs de sus proyectos de investigación.

## Estructura

- `index.html`: portada y tarjetas de proyectos.
- `assets/css/style.css`: estilos de la portada.
- `assets/img/logo-comes.png`: logo del grupo COMES.
- `.nojekyll`: indica a GitHub Pages que publique los archivos estáticos sin procesarlos con Jekyll.

## Proyectos enlazados

- CORA → `/cora/`
- RENO → `/reno/`
- BISHEAR → `/bishear/`

Los repositorios de los proyectos deberían llamarse `cora`, `reno` y `bishear` para que sus URLs de GitHub Pages coincidan con estos enlaces.

## Añadir CARLA en el futuro

En `index.html` hay un comentario preparado al final de la sección `.projects`. Duplica una de las tarjetas y cambia:

```html
<a class="project-card" href="/carla/" aria-label="Acceder al proyecto CARLA">
  <span class="project-number">04</span>
  <div>
    <h2>CARLA</h2>
    <p>Proyecto de investigación</p>
  </div>
  <span class="arrow" aria-hidden="true">→</span>
</a>
```

## Publicación

El repositorio debe llamarse exactamente `comes-uclm.github.io` y pertenecer a la organización `COMES-UCLM`. En `Settings > Pages`, configura `Deploy from a branch`, rama `main` y carpeta `/(root)`.
