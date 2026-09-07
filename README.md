# Vet AI

Interfaz web de Vet AI.

## Publicación de la interfaz

Este repositorio contiene la página `index.html`, preparada para publicarse con GitHub Pages.

La interfaz todavía necesita dos elementos antes de funcionar en internet:

1. Una copia de la carpeta `icons/` junto a `index.html`, para mostrar los iconos de especies y especialidades.
2. Un backend FastAPI privado accesible mediante HTTPS. En la versión local, la aplicación consulta `http://127.0.0.1:8000/ask`; antes de publicar hay que sustituir esa dirección por el dominio privado del backend.

No debe subirse al repositorio ninguna clave, archivo `.env`, base de datos, libro o contenido clínico con licencia.
