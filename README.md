## CRUD CON AWS

Crear un CRUD (Create, Read, Update, Delete) en AWS permite aprovechar varios servicios de la plataforma para construir una aplicación completa con funcionalidades de gestión de datos.

** Configurar una instancia de RDS:**
- Selecciona MySQL como motor de base de datos.
- Ajusta la capacidad de la instancia de acuerdo con los requisitos de tu aplicación.
- Especifica un nombre para la base de datos, junto con un usuario y una contraseña.
- Habilita la opción de acceso público.

**Configurar la base de datos:**
- Una vez que la instancia esté lista, puedes conectarte a MySQL usando un cliente como MySQL Workbench para crear las tablas necesarias para tu aplicación CRUD (por ejemplo, CREATE TABLE users...).

**Desarrollar funciones Lambda:**
- Create: Implementa la lógica para añadir un nuevo registro en la base de datos.
- Read: Implementa la lógica para leer registros de la base de datos.
- Update: Implementa la lógica para modificar registros existentes.
- Delete: Implementa la lógica para eliminar registros.

** Configurar API Gateway:**
- Define los endpoints para cada operación CRUD (POST, GET, PUT, DELETE).
- Asocia cada endpoint con su respectiva función Lambda.
- Configura CORS si planeas consumir la API desde un frontend.
