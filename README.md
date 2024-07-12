# Proyecto biblioteca de libros

<img src="https://raw.githubusercontent.com/rotfflores/web/main/img/logo.png" alt="logo del proyecto" width="100" />

Descripción del Proyecto
Librería Good es una aplicación que interactúa con la API de Gutendex para buscar, almacenar y gestionar libros y autores. Esta aplicación ofrece varias funcionalidades como la búsqueda de libros por nombre, idioma y autor, así como la visualización de los autores y los libros más descargados.
Funcionalidades
Menú Principal
El programa presenta un menú con las siguientes opciones:

Agregar Libro por Nombre: Busca un libro en la API de Gutendex por su nombre y lo almacena en la base de datos si no existe.
Libros Buscados: Muestra todos los libros buscados y almacenados en la base de datos.
Buscar Libro por Nombre: Permite buscar un libro en la base de datos por su nombre.
Buscar Todos los Autores de Libros Buscados: Lista todos los autores únicos de los libros almacenados.
Buscar Autores por Año: Permite buscar autores que estuvieran vivos en un año específico.
Buscar Libros por Idioma: Muestra libros almacenados según el idioma especificado.
Top 10 Libros más Descargados: Muestra los 10 libros más descargados.
Buscar Autor por Nombre: Permite buscar un autor por su nombre.
Salir: Cierra la aplicación.
Métodos Principales
consumo()
Gestiona el flujo principal de la aplicación y presenta el menú de opciones al usuario.

getDatosLibro()
Obtiene los datos de un libro de la API de Gutendex y convierte la respuesta JSON a un objeto Libro.

buscarLibroEnLaWeb()
Busca un libro en la web, lo guarda en la base de datos si no existe, y maneja excepciones.

librosBuscados()
Lista todos los libros almacenados en la base de datos.

buscarLibroPorNombre()
Busca un libro en la base de datos por su nombre y lo muestra.

BuscarAutores()
Lista todos los autores únicos de los libros almacenados.

buscarLibrosPorIdioma()
Busca libros en la base de datos según el idioma especificado.

buscarAutoresPorAnio()
Busca autores que estuvieran vivos en un año específico.

top10LibrosMasDescargados()
Muestra los 10 libros más descargados de la base de datos.

buscarAutorPorNombre()
Busca un autor en la base de datos por su nombre y lo muestra.

Requisitos
Java 8 o superior
Spring Framework
Conexión a Internet para acceder a la API de Gutendex
Base de datos compatible con Spring Data JPA
Configuración
Clonar el repositorio:

bash
Copy code
git clone https://github.com/tu-usuario/libreria-good.git
Navegar al directorio del proyecto:

bash
Copy code
cd libreria-good
Configurar las propiedades de la base de datos en application.properties:

properties
Copy code
spring.datasource.url=jdbc:mysql://localhost:3306/libreria_good
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
spring.jpa.hibernate.ddl-auto=update
Ejecutar la aplicación:

bash
Copy code
./mvnw spring-boot:run
Uso
Ejecuta la aplicación y sigue las instrucciones del menú principal.
Ingresa las opciones según las funcionalidades que desees utilizar.
Contribuciones
Las contribuciones son bienvenidas. Por favor, abre un issue para discutir lo que te gustaría cambiar o mejorar.

