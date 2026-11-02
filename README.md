# Street Style SV

Prototipo de tienda web de ropa y accesorios con identidad visual salvadoreña. Permite explorar un catálogo y recorrer una experiencia de compra desde el navegador.

## Funciones
- Catálogo de productos con imágenes y precios.
- Carrito con cambios de cantidad, eliminación y cálculo de totales.
- Formulario de contacto y entrega con validación.
- Interfaz de selección de método de pago.
- Confirmación simulada y preparación de un resumen para compartir por WhatsApp.
- Navegación adaptable a móvil y animaciones de interfaz.

## Tecnologías
HTML, CSS y JavaScript en `index.html`, Tailwind CSS mediante CDN y Google Fonts. Las imágenes de productos se encuentran en la raíz.

## Ejecutar
Desde la raíz:
```bash
python -m http.server 8000
```
Abre `http://localhost:8000`. También puedes utilizar Live Server en VS Code. No hay instalación de paquetes ni proceso de compilación.

## Alcance del prototipo
El pago se simula mediante un temporizador: no existe integración con una pasarela bancaria, backend de pedidos o inventario persistente. Utiliza datos ficticios para probar el formulario de pago. El enlace de WhatsApp requiere revisar el destinatario configurado antes de reutilizar la tienda.

## Recorrido de demostración
Agrega productos, cambia sus cantidades, revisa el total y completa el checkout con datos de prueba. Esto permite mostrar manejo del DOM, estado del carrito y validación de formularios.
