Análisis Técnico del Proyecto
El código se divide en dos capas fundamentales: Estructura Semántica (HTML) y Capa de Presentación (CSS). Esta separación permite una gestión eficiente del contenido y el diseño de forma independiente.
1. Estructura de Contenidos (HTML)
El documento está organizado en dos bloques principales de información:
Bloque de Encabezado:
Contiene la jerarquía principal del documento mediante etiquetas de encabezado (h1 y h2).
Utiliza identificadores únicos (id) para establecer una relación directa con las reglas de estilo.
Incluye un elemento de párrafo (p) destinado a texto informativo o descriptivo.
Pie de Página (footer):
Se estructura mediante tres contenedores div que agrupan información temática: Contacto, Servicios y Tecnologías.
El uso de la clase común pie_de_pagina en los contenedores permite aplicar estilos uniformes a las tres columnas de contenido.
2. Capa de Estilo y Maquetación (CSS)
La presentación visual se rige por principios de jerarquía y distribución de espacio:
Tipografía y Alineación:
Se implementa la familia de fuentes sans-serif (Arial/Helvetica) para mejorar la legibilidad en pantallas.
Los elementos identificados como titulo y subtitulo reciben una alineación centrada y pesos de fuente en negrita (bold) para enfatizar su importancia.
Modelo de Caja y Flexibilidad (Flexbox):
El elemento footer actúa como un contenedor flexible (display: flex).
La propiedad justify-content: space-evenly distribuye las columnas de manera proporcional a lo ancho de la pantalla, garantizando un equilibrio visual automático.
Se define un esquema de color de alto contraste con un fondo oscuro (#242323) y tipografía clara (#ffff), optimizando la visibilidad.
