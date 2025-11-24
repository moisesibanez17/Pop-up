# Página de acceso rápido a Instagram

Pequeña página estática cuyo único fin es mostrar el Instagram del proyecto y un botón que redirige a otra web.

Archivos creados:

- `index.html` — la página principal (edita los enlaces aquí).
- `styles.css` — estilos con predominio del color amarillo.

Cómo usar:

1. Abre `index.html` en tu navegador (doble clic o arrástralo a una ventana del navegador).
2. Para cambiar el Instagram, edita la línea del enlace en `index.html` que contiene `https://instagram.com/tu_usuario` y reemplaza `tu_usuario` por el nombre real.
3. Para cambiar la URL donde redirige el botón, modifica la constante `targetUrl` en el script al final de `index.html`.

Cambios recientes:

- Se añadieron 3 tarjetas de Instagram que usan las imágenes de la carpeta `assets`:
	- `assets/GI WY.png` → tarjeta 1 (`tu_usuario_1`)
	- `assets/GD WY.png` → tarjeta 2 (`tu_usuario_2`)
	- `assets/GB WY.png` → tarjeta 3 (`tu_usuario_3`)
- La imagen `assets/DIFERENTE.png` ahora se muestra centrada en la página (solo visual, no está ligada a una cuenta).

Cómo editar las nuevas tarjetas:

- Abre `index.html` y reemplaza `tu_usuario_1`, `tu_usuario_2` y `tu_usuario_3` por los nombres reales de Instagram (o cambia las URLs por las cuentas deseadas).
- Si deseas usar otras imágenes, reemplaza las rutas en los atributos `src` de las etiquetas `<img>` dentro de las tarjetas.

Estética y alineación:

- La página ahora es mayormente amarilla: el fondo y la tarjeta usan una paleta amarilla/crema, con un acento amarillo más intenso en botones.
- Las tarjetas de Instagram están alineadas usando CSS Grid: en pantallas grandes aparecen en una fila de 3, en tabletas en 2 columnas y en móviles en 1 columna.

Accesibilidad y contraste:

- Se cuidó el contraste entre texto y fondo para mantener legibilidad con la paleta amarilla; puedes ajustar las variables CSS en `styles.css` si quieres otro tono.



Notas:

- La página es totalmente estática y no requiere servidor. Si deseas servirla desde un dominio, sube estos archivos al hosting.
- Si quieres que el botón reemplace la pestaña actual en lugar de abrir una nueva, reemplaza `window.open(targetUrl, '_blank', 'noopener')` por `window.location.href = targetUrl;` en `index.html`.# Pop-up
