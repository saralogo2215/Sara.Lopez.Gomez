# Web personal

Web estática (HTML + CSS, sin herramientas de compilación) publicada con GitHub Pages.
Disponible en español (raíz) e inglés (carpeta `en/`).

## Estructura

```
web-personal/
├── index.html              Inicio (ES)
├── cv.html                 Currículum (ES)
├── investigacion.html      Líneas de investigación (ES)
├── publicaciones.html      Publicaciones (ES)
├── blog/
│   ├── index.html          Lista de entradas (ES)
│   └── AAAA-MM-DD-titulo.html   Una entrada por archivo
├── en/                     Las mismas páginas en inglés
│   ├── index.html, cv.html, research.html, publications.html
│   └── blog/
├── assets/
│   ├── css/style.css       Estilos (colores y fuentes al principio)
│   ├── js/main.js          Botón de modo claro/oscuro
│   ├── img/                Imágenes (sustituye foto.svg por tu foto)
│   └── docs/               PDFs (pon aquí cv.pdf)
├── 404.html                Página de error
└── .nojekyll               Indica a GitHub que sirva los archivos tal cual
```

## Ver la web en tu ordenador

Haz doble clic en `index.html` y se abrirá en el navegador.

## Tareas habituales

**Cambiar tus datos:** busca `Tu Nombre` / `Your Name` y los textos entre `[corchetes]` en cada página.

**Poner tu foto:** copia tu foto en `assets/img/` (por ejemplo `foto.jpg`) y en `index.html` y `en/index.html` cambia `foto.svg` por `foto.jpg`.

**Subir tu CV en PDF:** guárdalo como `assets/docs/cv.pdf`.

**Añadir una entrada al blog:**
1. Duplica `blog/2026-10-19-bienvenida.html` y renómbralo, p. ej. `blog/2026-11-02-mi-entrada.html`.
2. Cambia título, fecha y texto.
3. Añade un bloque `<li class="entry">` al principio de la lista en `blog/index.html` (y, si quieres, en la portada).
4. Repite en `en/blog/` para la versión en inglés. Actualiza el enlace del botón `EN`/`ES` de cada entrada para que apunte a su traducción.

**Añadir una publicación:** copia un bloque `<li class="entry">` en `publicaciones.html` y `en/publications.html`.

## Publicar cambios (GitHub Desktop)

1. Edita y guarda los archivos.
2. En GitHub Desktop verás los cambios. Escribe un resumen abajo a la izquierda y pulsa **Commit to main**.
3. Pulsa **Push origin**. En 1–2 minutos los cambios estarán en línea.
