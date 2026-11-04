# Planilla Docente

App web instalable (PWA) para llevar cursos, alumnos, asistencia, notas e informes.

## Archivos
index.html (la app) · manifest.json y sw.js (para instalarla y que ande sin internet) · icon-192.png e icon-512.png (ícono).

## Subirla a GitHub y usarla en el celular (gratis)
1. Descomprimí el zip (Mis archivos > mantené apretado el zip > Extraer).
2. Entrá a github.com e iniciá sesión.
3. Tocá **+** > **New repository**. Nombre: `planilla-docente`. Marcá **Public**. Tocá **Create repository**.
4. Tocá **uploading an existing file** y elegí los 5 archivos. Tocá **Commit changes**.
5. Entrá a **Settings > Pages**. En Branch elegí `main` y carpeta `/ (root)`. Tocá **Save**.
6. Esperá 1 o 2 minutos. Te va a mostrar el link: `https://TU-USUARIO.github.io/planilla-docente/`
7. Abrí ese link en Chrome > menú ⋮ > **Instalar app** (o **Agregar a pantalla principal**).

## Importante
- Los datos de alumnos NO están en el código: se guardan solo en el teléfono de cada docente. Por eso el repositorio puede ser público.
- La cámara (📷 Escanear lista) necesita internet la primera vez para bajar el lector de texto.
- Si se actualiza `index.html`, volvé a subirlo (Add file > Upload files) y reabrí la app.

## Cómo actualizar la app cuando se le agrega algo nuevo
1. Te paso un `index.html` nuevo (la versión sube, por ejemplo 1.2.0 a 1.3.0).
2. En GitHub, entrá al repositorio > **Add file > Upload files** y subí el archivo nuevo (reemplaza al viejo). **Commit changes**.
3. En la app: **Ajustes > Versión de la app > Buscar actualización**. Si hay una nueva, tocá **Actualizar**. Tus datos no se borran.
