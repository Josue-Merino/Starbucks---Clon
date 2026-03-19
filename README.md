# PROYECTO MODULO 2 BÉCALOS - STARBUCKS CLON
Descripción: Como proyecto del Módulo 2 del Becalos Tech Challenge se dejo como proyecto hacer un clon de la página de Starbucks México.
Este repositorio contiene los archivos que sirvieron para el desarrollo del proyecto así como una pequeña bitácora donde se resgistro los cambios más significativos al momento de su desarrollo.

[Visita la Demo](https://josue-merino.github.io/Starbucks---Clon/)

## Lista de avances del proyecto

### ACTIVIDAD 03
Creación de la página Home en donde se realizo: 
- Se estructuro la página del home mediante HTML.
- Se colocaron los links de cada imagen del home page
- Se creo el archivo app.css y se definieron los estilos básicos como el css reset y variables.

### ACTIVIDAD 04
Se continuo realizando la página princiapl de Starbucks donde se uso Flexbox y Grid para: 
- Definir la estructura de la Navbar.
- Alinear elementos dentro de la Navbar.
- Alinear imágenes, texto y títulos dentro de cada sección.
- Se logro realizar terminar el contenido y se quedo por realizar el footer de la página.

#### ACTIVIDAD 05
Se termino el footer de la pagina principal de esta forma se acabo la página principal solo quedando hacerla responsiva y se hizo la estructura de la siguiente página que es la de rewards:
- Se uso Flexbox y Grid para alinear elementos dentro del footer y definir su layout
- En la Paǵina de rewards se uso grid para definir la estructura del sitio definiendo el aside del sitio que permanecerá fijo y la columna del contenido con scroll.

### ACTIVIDAD 06
Se uso position para implementar el hover en el navbar y se termino la página de rewards donde: 
- Se uso Grid en la mayoría del sitio para definir columnas en cada sección del sitio.
- Se definieron nuevas variables para uso de colores
- Se descargarón las imaganes ya que en algunos casos al iniciar la visat previa no cargaban las imágenes.
- Uso se position y el pseudo elemento after para el hover de los links en el navbar.
- Al terminar la página se encontraron conflictos del layout en otros tamaños de pantalla

### ACTIVIDAD 07
Aquí se realizo la parte más complicada ya que se solucionaron conflictos en el diseño en los distintos tamaños de pantalla usando el enfoque Desktop - first y se termino la página del Menú ya responsiva con enfoque Mobile - first:

- Se comenzo con el diseño responsivo de la página principal donde los cambios mas relevantes fueron el uso de grid template areas para cambiar el orden de imágenes y texto al cambiar a tamaño mobile
- Se aplico el uso de media queries para cambiar tamaño de imágenes, texto y alineación de elemntos como en el footer.
- En la Página de rewards se ajusto la altura del contenedor de dos columnas para que en pantallas grandes siempre tuviese el 100vh y no tuviear scroll, se evito el conflicto entre el navabr y el contenedor antes mencionado para evitar que fuese empujado por el navbar.
- En la mayoria de secciones de la página de rewards se cambio el flujo del layout a una columna para que todo se acomodará en ese orden.
- Se creo la página de del Menú donde se uso el enfoque Mobile - first ya que considero así es mas fácil aplicar los media queries.

### ACTIVIDAD 08 
En la parte final del proyecto se realizaron grandes cambios donde los pricipales destacan solucion de confilctos en el diseño responsivo, organización de archivos y su contenido y terminar el login y registro del clon.

- Se uso correctamente @import de css para separar variables globales y estilos del navbar y el footer.
- Se separó por archivo los estilos de cada página permitiendo una mejor organización y uso de estilos globales importandolos desde el global css.
- Se corriegieron pequeños detalles en el diseño como reemplazo de clases y eliminación de clases, se agruparon algunas reglas que se repetian y se ajustaron los media queries para que fuesen consistentes con el Mobile - first y el Desktop - First.
- Se termino la página del Login junto con su diseño responsivo.
- Se termino la página del Registro junto con su diseño responsivo.