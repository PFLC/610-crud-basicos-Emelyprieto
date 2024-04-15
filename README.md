
# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

-Las operaciones CRUD son la columna vertebral de cualquier aplicación basada en bases de datos. Te permiten realizar las operaciones de base de datos más básicas y esenciales, como crear nuevos registros, leer los existentes, actualizarlos y eliminarlos.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.
- JavaScript (JS): Es fundamental para la interactividad en el lado del cliente y se puede usar junto con PHP para realizar solicitudes asíncronas (AJAX) para actualizar partes específicas de una página sin necesidad de recargarla por completo.

-jQuery: Una biblioteca de JavaScript que simplifica la manipulación del DOM y la realización de solicitudes AJAX. Puede facilitar la implementación de interactividad en la interfaz de usuario.

-AJAX (Asynchronous JavaScript and XML): Una técnica de desarrollo web que permite actualizar partes específicas de una página sin necesidad de recargarla por completo. Se puede utilizar para enviar y recibir datos del servidor sin interrumpir la experiencia del usuario.

-JSON (JavaScript Object Notation): Un formato de intercambio de datos ligero que es fácil de leer y escribir para humanos y fácil de analizar y generar para las máquinas. Se utiliza comúnmente para transmitir datos entre el cliente y el servidor en aplicaciones web.

-RESTful APIs: Si estás construyendo una aplicación más compleja o escalable, puedes optar por crear una API RESTful en PHP para manejar las operaciones CRUD de manera más estructurada y escalable. Esto permite una separación más clara entre el frontend y el backend, facilitando el desarrollo y la escalabilidad de la aplicación.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.
  - 
### 5. Página de Lista de Elementos:

-Muestra una lista de los elementos existentes en la base de datos.
-Proporciona opciones para filtrar, ordenar y buscar elementos.
-Permite al usuario seleccionar un elemento para ver detalles, editar o eliminar. 

### 6.Página de Creación de Elementos:

Presenta un formulario para que el usuario ingrese datos para un nuevo elemento.
Valida los datos ingresados para garantizar que cumplan con los requisitos.
Permite al usuario enviar el formulario para crear un nuevo elemento en la base de datos.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.


## Operaciones del CRUD:

Crear (Create): Permite agregar nuevos registros a la base de datos.
Leer (Read): Recupera y muestra registros existentes de la base de datos.
Actualizar (Update): Modifica registros existentes en la base de datos.
Borrar (Delete): Elimina registros de la base de datos.
## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

