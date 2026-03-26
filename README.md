# AVE Contenidos — Sitio Web

Sitio web oficial de **AVE Contenidos**, empresa de transmisión profesional en vivo de Mar del Plata, Argentina.

## 🚀 Publicar en GitHub Pages

### Paso a paso

1. **Crear el repositorio en GitHub**
   - Andá a [github.com/new](https://github.com/new)
   - Nombre sugerido: `ave-contenidos` (o el que prefieras)
   - Dejalo en **Public**
   - No marques ninguna opción extra → clic en **Create repository**

2. **Subir los archivos**
   - En la página del repo recién creado, hacé clic en **"uploading an existing file"**
   - Arrastrá o seleccioná el archivo `index.html` (y este `README.md` si querés)
   - Escribí un mensaje de commit, por ejemplo: `Primer deploy`
   - Clic en **Commit changes**

3. **Activar GitHub Pages**
   - Andá a **Settings** → **Pages** (en el menú lateral izquierdo)
   - En *Source*, seleccioná **Deploy from a branch**
   - En *Branch*, elegí `main` y carpeta `/ (root)`
   - Clic en **Save**

4. **¡Listo!** En 1-2 minutos tu sitio va a estar en:
   ```
   https://TU-USUARIO.github.io/ave-contenidos/
   ```

---

## 📝 Notas importantes

- **Galería de imágenes**: las fotos se guardan en el `localStorage` del navegador. Esto significa que cada visitante ve su propia galería local. Para compartir fotos entre todos los visitantes sería necesario un backend.
- **Panel admin**: las credenciales están en el código JavaScript (`ADMIN_USER` / `ADMIN_PASS`). No son secretas, cualquiera que vea el código puede leerlas.
- **Dominio propio**: desde *Settings → Pages* podés configurar un dominio personalizado (ej: `avecontenidos.com.ar`).

---

© 2025 AVE Contenidos — Mar del Plata, Argentina
