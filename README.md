Descripción del Proyecto

Este proyecto consiste en el desarrollo de una API REST para la gestión de productos de una tienda online. La aplicación permitirá administrar el catálogo de productos mediante operaciones CRUD (Crear, Leer, Actualizar y Eliminar), garantizando la seguridad de la información a través de un sistema de autenticación y almacenando los datos en la nube utilizando Firebase Firestore.

La solución fue diseñada siguiendo una arquitectura en capas, con el objetivo de mantener una estructura organizada, escalable y de fácil mantenimiento. Cada capa cumple una responsabilidad específica, facilitando futuras ampliaciones y modificaciones sin afectar al resto de la aplicación.

Objetivos
Gestionar un catálogo de productos mediante una API REST.
Implementar operaciones CRUD sobre los productos.
Incorporar autenticación para proteger los endpoints.
Almacenar la información en Firebase Firestore.
Aplicar una arquitectura escalable y modular.
Separar responsabilidades mediante capas bien definidas.
Funcionalidades
Gestión de Productos

La API permite:

Crear nuevos productos.
Obtener todos los productos registrados.
Consultar un producto específico por su ID.
Actualizar la información de un producto existente.
Eliminar productos del catálogo.
Autenticación

Se implementa un sistema de autenticación basado en Firebase Authentication para:

Validar usuarios autorizados.
Restringir el acceso a las operaciones protegidas.
Garantizar la seguridad de los datos almacenados.
Tecnologías Utilizadas
Node.js
Express.js
Firebase
Firestore Database
Firebase Authentication
JavaScript (ES Modules)
dotenv        
cors
