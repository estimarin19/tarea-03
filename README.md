# Las ASADAS de Costa Rica en el padrón de ARESEP: distribución territorial, condiciones de operación, completitud del registro y análisis geoespacial

**Estibadiz Marin Morales**  
Tarea 3 · PF-0953 Programación en R · II ciclo lectivo 2026  
Programa de Posgrado en Geografía, Universidad de Costa Rica

**Documento publicado:** <https://estimarin19.github.io/tarea-03/>

## Contenido del repositorio

- `index.qmd`: documento Quarto con el texto y el código en R.
- `index.html`: documento procesado con *Render* (`embed-resources: true`).
- `asadas_aresep.csv`: conjunto de datos abiertos *Acueducto comunales (ASADAS)* de la Autoridad Reguladora de los Servicios Públicos (ARESEP, 2019; licencia CC BY-SA 4.0), exportado en formato CSV desde <https://aresep.go.cr/datos-abiertos/acueducto-comunales-asadas/> el 3 de setiembre de 2026. El documento lo lee desde la URL *Raw* de este repositorio y construye con sus coordenadas CRTM05 la capa de puntos de las ASADAS.

Las capas de cantones y provincias del Instituto Geográfico Nacional (IGN, 1:5 000) y los datos de población por cantón (INEC, 2023) se leen por URL desde el repositorio del [sitio del curso](https://pf0953-programacionr.github.io/2026-ii/).

Este trabajo continúa la [tarea 1](https://estimarin19.github.io/tarea-01/), en la que se describieron el tema y los datos, y la [tarea 2](https://estimarin19.github.io/tarea-02/), con las tablas y los gráficos del padrón.
