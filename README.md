# MPMOTOS — Landing page

Landing page de una sola página para MPMOTOS, tienda de cascos para moto.
Sitio estático: un único archivo `index.html` sin dependencias externas ni build.

## Estructura

| Archivo | Qué es |
|---|---|
| `index.html` | Toda la landing: HTML, CSS e ilustraciones SVG en un solo archivo |
| `.gitignore` | Archivos que no se versionan |

## Ver en local

Abrí `index.html` con doble clic. No hace falta servidor ni instalar nada.

## Desplegar

Alojado en Vercel como sitio estático (sin framework, sin build). Cada `git push`
a la rama `main` publica una nueva versión automáticamente.

## Pendientes antes de salir a producción

Están marcados con `TODO` dentro de `index.html`:

- **WhatsApp**: reemplazar el placeholder `5491100000000` por el número real
  (formato internacional, sin `+` ni espacios). Aparece 3 veces.
- **Contacto**: mail y link de Instagram en el footer.
- **Precios y modelos**: los tres cascos usan precios de ejemplo ($129 / $189 / $249)
  junto con sus cuotas.
- **Testimonios**: son de ejemplo. Reemplazar por reseñas reales.
