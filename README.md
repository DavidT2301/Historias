# Expediente213 — Historias interactivas

Proyecto multimedia desarrollado con Ren'Py. Presenta una novela visual mediante un escritorio virtual de estética retro, desde el cual se accede a expedientes, historias y archivos importados.

## Demostración y descargas

- [Versión web corregida en Netlify](https://stupendous-chebakia-5d6170.netlify.app/)
- [Versiones descargables (Releases)](https://github.com/DavidT2301/Historias/releases)

## Funcionalidades

- Narrativa interactiva, diálogos y decisiones.
- Escritorio virtual, expedientes y papelera.
- Importación y visualización de imágenes y textos.
- Visores web de video y PDF, sujetos a compatibilidad del navegador.
- Importación web limitada a 20 MB por archivo. Los archivos importados no tienen persistencia garantizada entre sesiones.

## Tecnologías

Ren'Py 8.5.3, Python, JavaScript, Emscripten/WebAssembly, GitHub y Netlify.

## Código fuente

| Archivo | Responsabilidad |
| --- | --- |
| script.rpy | Narrativa, gestión de archivos y puente JavaScript/Python |
| screens.rpy | Escritorio, interfaces, miniaturas y visores |
| gui.rpy | Estilos y configuración gráfica |
| options.rpy | Configuración del motor y compilación |

## Ejecutar localmente

1. Instalar [Ren'Py 8.5.3](https://www.renpy.org/release/8.5.3).
2. Obtener la carpeta completa del proyecto y sus recursos originales del equipo. Los cuatro scripts del repositorio por sí solos no bastan.
3. Copiar los scripts actualizados de la rama main a la carpeta game del proyecto, conservando los recursos originales.
4. Abrir el proyecto desde el Launcher de Ren'Py y seleccionar Launch Project.

## Compilar y desplegar en web

1. Instalar el complemento web correspondiente a Ren'Py 8.5.3.
2. Seleccionar Web (Beta) en el Launcher y generar la distribución web.
3. Descomprimir el resultado y publicar en Netlify la carpeta que contiene index.html.
4. Probar la importación y apertura de PNG/JPG, TXT, PDF y MP4 desde el escritorio virtual. Para abrir un archivo importado, utilizar clic derecho.
