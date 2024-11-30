Proyecto Adopt Me

Este es el proyecto Adopt Me, una aplicación para gestionar las adopciones de mascotas.

Endpoints

Adopciones

Obtener todas las adopciones

GET /adoptions

Obtener una adopcion

GET /adoptions/:aid

Crear una adopcion

POST /adoptions/:uid/:pid

Usuarios

Obtener todos los usuarios

GET /users

Obtener un usuario

GET /users/:uid

Actualizar un usuario

PUT /users/:uid

Eliminar un usuario

DELETE /users/:uid

Mascotas

Obtener todas las mascotas

GET /pets

Obtener una mascota

GET /pets/:pid

Actualizar una mascota

PUT /pets/:pid

Eliminar una mascota

DELETE /pets/:pid

Imagen de Docker

https://hub.docker.com/layers/testdev34/adopt-me/v1/images/sha256-7b5d02b864e169b43344c3daaee4b4e98f29b50cbd64471d1439d082cbbcd83b?context=repo

Docker

Puedes ejecutar este proyecto usando Docker.
Construir la imagen de Docker

    Asegúrate de tener Docker instalado en tu máquina.
    Clona este repositorio y navega a la carpeta del proyecto.
    Construye la imagen con el siguiente comando:

docker build -t testdev30/adopt-me:v1 .
