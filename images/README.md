# Imágenes del Linktree

La página usa esta imagen como portada principal:

## `IMG_1092.jpg` - portada del perfil

- **Qué es:** la foto grande que aparece como fondo del Linktree.
- **Ruta final:** `./images/IMG_1092.jpg`
- **Variantes optimizadas:** `IMG_1092-900.webp`, `IMG_1092-1400.webp` y `IMG_1092-1892.webp`.

El HTML no rota la foto ni crea recortes destructivos. La imagen se renderiza como una capa fija detrás del contenido y se levanta por CSS, aumentando también el alto de esa capa, para que la cara quede más cerca de la parte superior en móvil, tablet y ordenador sin dejar huecos de fondo. El navegador usa WebP cuando puede y conserva el JPG como fallback.

## Fallback automático

Si la imagen todavía no existe, la página sigue funcionando con un degradado usando tu paleta:

- Turquesa Mar
- Azul Suave
- Arena Dorada
- Naranja Tierra
- Cálido Suave
