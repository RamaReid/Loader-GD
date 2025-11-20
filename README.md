# Loader-GD — Logo animations

Proyecto con las animaciones del logo (construcción doble y latido final).

Archivos principales:
- `Doble animacion GD.html` — flujo completo: doble montaje (2 pasadas) y, al terminar, el `heartbeat` que deja el logo en su estado final.
- `GDanimado.html` — versión base con el `heartbeat` aplicado por defecto (útil para pruebas y visualizaciones directas).
- `start_doble_then_base.html` — página alternativa que carga la animación inicial en un iframe y redirige como fallback.
- `css/style.css` — estilos y keyframes comunes.
- `img/` — imágenes (fondo y assets).

Cómo abrir localmente (desde la carpeta del proyecto):
```powershell
Start-Process '.\Doble animacion GD.html'    # flujo completo: doble montaje -> latido
Start-Process '.\GDanimado.html'             # vista base con latido
```

Si quieres publicar esto en GitHub Pages, crea la rama `gh-pages` con los archivos estáticos o habilita Pages desde `main` en la configuración del repo.

Autor: RamaReid
