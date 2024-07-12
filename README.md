# Proyecto Biblioteca de Libros

<img src="https://raw.githubusercontent.com/rotfflores/web/main/img/logo.png" alt="logo del proyecto" width="100" />

## Descripción del Proyecto

Librería Good es una aplicación que interactúa con la API de Gutendex para buscar, almacenar y gestionar libros y autores. Esta aplicación ofrece varias funcionalidades como la búsqueda de libros por nombre, idioma y autor, así como la visualización de los autores y los libros más descargados.

## Funcionalidades

### Menú Principal

El programa presenta un menú con las siguientes opciones:

1. **Agregar Libro por Nombre**: Busca un libro en la API de Gutendex por su nombre y lo almacena en la base de datos si no existe.
2. **Libros Buscados**: Muestra todos los libros buscados y almacenados en la base de datos.
3. **Buscar Libro por Nombre**: Permite buscar un libro en la base de datos por su nombre.
4. **Buscar Todos los Autores de Libros Buscados**: Lista todos los autores únicos de los libros almacenados.
5. **Buscar Autores por Año**: Permite buscar autores que estuvieran vivos en un año específico.
6. **Buscar Libros por Idioma**: Muestra libros almacenados según el idioma especificado.
7. **Top 10 Libros más Descargados**: Muestra los 10 libros más descargados.
8. **Buscar Autor por Nombre**: Permite buscar un autor por su nombre.
0. **Salir**: Cierra la aplicación.

### Métodos Principales

#### `consumo()`
Gestiona el flujo principal de la aplicación y presenta el menú de opciones al usuario.

#### `getDatosLibro()`
Obtiene los datos de un libro de la API de Gutendex y convierte la respuesta JSON a un objeto `Libro`.

#### `buscarLibroEnLaWeb()`
Busca un libro en la web, lo guarda en la base de datos si no existe, y maneja excepciones.

#### `librosBuscados()`
Lista todos los libros almacenados en la base de datos.

#### `buscarLibroPorNombre()`
Busca un libro en la base de datos por su nombre y lo muestra.

#### `BuscarAutores()`
Lista todos los autores únicos de los libros almacenados.

#### `buscarLibrosPorIdioma()`
Busca libros en la base de datos según el idioma especificado.

#### `buscarAutoresPorAnio()`
Busca autores que estuvieran vivos en un año específico.

#### `top10LibrosMasDescargados()`
Muestra los 10 libros más descargados de la base de datos.

#### `buscarAutorPorNombre()`
Busca un autor en la base de datos por su nombre y lo muestra.

## Requisitos

- Java 8 o superior
- Spring Framework
- Conexión a Internet para acceder a la API de Gutendex
- Base de datos compatible con Spring Data JPA

## Uso

1. Ejecuta la aplicación y sigue las instrucciones del menú principal.
2. Ingresa las opciones según las funcionalidades que desees utilizar.



¡Gracias por usar Librería!
