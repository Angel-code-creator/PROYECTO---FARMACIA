PÁGINA WEB DE GESTIÓN DE FARMACIA
----------------------------------
Consiste en la creación de Un sistema para gestionar una farmacia, incluyendo inventario y ventas.

TECNOLOGÍAS USADAS
-------------------
Para la creación de este proyecto se ha utilizado Laravel version 12, Bootstrap 5, el SIGBD Postgre. Todo ello, implementado con HTML.

INTEGRANTES
-----------

 - Vásquez Soto, Jesús Alonso
 - Vega Quiroz, Ángel Joseph

CONFIGURACIÓN DE LA BD
----------------------

Se tiene que editar el archivo denominado ".env" de la siguiente manera:

DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=FARMACIA
DB_USERNAME=postgres
DB_PASSWORD=

MIGRACIÓN DE LA BD
------------------
Para realizar la migración, se ha de digtar en la terminal el siguiente código:

php artisan migrate --seed

EJECUTAR EL SERVIDOR
--------------------
Para el arranque y visualización del proyecto, se ha de escribir el siguiente comando en la terminal:

php artisan serve

Posteriormente, ingresa a tu navegador, En la sección de URL digitar "localhost:8000" y listo.

MÓDULOS
------- 
El proyecto cuenta con las tablas Meidcamentos, Pedidos, Detalles_Pedidos,Proveedores, Ventas, Detalle_Ventas, Prescripciones y Detalle_Prescripciones.

![Diagrama de BD](https://github.com/user-attachments/assets/960ea373-77fe-42f0-8c83-18d0c8888e0c


