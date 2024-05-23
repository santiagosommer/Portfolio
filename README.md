# Portfolio
Para crear un portfolio utilizando Ruby on Rails y Angular, puedes utilizar el siguiente stack tecnológico:

1. **Backend: Ruby on Rails**
   - **Ruby**: Lenguaje de programación.
   - **Rails**: Framework web para construir la aplicación backend.
   - **PostgreSQL**: Base de datos relacional, aunque puedes usar otras como MySQL.
   - **Puma**: Servidor web para Rails.
   - **Devise**: Gem para la autenticación de usuarios.
   - **Active Storage**: Para gestionar la subida de archivos e imágenes.
   - **RSpec**: Framework para pruebas.

2. **Frontend: Angular**
   - **Angular**: Framework frontend para construir interfaces de usuario.
   - **TypeScript**: Lenguaje que extiende JavaScript, utilizado en Angular.
   - **Angular CLI**: Herramienta de línea de comandos para crear y gestionar el proyecto Angular.
   - **RxJS**: Librería para programación reactiva.
   - **Bootstrap o Angular Material**: Librerías de estilos para diseñar la interfaz.

3. **API de Conexión:**
   - **Rails API**: Configura tu aplicación Rails para servir como API.
   - **CORS**: Para manejar las solicitudes de origen cruzado entre el frontend y el backend.

4. **Autenticación y Autorización:**
   - **JWT (JSON Web Tokens)**: Para la autenticación basada en tokens entre Angular y Rails.
   - **Devise-JWT**: Extensión de Devise para manejar JWT en Rails.

5. **Despliegue:**
   - **Heroku**: Plataforma como servicio (PaaS) para desplegar aplicaciones Rails.
   - **Netlify**: Servicio para desplegar aplicaciones frontend como las de Angular.
   - **Docker**: Para contenerizar las aplicaciones y facilitar el despliegue.

6. **Herramientas de Desarrollo:**
   - **Git**: Control de versiones.
   - **Webpacker**: Integración de Webpack con Rails para gestionar el JavaScript.
   - **Yarn**: Gestor de paquetes para JavaScript.
   - **VS Code**: Editor de código recomendado con extensiones para Ruby y Angular.

### Ejemplo de Flujo de Trabajo

1. **Configuración del Backend con Rails:**
   - Configura una nueva aplicación Rails con `rails new my_portfolio --api`.
   - Configura la base de datos y añade gems necesarias (Devise, Devise-JWT, etc.).
   - Crea los modelos y controladores necesarios para manejar los datos del portfolio.

2. **Configuración del Frontend con Angular:**
   - Crea una nueva aplicación Angular con `ng new my-portfolio`.
   - Configura los servicios para consumir la API de Rails.
   - Diseña los componentes y vistas para mostrar tu portfolio.

3. **Integración y Pruebas:**
   - Configura CORS en Rails para permitir solicitudes desde el frontend.
   - Prueba las conexiones entre Angular y Rails utilizando herramientas como Postman.
   - Escribe pruebas unitarias y de integración tanto para el frontend como para el backend.

4. **Despliegue:**
   - Despliega el backend en Heroku siguiendo sus guías.
   - Despliega el frontend en Netlify o un servicio similar.

Este stack te proporcionará una estructura sólida para desarrollar un portfolio con Ruby on Rails y Angular, aprovechando las fortalezas de ambos frameworks.
