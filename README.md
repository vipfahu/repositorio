# Biblioteca Normativa de Postgrado — FAHU USACH

Sitio estático (GitHub Pages).

- `index.html` — plataforma pública de consulta y búsqueda.
- `admin.html` — panel de actualización (documentos, usuarios, publicación).
- `data/normativa/catalogo.js` — catálogo único de documentos (fuente de datos de ambas páginas).
- `data/normativa/pdf/` — documentos en PDF.

## Publicar un cambio
1. En el panel de actualización, editar o agregar documentos.
2. Descargar `normativa.json` y volcar su contenido en `data/normativa/catalogo.js` (arreglo `DOCS`).
3. Subir los PDF nuevos a `data/normativa/pdf/` y hacer push al repositorio.

Última generación: 2026-09-01T15:16:29.099Z
