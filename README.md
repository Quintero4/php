# php
Buscador de películas procesado en php

Este es un proyecto simple que permite buscar información sobre películas utilizando una interfaz web. El proyecto está construido con **HTML**, **CSS** y **PHP**, y utiliza la API de [OMDb](http://www.omdbapi.com/) para obtener datos sobre películas.

---

## Características

- **Búsqueda de películas**: Introduce el nombre de una película y obtén detalles como el título, año, director, actores, sinopsis y calificación.
- **Interfaz sencilla**: Diseño limpio y fácil de usar.
- **Responsive**: La interfaz se adapta a diferentes tamaños de pantalla.

---

## Cómo usar

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tuusuario/buscador-peliculas.git

2.Abre el proyecto:

Navega a la carpeta del proyecto:

bash
Copy
cd buscador-peliculas

3.Configura la API:

Obtén una clave API gratuita de OMDb API.

Reemplaza TU_CLAVE_API en el archivo index.php con tu clave API.

4.Ejecuta el servidor:

Si estás usando XAMPP, WAMP o Laragon, coloca la carpeta del proyecto en la carpeta htdocs y accede a:

Copy
http://localhost/buscador-peliculas/index.php
Busca una película:

Introduce el nombre de una película en el campo de búsqueda y haz clic en "Buscar".

Estructura del proyecto
Copy
buscador-peliculas/
├── index.php          # Archivo principal con la lógica de búsqueda y la interfaz.
├── README.md          # Este archivo.
└── styles.css         # Estilos CSS para la interfaz.
Requisitos
Servidor web con soporte para PHP (por ejemplo, XAMPP, WAMP o Laragon).

Conexión a Internet para acceder a la API de OMDb.

Existe la opción de verlo sin conexión a la red local gracias al hosting gratuito ****** quintero.free.nf *******

