LiterAlura - Catálogo de Libros
¡Hola y bienvenidos a otro challenge de back-end! Este proyecto es parte de Oracle Next Education y está dirigido a todos los estudiantes interesados en mejorar sus habilidades en desarrollo back-end. Soy Isai Aram Perez Flores, alumno de Alura Latam, y estoy aquí para guiarlos en este desafío.

Descripción del Proyecto
El proyecto LiterAlura es un catálogo de libros que permite a los usuarios registrar libros en una base de datos y obtener información sobre estos libros ya registrados. La aplicación se desarrollará utilizando Java, Spring, y PostgreSQL. Es fundamental que antes de comenzar este desafío, hayan completado los cursos sobre Java y Spring Data JPA.

Requisitos de la Aplicación
La aplicación debe cumplir con las siguientes cinco funcionalidades básicas:

Buscar libro por título:

El usuario ingresa el nombre del libro que desea buscar.
La aplicación consulta la API de Gutendex, obtiene la información del libro y lo registra en la base de datos.
Si el libro ya está registrado, se notifica al usuario.
Listar libros registrados:

Permite ver todos los libros almacenados en la base de datos.
Listar autores registrados:

Muestra una lista de todos los autores cuyos libros están en la base de datos.
Listar autores vivos en un determinado año:

Permite ingresar un año y muestra los autores que estaban vivos en ese periodo.
Listar libros por idioma:

Permite buscar libros según el idioma especificado (ES, EN, FR, PT).
Consideraciones Adicionales
La aplicación debe manejar adecuadamente los casos en que no se encuentra el libro buscado.
Debe evitarse la inserción de libros duplicados en la base de datos.
Aunque es una aplicación de consola, se alienta la creatividad para mejorar y agregar funcionalidades adicionales.
Configuración del Proyecto
Spring Initializer
Vayan a Spring Initializer.
Configuren el proyecto como un proyecto Maven en Java con la última versión de Spring Boot (en el momento de este desafío es la 3.2.4).
Nombre del grupo: com.alura.
Nombre del artefacto: literalura.
Packaging: JAR.
Java: 17.
Dependencias
Spring Data JPA
PostgreSQL Driver
API de Gutendex
Utilizaremos la API de Gutendex, que es parte del Proyecto Gutenberg, una biblioteca digital con más de 70 mil libros gratuitos. Lean la documentación de la API para entender cómo implementar los métodos necesarios para el proyecto.

Organización del Trabajo
Utilizaremos un tablero de Trello para organizar nuestras tareas. En el tablero encontrarán:

Descripción del desafío y contenido adicional: Información y recursos útiles.
Columna de Backlog: Detalle de cada tarea desde la creación del proyecto en GitHub hasta funcionalidades adicionales.
Recursos y Comunidad
Para resolver dudas, ayudar a compañeros y compartir resultados, utilicen el servidor en Discord. La colaboración y el apoyo mutuo son esenciales para el éxito de este desafío.

¡Con dedicación y esfuerzo, lograrán construir un proyecto increíble! ¡Nos vemos y buena suerte!

Isai Aram Perez Flores
Alumno de Alura Latam
