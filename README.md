# Prueba Técnica - Desarrollador web

Lo siguiente es una prueba para evaluar a los postulantes a programador front-end

## Introducción

Este repositorio contiene una serie de requerimientos de un caso práctico, que busca evaluar las capacidades técnicas del candidato con respecto a las principales funciones y responsabilidades que se requieren dentro del área de desarrollo.

¿Qué se busca evaluar?

Principalmente los siguientes aspectos:

1. Creatividad para resolver los requerimientos,
2. Calidad del código entregado (estructura y buenas prácticas),
3. Familiaridad con plataformas de desarrollo.


## Importante

La siguiente prueba será realizada desde la plataforma de Shopify, y para ello necesitarás acceso a la cuenta en donde se realizará la prueba.

Cuando tengas acceso a la cuenta deberás dirigirte a la siguiente ruta Online Store -> Themes y duplicar el current theme para después renombrarlo con tu nombre y apellido


![ Shopify platform](https://cdn.shopify.com/s/files/1/0553/4656/1213/files/Sin_titulo81.png?v=1654619518)

Los cambios que realices deberás realizarlo en el theme que creaste anteriormente. Para ello deberás de dar clic en el botón 'Actions' de tu theme y posteriormente en 'Edit Code'.

![ Shopify platform2](https://cdn.shopify.com/s/files/1/0553/4656/1213/files/Sin_titulo82.png?v=1654620280)


Siguiendo los anteriores pasos podrás ver todo el código del proyecto y editar los archivos correspondientes para realizar la prueba desde esa ventana.

![ Shopify platform3](https://cdn.shopify.com/s/files/1/0553/4656/1213/files/Sin_titulo83.png?v=1654622858)




Antes de comenzar es necesario conocer un poco la estructura del proyecto

#### layouts
Es la base del tema. Es utilizado para alojar los elementos repetidos del tema, como el header y el footer. La página del producto, las colecciones y el home page utiliza el archivo theme.liquid

#### Templates
Los templates controlan que se tiene que mostrar en cada página, La página del producto utiliza el template llamado product.liquid

#### Sections
Son módulos reutilizables de contenidos que pueden ser personalizados por el cliente. Para utilizar una section en un template se utiliza la siguiente sintaxis {% section 'section-name' %}

#### Snippets
Los snippets son trozos de código que pueden ser referenciados dentro de sections, templates o layouts.

#### Assets
Directorio que contiene todos los activos del proyecto como imágenes, hojas de estilo y archivos javascript.




## Ejercicio

Para mejorar la experiencia de usuario en una tienda en línea, se busca que el botón de  'ADD TO CART' siempre este visible en la pantalla.

![ Shopify platform4](https://cdn.shopify.com/s/files/1/0553/4656/1213/files/Sin_titulo72.png?v=1654614428)


Cuando el usuario se desplace hacia abajo y el botón deje de estar visible, se debe de mostrar una barra en la parte superior de la página, el cual le permita al usuario visualizar el nombre del producto, la variante actual, precio y un botón para poder agregar al carrito, similar a lo que se tiene en la siguiente imagen:

![ header](https://cdn.shopify.com/s/files/1/0553/4656/1213/files/Sin_titulo74.png?v=1654615253)

### Importante

Cuando el usuario cambia de variante, este también debe reflejarse en la información que se muestra en la barra superior

![ header1](https://cdn.shopify.com/s/files/1/0553/4656/1213/files/Sin_titulo80.png?v=1654617998)
![ header2](https://cdn.shopify.com/s/files/1/0553/4656/1213/files/Sin_titulo79.png?v=1654617876)