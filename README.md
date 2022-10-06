# Bienvenidos 👋👋!!! 

## **Amasijos Tradicionales de Colombia**
La página web se enfoca principalmente en informar a la comunidad todo lo relacionado con los amasijos tradicionales en Colombia que son un manjar para los colombianos, primordialmente se describe el significado de la palabra amasijo y la historia de cada producto que lo denomina. Además, se da una pequeña receta de cada amasijo tradicional para realizar la preparación en casa. Finalmente, se desarrolla un espacio para que los usuarios puedan interactuar mecho mejor con la página y comentar sobre que tal le pareció la receta o como tal la página. 
#### ***Puedes visualizar la página*** 👉👉 https://jhonattanssg01.github.io/AmasijosTradicionales/

## Inicio del proyecto 💢

Principalmente, se inició clonando el repositorio de GitHub donde se alojaba una plantilla guía de HTML para lograr desarrollar nuestra web tributo con base en esa plantilla.
### 	El comando en Git para clonar el repositorio es $ git clone <URL del repositorio a clonar> 📥

Luego de revisar la estructura propuesta de la plantilla, logre entender que se manejó mediante una librería la cual era W3School para dar una mejor visualización acorde. De igual manera, decidí cambiarla por la librería Bootstrap la cual ya tengo un poco de experiencia en utilizarla.

# Estructura de HTML 💯
## Head del documento HTML 🔹
```
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- Importamos recursos externos -->
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open Sans">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT" crossorigin="anonymous">
  <!-- Importamos recurso css para los estilos-->
  <link rel="stylesheet" href="css/index.css">
  <link rel="stylesheet" href="fontawesome-free-6.2.0-web/css/all.css">
  <link rel="shortcut icon" href="img/logoPestaña.png" type="image/x-icon">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
  <title>Amasijos Tradicionales</title>
</head>
```
Prácticamente en esta parte del código se importan los diferentes recursos que se utilizaron durante la construcción de la página web tributo, los recursos que se utilizaron fueron la fuente de Google Fonts, la librería Bootstrap para algunas funcionalidades, la ruta local de los estilos de la página web, la ruta local de los iconos descargados de Font-awesome y por último agregando el logo y título en la parte de la pestaña.

## Header del documento HTML 🔸
```
<!-- START Boostrap -->
  <div class="part-body container p-0" style="max-width:100%;">
    <!-- Header -->
    <section class="header-fixed">
      <header class="part-header p-10">
        <nav class="nav-header">
        'etiquetas correspondientes para poder visualizar el menú'
        </nav>
      </header>
    </section>
<!-- END Header -->
```
Esta parte del código incluida en la etiqueta <body></body> se le agregó un contenedor para tener control del ancho máximo para que no se desbordara algún contenido, en ella nos encontramos el encabezado del documento que incluye el logo, nombre de la empresa y un menú para poder navegar a distintas vistas dentro de la web. Además, en el menú se encuentra una parte desplegable que abarca variadas recetas de una sola sección llamada recetas, con la ayuda de Bootstrap se logró implementar para una mejor facilidad de uso, comparándolo esta parte con el Wireframe y Mockup anteriormente realizado, decide añadir esa funcionalidad sin haberla incluido en el diseño. 

Por último, el encabezado está incluido en una sección principal para poder tener el menú fijado en la Ventana y siempre tener la facilidad de interactuar con el menú sin necesidad de volver hasta la parte superior, al principio sé ME complico, ya que, dos pociones entraron en conflicto y no me daba el resultado que quería, revisando el código logre encontrar el bug y solucionarlo lo cual logre obtener lo que esperaba.

