# Cotizador YuranSnacks

Mini web app de una sola página para calcular el total de un pedido de YuranSnacks según el producto, la cantidad y el canal de entrega. Pensada para usarse desde el celular mientras se conversa con un cliente por WhatsApp.

## Qué hace

- Permite elegir un producto, indicar la cantidad (mínimo 1) y escoger el canal de entrega.
- Calcula el subtotal, el costo de entrega y el total.
- Genera un resumen del pedido y lo copia al portapapeles para pegarlo en WhatsApp.

## Productos y precios

| Producto | Precio |
|---|---|
| Barra Kiwicha y Cacao | S/ 8 |
| Barra Quinua Original | S/ 7 |
| Pack x5 Kiwicha y Cacao | S/ 35 |
| Pack x5 Quinua Original | S/ 30 |

| Canal de entrega | Costo |
|---|---|
| Recojo en punto de venta | Sin costo |
| Delivery en Lima | + S/ 5 |

## Cómo usarlo

No necesita instalación ni internet. Abre el archivo `index.html` con cualquier navegador.

## Cómo cambiar precios o productos

Abre `index.html` con un editor de texto. Al inicio de la sección de JavaScript están las listas `PRODUCTOS` y `CANALES`. Cambia un número para actualizar un precio, o agrega una línea para sumar un producto.

## Tecnologías

HTML, CSS y JavaScript en un solo archivo. Sin librerías externas, sin servidor y sin base de datos.

## Versión actual (v1) y lo que queda fuera

Esta versión es un MVP. Por ahora no incluye pagos en línea, registro de clientes, historial de pedidos, inicio de sesión ni control de inventario.
