# Río & Raíz — Catálogo demostrativo para feriantes de Neuquén

**Demo de LUNA Proyectos**, no de un comercio existente. Todos los nombres, precios, cantidades y textos comerciales son ficticios.

## Vista previa

Si GitHub Pages está configurado para publicar la raíz de la rama `main`, la página queda disponible en:

https://bitflowapp.github.io/luna-catalogo-demo-preview/feria-neuquen/

La demo original ubicada en la raíz de este repositorio **no se modifica**.

## Qué permite probar

- Diseño responsive para móvil y escritorio, 12 fichas y categorías.
- Búsqueda sin acentos, filtros de disponibilidad, ordenamiento por precio.
- Stock de muestra con estado agotado y aviso de pocas unidades.
- Bolsa de selección con control de cantidades y suma de importes.
- Mensaje armado para WhatsApp, sin destinatario fijo, o copiado al portapapeles.
- **Modo feriante**: editar unidades y restaurar los valores de ejemplo.

## Qué NO incluye

- **No hay stock sincronizado**: los cambios realizados en modo feriante se guardan en `localStorage` únicamente en ese dispositivo/navegador; otros visitantes verán el stock inicial.
- No hay checkout, cobros, reservas, envíos ni envío de mensajes automáticos.
- No hay panel autenticado o administración remota.
- Las fotos son referencias externas de Unsplash, no fotos del supuesto emprendimiento. Pueden necesitar reemplazo si cambian las URLs o condiciones del proveedor.
- Es un ejemplo comercial; **no** corresponde anunciar las cantidades como inventario real.

## Cómo reutilizarlo con otro feriante

1. Crear una copia del HTML en un directorio independiente dentro del hosting del cliente.
2. Cambiar marca, nombres, textos, categorías, precios, cantidades e imágenes en el arreglo `products` del script.
3. Reemplazar fotos referenciales por fotografías del negocio y alojarlas en el repositorio. Esto evita depender de URLs de terceros.
4. Cambiar `getOrder()` para quitar el aviso de demo. Configurar el número del vendedor en `https://wa.me/549...?` (solo después de verificar el número con el cliente).
5. Si necesita stock común entre varios dispositivos, presupuestar un backend o una integración confiable: GitHub Pages estático no proporciona sincronización de inventario por sí solo.

Sin librerías JS, base de datos ni build step. El catálogo HTML puede alojarse estáticamente en GitHub Pages, sujeto a los límites y políticas de GitHub.
