Plantilla base HTML
=====================

Descripción
-----------
Archivo: `plantilla-base.html`

Plantilla mínima y accesible para empezar a programar en HTML dentro de este proyecto. Incluye:
- Estructura semántica (header, nav, main, aside, footer).
- Enlaces a `./css_scss/styles.css` y `./js/index.js` (ajusta rutas si tus archivos están en otra carpeta).
- Formulario de ejemplo y pautas rápidas de accesibilidad.

Cómo probarla localmente
------------------------
1. Abre el archivo `plantilla-base.html` con el navegador haciendo doble clic.

2. (Recomendado) Levanta un servidor local para evitar restricciones de CORS o problemas al usar fetch/imports. En PowerShell o CMD (Windows) desde la carpeta del proyecto ejecuta:

```powershell
python -m http.server 8000
```

Luego abre en tu navegador: `http://localhost:8000/plantilla-base.html`

Siguientes mejoras sugeridas
---------------------------
- Mover estilos inline a `css_scss/styles.css` y añadir una hoja para variables/colores.
- Añadir un archivo `manifest.json` y favicons adecuados.
- Crear plantillas parciales (header/footer) si usas un motor de plantillas o Pug.

Contacto
--------
Si quieres, puedo:
- Añadir un script para descargar el HTML generado.
- Generar variantes (plantilla con grid CSS, plantilla con Tailwind, etc.).
- Añadir linting y tareas de build simples.

