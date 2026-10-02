# EmbaMax — Gestión de local (MVP de demostración)

Prototipo navegable para mostrarle a EmbaMax (descartables, embalajes y envases, Río Ceballos) cómo funcionaría un sistema de gestión para el local.

> **Datos de ejemplo.** Productos, precios, stock y proveedores son inventados. El sistema no guarda nada: al recargar la página vuelve al estado inicial.

## Qué incluye

| Módulo | Qué muestra |
|---|---|
| **Inicio** | Vendido en el día, tickets, ventas por hora, lo más vendido y alertas de stock. |
| **Mostrador** | Búsqueda por nombre o código de barras, precio por cantidad automático (10/20/50/100 unidades), cobro con comprobante y descuento de stock. Mide los segundos por venta. |
| **Stock** | Existencias en salón y depósito, estado por producto, movimientos salón ← depósito y conteos que registran la diferencia con el sistema. |
| **Reposición** | Productos bajo mínimo agrupados por proveedor, redondeados al bulto de compra, con el mensaje de WhatsApp listo para copiar y registro de recepción. |
| **Cotizaciones** | Armado con precios por cantidad, mensaje para el cliente y conversión directa en venta. |

## Cómo verlo

Es un único archivo HTML sin dependencias de build.

- **Local:** abrir `index.html` en el navegador.
- **Online:** activar GitHub Pages en *Settings → Pages → Deploy from a branch → `main` / root*.

## Contexto

Esta demo acompaña la propuesta. El alcance final se define después de la visita al local, empezando por un piloto acotado: una familia de productos, un puesto de venta y un período corto.
