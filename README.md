# Sistema de Control de Asistentes para la Biblioteca

¡Bienvenido al repositorio del proyecto de la Biblioteca! En este proyecto, el objetivo es desarrollar un sistema de control de asistentes que permita al personal de la biblioteca gestionar y realizar un seguimiento de la cantidad de personas presentes en cada momento. Cada asistente estará asociado a un nombre de superhéroe.

## Objetivo

El objetivo principal de este proyecto es proporcionar una plataforma eficiente y fácil de usar que permita al personal de la biblioteca gestionar y realizar un seguimiento de la ocupación en tiempo real. Esto incluye la creación de nuevos asistentes, la visualización de un tablero con la lista de asistentes, la capacidad de filtrar y ver solo aquellos presentes en la biblioteca, así como editar y eliminar asistentes cuando sea necesario.

## Tecnologías Utilizadas

Para lograr este objetivo, utilizaremos tecnologías modernas de desarrollo web:

- **Backend:** Usaremos **Express** y **Node.js** para construir el backend de nuestra aplicación, asegurando un flujo de datos eficiente entre el frontend y la base de datos.

## Levantar el Servidor

Para levantar el servidor vamos a correr el siguiente comando en una consola al nivel del index.js
```
node index.js
```
## Endpoints disponibles

Finalmente probamos los endpoints:
#### Postman Get Authors
```
localhost:3005/api/hero/
```
#### Get AutorFor Id
```
localhost:3005/api/hero/:id
```
#### Update Author
Verbo patch
```
localhost:3005/api/hero/update/:id
```
con el siguiente esquema de json:
```
{
    "first_name":"Capitan Python",
    "faction":"Python",
    "hp":50,
}
```
#### Create Author
```
localhost:3005/api/hero/create
```
con el siguiente esquema de json:
```
{
    "first_name":"Capitan Python",
    "faction":"Python",
    "hp":50,
}
```
#### Delete Author
```
localhost:3005/api/hero/delete/:id
```
