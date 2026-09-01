# Repositorio Normativa Postgrados FAHU e IDEA

Sitio estático (GitHub Pages).

- `index.html` — plataforma pública de consulta, búsqueda y visor de PDF.
- `admin.html` — panel de actualización (documentos, usuarios, publicación).
- `data/normativa/catalogo.js` — catálogo único de documentos; única fuente de datos del sitio público.
- `data/normativa/pdf/` — documentos en PDF.
- `assets/logo-fahu.png` — logotipo institucional.

## Publicar un cambio
1. En el panel de actualización, editar o agregar documentos (los cambios quedan como borrador local del navegador).
2. Descargar `normativa.json` y volcar su arreglo de documentos en `data/normativa/catalogo.js` (constante `DOCS`).
3. Subir los PDF nuevos a `data/normativa/pdf/` y hacer push al repositorio.

Última generación: 2026-09-01T15:49:03.953Z
