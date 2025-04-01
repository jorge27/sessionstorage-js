# Proyecto de Autenticación con JWT y SessionStorage

Este repositorio se utiliza para evaluar la comprensión y aplicación de autenticación basada en JSON Web Tokens (JWT) en una aplicación web, junto con el uso de SessionStorage para guardar la información del usuario durante la sesión. El objetivo es demostrar el uso efectivo de JWT para la validación de usuarios y la integración de SessionStorage para mantener la información de la sesión de forma temporal.

## Instrucciones para Clonar el Repositorio

1. Abre tu terminal o línea de comandos.
2. Navega al directorio donde deseas clonar el repositorio.
3. Ejecuta el siguiente comando 

   ```bash
   git clone https://github.com/jorge27/sessionstorage-js.git

4. Ingresa al directorio del repositorio clonado:
    ````bash
    cd sessionstorage-js
    
## Requisitos del Proyecto
El proyecto debe cumplir con los siguientes requisitos:
- La aplicación debe permitir que los usuarios se logueen utilizando JSON Web Tokens para la validación.
- Al iniciar sesión, la aplicación debe almacenar el token JWT y la información del usuario en SessionStorage.
- Los datos almacenados en SessionStorage deben persistir mientras la pestaña esté activa y borrarse al cerrarla.
- La aplicación debe contar con un formulario de login para que los usuarios ingresen sus credenciales.
- Tras el login, se debe mostrar un mensaje de bienvenida junto con la opción de cerrar sesión.
- Pruebas Unitarias: Incluir pruebas unitarias que verifiquen el correcto funcionamiento de la petición y la actualización de la tabla.
- Tiempo de Ejecución: El proyecto debe completarse en un máximo de 1 hora.
