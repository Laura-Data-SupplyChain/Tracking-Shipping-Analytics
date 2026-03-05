# E-commerce Tracking & Shipping Analytics: Operaciones Internacionales

### Gestión de Visibilidad End-to-End: Del Seller a la Entrega Final
**Herramientas:** `Power BI (Advanced DAX)` | `Excel` | `E-commerce Logistics` | `SLA Monitoring`

---

## Objetivo del Proyecto
Simular la gestión operativa integral de una cadena de suministro e-commerce internacional (70 órdenes). El proyecto se enfoca en la trazabilidad total, desde la salida del **Seller** hasta la última milla, evaluando el cumplimiento de la promesa de entrega y la eficiencia de los proveedores logísticos globales.

## Metodología de Análisis (KPIs de Clase Mundial)
Para este modelo de control, se implementaron indicadores estándar de la industria:
1. **DOT (Delivery On Time %):** Medición exacta de pedidos entregados en la fecha pactada.
2. **Lead Time (LT):** Análisis del ciclo de tiempo promedio por país de origen (China, USA, España).
3. **CAS (Customer Affected Shipments %):** Identificación del volumen de órdenes con incidencias críticas que impactan la experiencia del usuario.

## Hallazgos y Diagnóstico Operativo (Insights)
* **Alerta de Nivel de Servicio:** Se detectó un **DOT del 50%**, lo que señala una oportunidad crítica de optimización en la coordinación entre Sellers y Transportadoras.
* **Cuellos de Botella en Origen:** El **"Retraso del Seller"** y **"Retraso en Aduanas"** representan las principales causas de incumplimiento (12 órdenes afectadas), sugiriendo la necesidad de una mejor auditoría de proveedores.
* **Desempeño de Carriers:** A pesar de ser líderes globales, el análisis revela que **DHL (54%)** y **FedEx/UPS (48%)** presentan variaciones significativas de cumplimiento en esta ruta específica.
* **Estacionalidad:** El pico operativo de **Marzo** demostró una correlación directa entre el aumento de volumen y la degradación del servicio.

## Propuestas de Optimización Logística
1. **Plan de Acción con Sellers:** Implementar penalizaciones o incentivos basados en el DOT para los Sellers con desempeño menor al 60% (Caso Seller_D).
2. **Estrategia de Aduanas:** Revisar la documentación pre-alerta para mitigar los retrasos en procesos de nacionalización.

---

## Estructura del Proyecto
* **data/**: Base de datos normalizada con flujo de órdenes internacionales.
* **powerbi/**: Dashboard interactivo con niveles de detalle:
   * **Página 1:** Resumen Ejecutivo (Indicadores Macro).
   * **Página 2:** Análisis Operativo (Drill-down por transportadora e incidencia).

---

### Enlaces de Interés
* [Descargar Reporte en PDF](/Power_BI/dashboard_tracking_shipping.pdf)
* [Ver Dashboard en Power BI Desktop](/Power_BI/dashboard_tracking_shipping.pbix)

**Autor** Laura M
