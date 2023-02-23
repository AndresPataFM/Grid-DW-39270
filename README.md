# Grids

Este repo contiene ejemplso básicos de grids, para propiedades más avanzadas revisen los siguientes links:

* [Grids y media Queries](https://docs.google.com/document/d/1zpaCVrb6dCQ8odArg2EGkNapyFmkLO_mnnvYqbekqFw/edit?usp=sharing)
* [CSS-Tricks Grids](https://css-tricks.com/snippets/css/complete-guide-grid/)
* [W3Schools Grids](https://www.w3schools.com/css/css_grid.asp)
* [Mozilla Grids](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout)

## Requerimientos
Grids requiere de un contenedor padre con hijos
se le aplica grids al padre para ordenar a los hijos

## Propiedades del padre

*esencial*
* display: grid;

*configurar columnas/filas*
* grid-template-columns
* grid-template-rows
* grid-auto-columns
* grid-auto-rows

*posicionar celdas*
* grid-template-area

*espacio entre celdas*
* column-gap
* row-gap
* gap

*posicionar el grid en totalidad (necesita que sobre espacio)*
* justify-content
* align-content
* place-content

*posicionar la celda con el espacio de la celda (necesita que la celda sea más grande que su contenido)*
* justify-items
* align-items
* place-items

## Propiedades Hijo

*posicionar columna*
* grid-column-start
* grid-column-end
* grid-column

*posicionar fila*
* grid-row-start
* grid-row-end
* grid-row

*grid area, permite agregar nombre y grid-column y grid-row*
* grid-area

*posicionar*
* justfy-self
* align-self
* place self