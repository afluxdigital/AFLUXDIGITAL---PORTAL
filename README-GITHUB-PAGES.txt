AFLUX OS — VERSIÓN ESTÁTICA PARA GITHUB PAGES

ARCHIVOS PARA SUBIR AL REPOSITORIO:
- index.html
- aflux-logo.png
- .nojekyll
- este README (opcional)

IMPORTANTE:
GitHub Pages solo publica archivos estáticos. Esta versión permite abrir la interfaz de Aflux OS, pero no ejecuta los endpoints de servidor que estaban en /api.

Por tanto, las funciones que necesitan backend real (AURA con inteligencia completa, análisis remoto de URLs y búsqueda real de Google Places) requieren desplegar posteriormente el backend en un servicio compatible, como Vercel, y configurar sus variables de entorno allí.

El mapa de Google 3D también requiere una clave de Google Maps Platform válida y restringida al dominio publicado. No incluyas claves privadas de Google Places ni de OpenAI en este repositorio.

CÓMO PUBLICAR:
1. Descomprime este ZIP.
2. Sube los archivos que contiene directamente a la raíz de tu repositorio GitHub (no subas la carpeta contenedora).
3. En GitHub, abre Settings → Pages.
4. En Build and deployment, selecciona Deploy from a branch.
5. Selecciona la rama principal (normalmente main) y la carpeta /(root), y guarda.
6. Espera a que GitHub Pages publique la web.

Si el repositorio ya contiene una versión anterior, reemplaza index.html y aflux-logo.png por estos archivos.
