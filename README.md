# Tracking & Shipping Analytics – Operaciones Internacionales E-commerce
Proyecto de análisis aplicado a una operación internacional de e-commerce, simulando la gestión integral de 70 órdenes desde la compra hasta la entrega al cliente final.

Se realizó seguimiento a la operación de Tracking (Seller → Despacho) y Shipping (Despacho → Entrega), evaluando cumplimiento de promesa, desempeño por seller, transportadora y principales causas de incumplimiento, mediante construcción de indicadores clave (DOT, LT, CAS) y dashboard interactivo en Power BI.

## Objetivos

- Simular la gestión operativa de pedidos internacionales en entorno e-commerce.
- Analizar el cumplimiento de promesa de entrega (Delivery On Time – DOT).
- Evaluar Lead Time promedio por país de origen.
- Identificar principales incidencias que afectan la operación.
- Detectar oportunidades de mejora en sellers y transportadoras.
- Construir dashboard ejecutivo para toma de decisiones operativas.

## Estructura de Archivos

- /data
  - tracking_shipping_falabella.xlsx

- /powerbi
  - dashboard_tracking_shipping.pbix

## KPIs Analizados

- Total de órdenes procesadas
- Delivery On Time (DOT %)
- Lead Time promedio (LT)
- Customer Affected Shipments (CAS %)
- Retraso promedio (días)
- DOT por Seller
- DOT por Transportadora
- Incidencias por tipo
- Tendencia de volumen por mes

## Herramientas Utilizadas

Excel (limpieza de datos, cálculos y validación) | Power BI (modelado de datos, medidas DAX, visualización y dashboards) | Construcción de KPIs logísticos | Análisis operativo internacional

## Principales Hallazgos

- Se analizaron 70 órdenes internacionales.
- DOT promedio de 50%, evidenciando oportunidad clara de mejora operativa.
- CAS del 50%, indicando que la mitad de los pedidos presentó alguna afectación.
- Lead Time promedio de 14,97 días (~15 días), consistente entre países de origen.
- Seller_D presentó el menor desempeño con 57% de cumplimiento.
- Las principales causas de incumplimiento fueron Retraso en Aduana y Retraso del Seller (12 órdenes afectadas).
- DHL mostró el desempeño más bajo (54% DOT), seguido por FedEx y UPS (48%).
- Marzo concentró el mayor volumen operativo (31 órdenes), lo que podría explicar incremento en incidencias por carga operativa.

## Cómo Explorar el Proyecto

- Abrir el archivo Excel ubicado en la carpeta /data para revisar la base de datos simulada.
- Abrir el archivo .pbix en la carpeta /powerbi para visualizar el dashboard interactivo.
- Explorar la Página 1 (Resumen Ejecutivo) para indicadores generales.
- Analizar la Página 2 (Análisis Operativo) para identificar patrones por seller, transportadora y tipo de incidencia.
- Utilizar filtros dinámicos para segmentar por país, seller o transportadora.

**Autor** Laura M
