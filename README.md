# Ejercicios básicos de CSS

Abre cada HTML con Live Server. Compara tu resultado con las imágenes de referencia y prueba distintas clases y propiedades CSS. 
Mira [este vídeo](https://oscarm.tinytake.com/msc/ODcxODgxN18yMjExNTExNg) para ver el diseñó de cómo debe quedar todo. Pon el audio. Nota: el vídeo contiene algunos ejercicios que ya no están, pero no importa, la explicación es útil para los demás ejercicios.

| Ejercicio | Diseño esperado | Colores aproximados de la captura |
|---|---|---|
| [Currículum vitae](1-curriculum-vitae-plantilla/curriculum-vitae.html) | [Ver imagen](cv-vitae.png): título grande, centrado y en mayúsculas; fondo gris azulado; apartados con barras azul grisáceas subrayadas; datos e instituciones azules; pie blanco alineado a la derecha. | Fondo `#d7dfe3`, barra `#809ba8`, bloque `#b9c9d0`, texto oscuro `#333333`, dato `#006da5`, entidad `#008bd1`, pie `#ffffff`. |
| [Greguerías](3-greguerias-1-plantilla/greguerias-1.html) | [Ver imagen](greguerias.png): fondo verde; título negro grande; ocho frases separadas verticalmente con tipografías y colores alternos. | Fondo `#258b50`, título `#000000`, blanco `#ffffff`, crema `#ffdbac`, naranja `#ff9b16`, rosa `#ff285e`. |
| [Películas con emojis](4-emoji-peliculas-plantilla/emoji-peliculas.html) | [Ver imagen](peliculas.png): fondo crema; título marrón en mayúsculas; pregunta naranja; cinco filas de emojis precedidas por un triángulo negro y con fondos rosa y blanco alternos. | Fondo `#ffebce`, título `#995900`, pregunta `#ff8c00`, rosa `#ffc9e9`, blanco `#ffffff`, negro `#000000`. |

Los códigos de color son aproximaciones de las capturas: pueden variar según pantalla, navegador y fuente de emojis. En Greguerías, las fuentes exactas no son obligatorias.

## Recursos W3Schools: enlaces directos «Try it»

- [Clases CSS: aplica un estilo a varios elementos](https://www.w3schools.com/cssref/tryit.php?filename=trycss_sel_class)
- [Atributo `class` en HTML](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_classes_css)
- [Color de fondo de la página](https://www.w3schools.com/css/tryit.asp?filename=trycss_background-color_body)
- [Color de fondo de elementos](https://www.w3schools.com/css/tryit.asp?filename=trycss_background-color_elements)
- [Nombres de colores CSS](https://www.w3schools.com/css/tryit.asp?filename=trycss_colors_names)

## Etiquetas HTML útiles

- `header` para la cabecera y `main` para el contenido principal.
- `section` con `h2` para cada apartado del currículum; `footer` para autor y fecha.
- `h1` para el título de cada página; `h2` y `h3` para subtítulos.
- `p` para la introducción y cada greguería; `span` con una clase para destacar partes de una línea.
- `ul` y `li` para las cinco películas; cada fila representa un elemento de la lista.
- `article` si se desea presentar una greguería como pieza independiente.

No hace falta usar todas las etiquetas. Escoge las que describan el contenido y añade clases donde necesites compartir un estilo.
