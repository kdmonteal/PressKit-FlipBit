# Press kit de FlipBit · kdmonteal.studio

Press kit generado con [presskit.html](https://github.com/pixelnest/presskit.html).

- `data.xml` + `images/` → página del estudio (kdmonteal.studio)
- `flipbit/data.xml` + `flipbit/images/` → página de FlipBit
- `build/` → el sitio listo para publicar (no se edita a mano)

## Cambiar textos o imágenes

1. Edita los `data.xml` o reemplaza imágenes en las carpetas `images/`.
   - `header.png` = banner, `logo.png` = logo, `icon.png` = ícono.
   - Cualquier otra imagen (png, jpg, gif) aparece en la galería.
2. Vuelve a generar el sitio (necesitas Node.js):

   ```bash
   npx presskit@0.14.0 build -D -L -M .
   ```

3. Haz commit y push. GitHub Pages publica la carpeta `build/` automáticamente.

## Publicar en GitHub Pages (solo la primera vez)

En GitHub: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
El press kit queda en `https://kdmonteal.github.io/PressKit-FlipBit/` y FlipBit en `.../flipbit/`.
