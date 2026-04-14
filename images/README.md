# Imágenes del Linktree

Añade aquí dos imágenes para que el linktree muestre tus fotos reales:

## 1. `hero.jpg` — Fondo panorámico
- **Qué es:** la foto panorámica que se ve detrás de todo el contenido.
- **Recomendación:** la foto del paisaje rocoso con el mar o la de la furgo al atardecer, en **formato horizontal**.
- **Resolución sugerida:** 1920×1080 px o mayor, comprimida (JPG ~300–500 KB).
- **Ruta final:** `./images/hero.jpg`

## 2. `profile.jpg` — Foto de perfil circular
- **Qué es:** la foto redonda centrada arriba, sobre el nombre.
- **Recomendación:** recorte cuadrado (**1:1**) donde se te vea de cerca.
- **Resolución sugerida:** 400×400 px, JPG.
- **Ruta final:** `./images/profile.jpg`

---

## Cómo subirlas

Opción rápida desde la web de GitHub:

1. Entra al repo en GitHub
2. Navega a la carpeta `images/`
3. Haz clic en **Add file → Upload files**
4. Arrastra `hero.jpg` y `profile.jpg`
5. Commit

O desde local:

```bash
cp /ruta/a/tu-foto-paisaje.jpg images/hero.jpg
cp /ruta/a/tu-foto-perfil.jpg  images/profile.jpg
git add images/
git commit -m "Add hero and profile images"
git push
```

## Fallback automático

Si las imágenes aún no están, el linktree funciona igual mostrando un **gradiente de tus colores de marca** (Azul Suave → Arena Dorada → Naranja Tierra) como fondo. Así siempre queda bonito aunque estés en medio de subirlas.
