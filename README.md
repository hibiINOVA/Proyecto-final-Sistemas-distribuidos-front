Catálogo de Videojuegos - Frontend (Angular)

Este proyecto es la interfaz de usuario (frontend) construida con Angular para interactuar con un sistema de gestión de videojuegos.
Inicio Rápido

Sigue estos pasos para poner en marcha la aplicación web en tu entorno local.
1. Requisitos Previos

Necesitas tener instalados:

    Node.js y npm: Asegúrate de tener una versión LTS (Long-Term Support).

    Angular CLI: Necesario para compilar y ejecutar el proyecto.

Bash

# Instalar Angular CLI globalmente (si no lo tienes)
npm install -g @angular/cli

2. Instalación de Dependencias

Navega al directorio raíz de este proyecto (donde se encuentra el archivo package.json) e instala todas las dependencias:
Bash

npm install

3. Ejecución del Servidor

Para que la aplicación funcione, el servidor API (backend) debe estar corriendo y accesible.

Una vez instaladas las dependencias, inicia el servidor de desarrollo de Angular con el siguiente comando:
Bash

ng serve

Acceso a la Aplicación

Cuando el proceso de compilación termine exitosamente, abre tu navegador web y navega a la siguiente dirección:

http://localhost:4200/
Nota Importante

Esta aplicación depende de una API REST externa para obtener, crear y modificar datos. Asegúrate de que el backend correspondiente esté activo y configurado correctamente para que el frontend pueda interactuar con él.
