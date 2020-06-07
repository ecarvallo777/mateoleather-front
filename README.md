Para este proyecto fue imprescindible el uso del framework CSS Bootstrap 4, una de las librerías más conocidas y de código abierto que están disponibles en el lado del FrontEnd. BootStrap nos facilitó enormemente la maquetación de la página web.
Para esto, en este proyecto implementamos bootstrap de forma remota, es decir, incluímos el framework sin necesidad de descargarlo, sino más bien, utilizamos una CDN (Content Delivery Network) que nos facilita bootstrap.
Gracias a las etiquetas Link y Script, HTML5 nos permite importar de manera remota las librerías de bootstrap para utilizarlas sin necesidad de almacenarlas en nuestro servidor local.
Pese a que BootStrap nos ofrece una cantidad enorme de íconos, decidimos utilizar nuestros propios íconos. Por otro lado, la fuente Lato de Google que utilizamos en este proyecto, la importamos con la etiqueta Link.
En cuanto a la maquetación de nuestro proyecto, utilizamos una hoja de estilo en donde añadimos propiedades tradicionales de maquetación, contenedores y divisiones, además, le dimos propiedades para visualización en aparatos móviles. También utilizamos la hoja de estilo css "normalize" de necolas alojada en Github para estandarizar la renderización de los diferentes navegadores modernos.
Por otro lado, se consideró el uso de buenas práctias y modularizamos el contenido de header y footer, para ahorrar líneas de código en nuestros archivos y poder editar de manera más rápida cualquier característica de estos. Para esto, se utilizó w3-include-html para incluir el html externo y una función de javascript para mostrar el contenido. 
Para continuar con las buenas prácticas, limpiamos nuestros archivos html de cualquier código no-html, en nuestro caso, javascript. Situandolo en carpetas dedicadas a alojar archivos js.
En cuanto a la implementación de BootStrap en nuestra página principal, lo utilizamos para darle dinamismo, incluyendo una ventana modal para notificar al cliente las medidas que se han implementado debido a la contigencia nacional.
Más abajo, casi llegando al footer, se añade un carrusel de bootstrap para mostrar con diferentes imagenes desenfocadas, testimonios reales de compra.	
Archivos categorías.html's: Para mostrar los productos de nuestro cliente (Mateo Leather), utilizamos secciones y divisiones de la hoja de estilo local, y para su paginación, implementamos la paginación amigable de BootStrap.
Archivo nosotros.html: Para mostrar la historia de Mateo Leather dividimos el contenedor en imagen y en texto, apoyado de la hoja de estilo local.
Archivo cotizar.html: Luego de importar el header y footer, tenemos código puro de bootstrap, el formulario de lleno desarrollado por los componentes que nos ofrece bootstrap junto a una ventana modal.
https://github.com/crewxart/crewxart.github.io
https://crewxart.github.io/
