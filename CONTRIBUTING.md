# Guía de colaboración

## Preparación
Usar Ren'Py 8.5.3 y una copia completa del proyecto con sus recursos. Mantener los scripts de main sincronizados con la carpeta game.

## Flujo de trabajo
1. Actualizar main antes de comenzar.
2. Crear una rama descriptiva (por ejemplo, fix/visor o feature/expediente).
3. Realizar cambios pequeños y commits descriptivos.
4. Ejecutar el análisis Lint de Ren'Py y probar localmente.
5. Abrir un Pull Request hacia main con descripción, archivos afectados y resultados de pruebas.
6. Revisar los cambios antes de integrarlos.

## Pruebas de importación
- Importar PNG/JPG y verificar miniatura y apertura mediante clic derecho.
- Importar TXT con caracteres especiales y verificar que se muestra correctamente.
- Probar video y PDF en navegador compatible.
- Probar archivos no admitidos, límite de tamaño, nombres repetidos y papelera.
- Confirmar que el flujo local no se rompe y que la historia sigue iniciando.

No presentar una compilación exitosa como prueba funcional completa. Documentar errores y limitaciones.

## Recursos y privacidad
No subir archivos personales, partidas guardadas, credenciales, registros locales ni archivos importados por usuarios. Incorporar únicamente recursos autorizados por sus titulares. Distribuir compilaciones ZIP mediante Releases, no mezclarlas con el código fuente.
