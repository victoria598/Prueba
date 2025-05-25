# PRACTICA 1 - Modulo IV - Dev Ops

## 📌 Descripción General

Este proyecto es una práctica correspondiente al Módulo IV, cuyo objetivo es construir un sistema web con una arquitectura dividida en frontend y backend. La aplicación está diseñada para ejecutarse en un entorno local, simulando el uso de una base de datos mediante archivos JSON.


## 🌐 Requisitos de Ejecución

Para que el sistema funcione correctamente, debe ejecutarse en un servidor local que soporte PHP. Puedes usar cualquiera de los siguientes entornos:

- [XAMPP](https://www.apachefriends.org/index.html)
- [Laragon](https://laragon.org/)
- [MAMP](https://www.mamp.info/)

Ubica tu proyecto en la carpeta `htdocs` (o equivalente según el entorno) y accede desde el navegador:


---

## 🌿 Estructura de Ramas

Este proyecto utiliza un sistema de ramas para separar las diferentes áreas de desarrollo y mantener un flujo de trabajo organizado:

| Rama     | Rol                                                                 |
|----------|----------------------------------------------------------------------|
| `main`   | Rama principal. Contiene la versión final, estable y documentada.   |
| `frontend` | Contiene todo el desarrollo de la interfaz web con HTML + Bootstrap. |
| `backend`  | Implementación del servidor con PHP. Incluye lógica y manejo de JSON. |
| `developer`      | Rama de integración. Aquí se prueban los cambios antes de pasarlos a `main`. |

---

## 🗂️ Estructura del Proyecto

── 📁Practica1Modulo4
    └── 📁assets
        └── 📁images
            └── i1.png
            └── promocion.jpg
        └── 📁xml
            └── menu.xml
    └── 📁controller
        └── editar.php
        └── eliminar.php
        └── guardar.php
        └── obtenerdatos.php
    └── 📁database
        └── reservas.json
    └── 📁pages
        └── comunidad.html
        └── contacto.html
        └── extras.html
        └── faq.html
        └── index.html
        └── listareservas.php
        └── personalizacion.html
        └── recomendaciones.html
        └── reservas.html
    └── LICENSE
    └── README.md


---

## 🛠 Tecnologías Usadas

- **HTML5**
- **Bootstrap (CDN)**
- **PHP**
- **JSON** (para simular base de datos)
- **Servidor local** (XAMPP, Laragon, etc.)

---

## 👨‍💻 Autor

María Victoria Quintanilla Villanueva 
Módulo IV – Dev Ops 
