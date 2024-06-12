# Rutas Públicas y Privadas

Este proyecto contiene una implementación de un sistema de enrutamiento con rutas públicas y privadas, ideal para aplicaciones web que requieren gestionar accesos y permisos de usuarios.

## Características

- **Autenticación de Usuarios**: Mecanismo para autenticar usuarios y gestionar sesiones.
- **Rutas Públicas**: Accesibles para cualquier usuario, sin necesidad de autenticación.
- **Rutas Privadas**: Requieren autenticación para ser accesibles, asegurando la protección de recursos y datos.
- **Redirección Automática**: Usuarios no autenticados que intenten acceder a rutas privadas serán redirigidos a la página de inicio de sesión.
- **Protección de Rutas**: Implementación de middleware para verificar el estado de autenticación antes de acceder a rutas privadas.

## Tecnologías Utilizadas

- **Backend**: [Node.js](https://nodejs.org/), [Express](https://expressjs.com/)
- **Autenticación**: [JWT (JSON Web Tokens)](https://jwt.io/)

## Instalación

1. **Clonar el repositorio**

    ```bash
    git clone https://github.com/usuario/rutas-publicas-privadas.git
    cd rutas-publicas-privadas
    ```

2. **Instalar dependencias**

    Para el backend:

    ```bash
    cd backend
    npm install
    ```

3. **Configurar variables de entorno**

    Crear un archivo `.env` en la raíz del proyecto y añadir las siguientes variables:

    ```env
    # Backend
    PORT=3000
    JWT_SECRET=your_jwt_secret
    DATABASE_URL=your_database_url

    ```

4. **Iniciar la aplicación**

    Para el backend:

    ```bash
    cd backend
    npm start
    ```

    La aplicación estará disponible en `http://localhost:3000`.

## Uso

- **Página de Inicio de Sesión**: Usuarios deben autenticarse para acceder a rutas privadas.
- **Rutas Públicas**: Accesibles sin autenticación.
- **Rutas Privadas**: Accesibles solo después de la autenticación exitosa.

## Contribuciones

¡Las contribuciones son bienvenidas! Por favor, sigue estos pasos para contribuir:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-caracteristica`).
3. Realiza tus cambios y haz commit (`git commit -am 'Agrega nueva característica'`).
4. Envía tus cambios a tu repositorio fork (`git push origin feature/nueva-caracteristica`).
5. Crea un Pull Request en GitHub.

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).

## Contacto

Para cualquier consulta o sugerencia, por favor contactanos.

