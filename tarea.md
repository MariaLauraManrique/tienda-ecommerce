### Puntos a realizar en el proyecto:

    - Menú de navegación: Lograr que sea funcional y se puedan navegar entre las diferentes páginas del sitio. (Home , Contacto, Cart -> enlace logo del carrito). El checkout debe ser accedido desde la página carrito.
    - Para cart, checkout, conctact, mejorar el logo y el título del banner.
  
    - Página Contacto: Rearmar la parte del formulario y la info de contacto, en lo posible con bootstrap, sino con flex. Para que quede lo más similar posible al diseño.
    - Carrito: Pulir los detalles de diseño. 
    - Checkout: terminar la parte del formulario, y rearmar la estructura para posicionar cambios contenedores (form, resumen final.)
    - Desarrollar el listado de carácteristicas de la parte superior de las páginas de contacto, carrito y checkout.



### Tarea 26-08

    - Mejoras mobile:
        - Home: Separa carrusel, de la sección beatiful rooms.
        - Product detail: Mostrar solo un card en el carrusel (realated products)
            new Splide('.splide', {
            perPage: 4,
            gap: 16,
            type: "loop",
            autplay: true,
            interval: 500,
            breakpoints: {
                640: {
                    perPage: 2,
                },
            }
            }).mount();
        
        - Contacto: mejorar un poco el formulario (tamaño)
        - Carrito
        - Checkout