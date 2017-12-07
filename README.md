## Proyecto de Pagina Web
Este proyecto es una pagina web para el museo Mucho, un museo que se dedica a  informar sobre la cultura del chocolate

## En este proyecto se utilizo
- Html5
- CSS3
- JavaScript
- JQuery 3.2.1
- Materialize
- Adobe Illustrator

## Funcionalidad
El proyecto esta diseñado para funcionar de forma responsive esto quiere decir que se ajusta todo el contenido del html en
cualquier tipo de pantalla esto es posible por el codigo css y materialize que es una libreria con codigo JavaScript y CSS
que nos ayudan a reutilizar código esto es para que la pagina sea mas rapida y estable en un servidor. Con esto utilizamos
todo el codigo en un solo html para que se pidan menos archivos al servidor y se opto por utilizar encapsulamiento de materialize
para seccionar el código en el html para solo mostrar la informacion que el usuario busque.

El código esta seccionado en:
- Inicio
- Historia
- Exposiciones
- Galeria
- Contacto

Es posible apreciar que dependiendo la resolucion de la pantalla cambia la estructura de la pagina esto es por que la pagina
esta pensada para verse diferente dependiendo el dispositivo.

A continuacion se explicara las secciones mas complejas de la pagina web. 

## Galeria
La galeria esta pensada como una pequeña red social dentro de la pagina en la cual podemos ver cartas (El contnedor de la imagen)
esta tiene los siguientes atributos:

- Imagen
- Nombre de la imagen
- Boton responsivo
- Descripción de la imagen

Estas estan pensadas para  verse en dispositivos grandes acomodandose en columnas de 4 y en dispositivos mas pequeños en
columnas de 2

El contenedor de las cartas es un objeto que nos proporciona materialize la cual es una combinación de CSS, JavaScript y JQuery
es posible observar como llamamos a esta funcion en las linea de código 24 a la 28 de nuestro index.html.

## Contacto
 En el contacto podemos apreciar que se muestra en google maps la ubicación de del museo esto se nos permite copiando la direccion
 del mapa como un <iframe> a esta etiqueta se le tiene que especificar la posición del mapa y los tamaños de este los cuales estan definidos
 en el código en porcentaje

 Tambien es posible apreciar un formulario este esta modificado tambien para ser responsivo esto es con ayuda de materialize el cual mediante
 atributos sensillos agrega interactividad al formulario.

 ## Botones de animaciones.
 Al precionar todos los botones es posible apreciar una animación del mounstruo hablando esto es por que los botones tiene una fracción de código
 en JavaScript por el atributo onClick que nos permite realizar una acción al dar clic en el boton en este caso hablar. En la función definimos el tiempo 
 que habla el moustruo como 4 seg. por lo cual lo definimos como 4000.

 ## Adobe Illustrator
 Fue utilizado para realizar el dibujo del moustruo esto es por que ya que deseamos que la pagina web sea responsive tendremos multiples tamaños
 por lo que Illustrator que utiliza vectores y no mapas de bits nos permite que nuestras imagenes sean de gran calidad.

