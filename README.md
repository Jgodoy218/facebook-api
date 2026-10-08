# 📱 Facebook API - Taller Backend

API REST desarrollada con **Laravel** como parte del taller de Backend.

El proyecto simula algunas de las funcionalidades principales de una red social,
permitiendo crear publicaciones, agregar imágenes, realizar comentarios,
dar "likes" y eliminar publicaciones.

---

## 🚀 Descripción del proyecto

Este proyecto fue desarrollado para poner en práctica la creación de una API
REST utilizando Laravel.

La API permite administrar publicaciones y realizar diferentes acciones sobre
ellas mediante diferentes endpoints.

Las pruebas de funcionamiento fueron realizadas utilizando **Postman**.

---

## 🛠️ Tecnologías utilizadas

- 🐘 PHP
- 🔥 Laravel
- 🗄️ MySQL
- 📬 Postman
- 🌐 API REST
- 🗃️ Eloquent ORM
- 📦 Composer
- 🔧 Git y GitHub

---

## ✨ Funcionalidades

Actualmente la API cuenta con las siguientes funcionalidades:

### 📝 Publicaciones

- Crear una publicación.
- Consultar las publicaciones.
- Consultar información de una publicación.
- Eliminar una publicación.

### 🖼️ Imágenes

- Permitir imágenes al crear una publicación.
- Validar el tipo de imagen.
- Guardar las imágenes utilizando el sistema de almacenamiento de Laravel.
- Generar la URL para acceder a las imágenes.

### 💬 Comentarios

- Agregar comentarios a una publicación.
- Registrar el autor del comentario.
- Registrar el contenido del comentario.

### ❤️ Likes

- Agregar likes a una publicación.
- Contabilizar la cantidad de likes recibidos.

---

# 🔗 Endpoints de la API

La API utiliza la siguiente dirección base:

```text
http://127.0.0.1:8000/api