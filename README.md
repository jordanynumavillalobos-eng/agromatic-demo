# AGROMATIC — Demo web estática

Demo de las páginas **Inicio, Nosotros, Productos y Contáctanos** lista para GitHub Pages.

## Publicación

1. Crear un repositorio público `agromatic-demo` en GitHub.
2. Subir **el contenido de esta carpeta** a la raíz de la rama `main`, incluido `index.html`.
3. En GitHub: `Settings > Pages > Build and deployment > Deploy from a branch`.
4. Elegir `main` y `/(root)`; guardar.
5. Abrir `https://TU-USUARIO.github.io/agromatic-demo/`.

Si utilizas GitHub Desktop, crea un repositorio en esta carpeta y publica `main`.

## Alcance y límites

- El sitio es **100 % estático**: HTML, CSS, imágenes y archivos JSON.
- El formulario de Contáctanos **no envía correos reales**; es una demostración visual.
- El buscador filtra el catálogo local y las tarjetas de productos son de demostración.
- Algunas asociaciones de fotografías del catálogo son provisionales, según el material de origen.
- El mapa depende de Google Maps y el botón WhatsApp abre el servicio externo.
- No incluye el Laravel original, base de datos, `.env`, controladores ni claves.
- `noindex` evita solicitar indexación en buscadores, pero el enlace y el repositorio serán públicos.
- Antes de compartir, confirma que la empresa autoriza el uso público de las fotografías y contenidos.

## Prueba local

Abre la carpeta con VS Code > Live Server, o ejecuta `python -m http.server 8000` desde ella.
Entra a `http://localhost:8000/` y prueba los enlaces de Inicio, Nosotros, Productos y Contáctanos.