![image](https://user-images.githubusercontent.com/80645321/194388408-adfb171b-3ead-4990-be05-1e191b263bda.png)

## Slider de imágenes 🔸
```
<!-- Slider image header -->
   <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
     <div class="carousel-indicators">
      'etiquetas correspondientes que brinda Boostrap para el carusel de imagenes'
     </div>
  </div>
<!-- END Slider image header -->
```
Esta parte del código incluida en las etiquetas ```<body><main></main></body>```, abarca la sección de un carrusel de imágenes alusivas a los amasijos tradicionales la cual puede llevar a cabo con la ayuda de Bootstrap, el desafío fue poder cambiar gran parte de su estructura y estilo para lograr lo propuesto en el diseño, pero finalmente lo logre con la ayuda de la herramienta de desarrollador que nos ofrece el navegador para revisar toda la estructura de HTML y CSS.

![image](https://user-images.githubusercontent.com/80645321/194387787-a82a808a-bf40-4df2-8e22-45dc81efa72b.png)

## Sección de información sobre el significado de los amasijos 🔸
```
<!-- History entry -->
  <div class="content-first container" style="max-width: 90%;">
   <section>
    <div class="content-first-left text-center">
       'etiqueta para la imagen alusiva a la sección'
    </div>
    <div class="content-first-right">
       'etiquetas para el título y descripción sobre la sección'
    </div>
    <hr class="m-0">
   </section>
<!-- END HISTORY ENTRIES -->
```
Esta parte del código incluida en las etiquetas ```<body><main></main></body>```, tiene como propósito informar a los usuarios sobre “¿Qué son los amasijos?” y esa información descriptiva envuelve alrededor una imagen alusiva sobre el tema principal.

![image](https://user-images.githubusercontent.com/80645321/194387917-865cb2b7-e469-40ae-aafa-fbdc00b90202.png)

## Sección de la historia de los amasijos y sus productos 🔸
```
<!-- History all entry -->
   <section class="pt-5 pb-5">
     <div class="row mt-5">
       <div class="col-8 text-center">
         'etiquetas para el título, descripción sobre la sección y enlace'
       </div>
      <div class="text-center col-4">
        'etiqueta para la imagen alusiva a la sección'
      </div>
    </div>
   </section>
<!-- END History  -->
```
Esta parte del código incluida en las etiquetas ```<body><main></main></body>```, tiene como propósito informar a los usuarios sobre “La historia de los amasijos en Colombia” esa información descriptiva se encuentra al lado de una imagen alusiva sobre el tema y un enlace para visualizar mejor la información. Con la ayuda de las filas y las columnas que brinda Bootstrap para controlar elementos seguidos como en este caso. Luego se incluyen imágenes representativas sobre algunos amasijos tradicionales.

![image](https://user-images.githubusercontent.com/80645321/194388044-93ecf446-7a39-4604-bcef-ce2a70a143e2.png)

## Sección de las recetas de los amasijos 🔸
```
<!-- Recetas all entry -->
   <section class="pt-5 pb-5">
     <div class="row mt-5">
       <div class="col-4 text-center">
         'etiqueta para la imagen alusiva a la sección'
       </div>
       <div class="content-middle col-8 text-center">
         'etiquetas para el título, descripción sobre la sección y enlace'
       </div>
     </div>
   </section>
   <section class="pt-5 pb-5">
     <section class="content-third">
       <div class="row pt-3">
         <div class="text-center col-4">
           'etiqueta para la imagen alusiva al producto'
         </div>
         <div class="content-last p-3 col-8">
           'etiquetas para el título y descripción del producto'
         </div>
       </div>
       <div class="row pt-5">
     </section>
   </section>
<!-- END Recetas  -->
```
Esta parte del código incluida en las etiquetas ```<body><main></main></body>```, tiene como propósito informar a los usuarios sobre “Las recetas comunes de los amasijos” esa información descriptiva se encuentra al lado de una imagen alusiva sobre el tema y un enlace donde redirige a una nueva vista con información más detallada. Con la ayuda de las filas y las columnas que brinda Bootstrap para controlar elementos seguidos como en este caso. Luego se incluyen imágenes representativas sobre algunos amasijos tradicionales.

![image](https://user-images.githubusercontent.com/80645321/194388113-61040337-a5cb-4cab-a7dd-1757edb3201d.png)

## Sección Footer del documento HTML 🔸
```
<!-- Footer -->
   <footer class="part-footer">
     <div class="container" style="max-width: 100%;">
      'etiquetas para el logo, iconos de redes, ubicación y email corporativo'
     </div>
   </footer>
<!-- END footer -->
```
Esta parte del código se describe el pie de página de una web, en esta última sección abarca información puntual sobre la empresa seguida de las diferentes redes sociales con las cuales se puede contactar igualmente que el correo empresarial y finalmente la ubicación donde se encuentre la empresa actualmente.

![image](https://user-images.githubusercontent.com/80645321/194388225-14718d48-d7c7-4114-a117-bea85b2d824e.png)

# Vistas 🟧🟨🟩🟦

Con base a la estructura desarrollada en la página principal, logre realizar las vistas restantes con información más detalla sobre cada sección, solamente tuve que reorganizar algunas cosas, cambiar el contenido para visualizar lo necesario y lo descritivo de la vista propuesta.
### En cada vista siempre permanecio la msima estructura del encabezado con su menú y el pie de página.

>Vista historia
![image](https://user-images.githubusercontent.com/80645321/194437122-e2c435e6-8c71-46f5-9ba1-2289ddd5c1e2.png)

>Vista recetas
![image](https://user-images.githubusercontent.com/80645321/194437152-52fe5d19-ac0c-4736-8c12-b8b9b61c37dc.png)

>Vista recetas por producto
![image](https://user-images.githubusercontent.com/80645321/194437195-cd0b3155-4183-4b31-bf02-092daefea79e.png)

>Vista comunidad
![image](https://user-images.githubusercontent.com/80645321/194392099-24b5389f-46c3-46aa-8573-d5a7f780c85c.png)


## Sección de formularios

```
<!-- Formulario -->
   <div class="container">
     <form>
       <div class="row">
         <div class="content-formulario col-md">
          'etiquetta para un campo de texto'    
         </div>
         <div class="content-formulario col-md">
           'etiquetta para un campo de texto'      
         </div>
        </div>
        <section class="content-formulario p-4">
         'etiquetta para un campo de texto'  
        </section>
        'etiquetta para el botón de envio'  
      </div>
    </form>
  </div>
<!-- END Formulario -->
```

Esta parte del código abarca un formulario básico que se encuentra en cada receta y en el foro para que los usuarios puedan dar sus opiniones frente a la web.

![image](https://user-images.githubusercontent.com/80645321/194395599-6dd3f349-34df-4c2e-b1b2-0f67e406daee.png)

