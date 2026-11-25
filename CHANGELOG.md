# Historial de cambios

## 2026-11-25 — Corrección de importación web

Integrado mediante [PR #2](https://github.com/DavidT2301/Historias/pull/2).

### Corregido
- Recuperación de resultados JavaScript con emscripten.run_script_string().
- Conversión de imágenes Base64 a objetos im.Data y miniaturas compatibles.
- Separación de archivos locales y web, incluyendo apertura de textos.
- Gestión de archivos pendientes mediante cola y avisos de errores.

### Añadido
- Visores web de video y PDF.
- Validación de extensiones y límite de 20 MB por archivo.
- Identificación de imágenes por hash SHA-256.

### Pendiente de validar
- Prueba interactiva completa de carga, apertura y papelera en navegador.
- Compatibilidad de códecs, PDF y dispositivos.
- Persistencia de archivos entre sesiones.

La historia y el diseño general no se modificaron en esta corrección.
