# sitio-web-grupo1





Cristian Sahon										 



Gilmar Maldonado 



Nahum Albeño 



&nbsp;



&nbsp;



&nbsp;



Tipos de Páginas Web 



En el desarrollo web, hay páginas que se pueden clasificar en tres categorías según cómo se genera y se presenta su contenido. 



&nbsp;



Páginas Web Estáticas: Son las más “sencillas”. Su contenido es fijo y se da al navegador del usuario exactamente como está almacenado en el servidor. Cada visitante mira la misma información. Son ideales para sitios que no requieren de actualizaciones seguidas, como un portafolio personal, el "Acerca de" de una empresa o un currículum en línea. Por ejemplo, una página informativa sobre un evento histórico que no va a cambiar. 



Páginas Web Dinámicas: A diferencia de las estáticas, el contenido de estas páginas se genera en tiempo real cuando el usuario las solicita. Utilizan lenguajes de programación del lado del servidor (como PHP o Python) y bases de datos para personalizar el contenido. Por ejemplo, un blog de noticias, la página principal va a muestra siempre las últimas publicaciones sin la necesidad de editar el archivo HTML manualmente. Otro ejemplo es una tienda en línea que muestra productos diferentes según la categoría que elegimos. 



Páginas Web Interactivas: Llevan la personalización un paso más allá. Reaccionan a las acciones del usuario en tiempo real sin la necesidad de que recargue la página por completo. Se consigue con tecnologías del lado del cliente como JavaScript. La relación puede ser parte tanto de sitios estáticos como dinámicos. Por ejemplo, Google Maps. Puedes arrastrar el mapa, hacer zoom y buscar lugares, y la vista se actualiza instantáneamente. Las redes sociales como Facebook o X también son altamente interactivas, permitiéndote dar "me gusta" o comentar publicaciones con una respuesta inmediata de la interfaz. 



&nbsp;



&nbsp;



Uso de la Etiqueta <style> en HTML 



La etiqueta <style> se utiliza para incluir código CSS directamente dentro de un documento HTML. Su propósito es el de definir la apariencia y el diseño de los elementos HTML, como los colores, las fuentes y la disposición en la página. 



Normalmente, se coloca dentro de la sección <head> del documento. Al usar esta etiqueta, los estilos que definas se aplicarán únicamente a esa página HTML en particular. 



&nbsp;



&nbsp;



&nbsp;



Ejemplos:  



&nbsp;



Define el color del texto de un elemento. 



HTML 



<style> 

&nbsp; p { 

&nbsp;   color: green; 

&nbsp; } 

</style> 

&nbsp;

<p>Este texto del párrafo será de color verde.</p> 



&nbsp;



&nbsp;



&nbsp;



Establece el color de fondo de un elemento. 



HTML 



<style> 

&nbsp; div { 

&nbsp;   background-color: yellow; 

&nbsp; } 

</style> 

&nbsp;

<div>Este contenedor tiene un fondo amarillo.</div> 



&nbsp;



&nbsp;



Controla el tamaño del texto. Puedes usar píxeles (px), porcentajes (%) o unidades relativas (em). 



HTML 



<style> 

&nbsp; h2 { 

&nbsp;   font-size: 24px; 

&nbsp; } 

</style> 

&nbsp;

<h2>Este título tiene un tamaño de 24 píxeles.</h2> 



&nbsp;



&nbsp;



&nbsp;



&nbsp;



Alinea el texto dentro de un elemento. Los valores más comunes son left (izquierda), right (derecha), center (centrado) y justify (justificado). 



HTML 



<style> 

&nbsp; h3 { 

&nbsp;   text-align: center; 

&nbsp; } 

</style> 

&nbsp;

<h3>Este encabezado está centrado.</h3> 



&nbsp;



&nbsp;



Estos controlan el espacio alrededor de un elemento. 



margin: Es el espacio exterior, fuera del borde del elemento (lo separa de otros elementos). 



padding: Es el espacio interior, entre el contenido y el borde del elemento. 



HTML 



<style> 

&nbsp; .caja-ejemplo { 

&nbsp;   background-color: lightblue; 

&nbsp;   border: 1px solid black; /\* Borde para visualizar mejor \*/ 

&nbsp;    

&nbsp;   margin: 20px;       /\* 20px de espacio por fuera en todos los lados \*/ 

&nbsp;   padding: 15px;      /\* 15px de espacio por dentro en todos los lados \*/ 

&nbsp; } 

</style> 

&nbsp;

<div class="caja-ejemplo"> 

&nbsp; Este texto está dentro de una caja con 20px de margen exterior y 15px de relleno interior. 

</div> 

