# LUNA — Boutique de carteras

Tienda boutique minimalista en **HTML, CSS y JavaScript sin frameworks**, adaptable a celular y escritorio. Paleta verde oliva, negro cálido, crema y lino. No requiere instalación ni compilación.

## Abrir

Abrí `index.html` en tu navegador o serví la carpeta con:

```bash
python -m http.server 8080
```

Luego visitá `http://localhost:8080`.

## Qué incluye

- Home editorial, colección filtrable por categoría, búsqueda y ordenamiento.
- Ocho productos de ejemplo, ficha ampliada, favoritos y carrito con cantidades persistidas en `localStorage`.
- Preparación de pedido con descarga `.txt` o copiado al portapapeles.
- Menú móvil, ventanas accesibles, navegación por teclado, respeto de preferencias de movimiento reducido.
- Fotografía de referencia cargada desde Unsplash; SVG local como respaldo si una imagen falla.

## Importante antes de vender

Este proyecto es un **prototipo de tienda**, no una tienda habilitada para cobros: catálogo, modelos, precios, fotos y disponibilidad son **ilustrativos**. El resumen no se envía a ningún comercio, no almacena datos de clientes y no realiza pagos. Antes de publicar con fines comerciales necesitás reemplazar el catálogo de `script.js` por productos y fotografías de la marca, definir inventario y medios de contacto, e integrar un checkout real (por ejemplo, Mercado Pago mediante backend seguro), más términos y política de privacidad correspondientes. No coloques credenciales privadas en JavaScript del navegador.

Las fotografías de Unsplash son referenciales y requieren conexión a internet. Verificá licencia y pertinencia de cada imagen antes de usarla comercialmente. Google Fonts es una dependencia externa de tipografía.

## Archivos

- `index.html`: estructura y accesibilidad
- `styles.css`: diseño responsive
- `script.js`: productos e interacciones
- `assets/favicon.svg` y `assets/bag-fallback.svg`: recursos locales

© 2026 — Demo visual LUNA.