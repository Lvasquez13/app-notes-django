# app-notes-django
En resumen, la aplicación de notas es un ejemplo de un CRUD básico implementado en Django, que además incluye características de autenticación de usuarios y protección de rutas para garantizar la seguridad y la privacidad de los datos del usuario.


## Funcionalidades básicas de CRUD
La aplicación permite al usuario crear, leer, actualizar y eliminar notas. Esto se logra utilizando las operaciones CRUD (Create, Read, Update, Delete) en la base de datos SQLite3 a través del framework Django.

## Autenticación de usuarios
La aplicación cuenta con un sistema de login que permite a los usuarios registrarse e iniciar sesión en la aplicación. Esto proporciona seguridad y control de acceso a las funcionalidades de la aplicación.

## Protección de rutas
Se implementa una protección de rutas para asegurar que ciertas páginas o funcionalidades solo sean accesibles por usuarios autenticados. Esto se logra utilizando decoradores en las vistas de Django para verificar la autenticación del usuario antes de permitir el acceso a una ruta específica.

## Diseño con Bootstrap
La aplicación utiliza Bootstrap para el diseño y estilo de la interfaz de usuario, proporcionando una apariencia moderna y responsive.



