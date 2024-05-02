# Proyecto de Dashboard de Usuario con Laravel "MVC AJG"

Este proyecto es una aplicación web desarrollada utilizando Laravel PHP, HTML, CSS y JavaScript. Proporciona funcionalidades completas de un dashboard de usuario, permitiendo gestionar información personal como nombre, apellido, RUT, teléfono, dirección, entre otros detalles.

# Funcionalidades Destacadas

- **Gestión de Usuario**: Permite a los usuarios registrados acceder y actualizar su información personal.
- **MVC**: El proyecto sigue el patrón Modelo-Vista-Controlador para una estructura de código clara y organizada.
- **Envío de Datos AJAX**: Utiliza tecnología AJAX para enviar y recibir datos de forma asíncrona, mejorando la experiencia del usuario.
- **Búsqueda y Filtros Avanzados**: Ofrece funcionalidades de búsqueda y filtrado para facilitar la navegación y encontrar información específica.
- **Variables de Sesión**: Utiliza variables de sesión para mantener la información del usuario durante su sesión en el dashboard.

# Requisitos del Sistema

- PHP >= 7.0
- Composer (para la gestión de dependencias de PHP)
- Node.js y NPM (para la gestión de dependencias de JavaScript)

# Instalación

1. Clona este repositorio en tu máquina local.
2. Ejecuta `composer install` en el directorio raíz del proyecto para instalar las dependencias de PHP.
3. Copia el archivo `.env.example` y renómbralo a `.env`. Configura las variables de entorno necesarias, como la conexión a la base de datos.
4. Ejecuta `php artisan key:generate` para generar una nueva clave de aplicación.
5. Ejecuta `npm install && npm run dev` para instalar las dependencias de JavaScript y compilar los assets.
6. Ejecuta `php artisan migrate` para ejecutar las migraciones de base de datos y crear las tablas necesarias.
7. Ejecuta `php artisan serve` para iniciar el servidor de desarrollo.
8. Visita `http://localhost:8000` en tu navegador para acceder al dashboard de usuario.

