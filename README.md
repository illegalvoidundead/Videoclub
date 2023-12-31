![](https://github.com/illegalvoidundead/Videoclub/blob/main/images/video-rentals.jpg)
# Base de datos para un videoclub

En este proyecto he desarrollado un esquema SQL para la gestión de un videoclub. El objetivo principal ha sido crear un esquema que permita administrar eficientemente el negocio a partir de una serie de tablas provinientes de una antigua base de datos. Para la limpieza, transformacion y organización de las tablas he utilizado la librería Pandas de Python. Para crear la base de datos he usado SQL mediante MySQL Workbench, una herramienta que facilita el diseño y la administración de bases de datos.


![](https://github.com/illegalvoidundead/Videoclub/blob/main/images/videoclub.jpeg)
## Características del videoclub

El esquema SQL desarrollado está destinado a un videoclub que ofrece una amplia selección de películas a sus clientes. Lo elementos que componen dicho esquema son los siguientes:

:movie_camera: Películas: El videoclub cuenta con una extensa colección de películas, cada una de las cuales está representada en la tabla "film". Cada película tiene un título, una descripción, una duración de alquiler, una tarifa de alquiler, una longitud, un costo de reemplazo, una clasificación y características especiales.

:clapper: Actores: Los actores que participan en las películas están representados en la tabla "actor". Cada actor tiene un identificador, un nombre y un apellido.
Categorías: Las películas se agrupan en diferentes categorías, que se representan en la tabla "category". Cada categoría tiene un identificador y un nombre.

:tongue: Idiomas: Las películas están disponibles en diferentes idiomas, que se representan en la tabla "language". Cada idioma tiene un identificador y un nombre.

:green_book: Inventario: El videoclub mantiene un inventario de las películas disponibles para alquilar. Esta información se registra en la tabla "inventory", que tiene un identificador de inventario, un identificador de película y un identificador de tienda.

:money_with_wings: Clientes: El videoclub tiene una base de datos de clientes, que se representa en la tabla "customer". Cada cliente tiene un identificador, un nombre, un apellido, una dirección de correo electrónico, un número de teléfono, una dirección, una ciudad, un estado, un país y un código postal.

:recycle: Alquileres: Los alquileres de películas se registran en la tabla "rental", que tiene un identificador de alquiler, una fecha de alquiler, un identificador de inventario, un identificador de cliente, una fecha de devolución y un identificador de personal.

:steam_locomotive: Old films: Catálogo de películas antíguas en el que hay registrado los nombres de los actores que aparecen, título de la película y categoría.

![](https://github.com/illegalvoidundead/Videoclub/blob/main/images/Esquema.jpg)
## Beneficios del esquema SQL

Para el desarrollo de la base de datos de este videoclub hemos utilizado un esquema SQL, el cual ofrece los siguientes beneficios:

Organización de la información: El esquema SQL permite almacenar y organizar de manera eficiente la información sobre películas, actores, categorías, idiomas, inventario, clientes y alquileres.

Facilidad de acceso a la información: Gracias al esquema SQL, es posible realizar consultas y obtener rápidamente la información necesaria sobre películas, actores, clientes, alquileres, etc.

Eficiencia en la gestión del negocio: El esquema SQL facilita la gestión del videoclub, permitiendo un seguimiento preciso de las películas disponibles, los clientes, los alquileres, etc.

En resumen, el esquema SQL desarrollado para este videoclub ofrece una solución eficiente y efectiva para la gestión de un negocio de alquiler de películas. Gracias a su diseño cuidadoso y a sus características útiles, este esquema SQL puede contribuir significativamente al éxito y la rentabilidad del videoclub.

![](https://github.com/illegalvoidundead/Videoclub/blob/main/images/videodrome07.gif)
