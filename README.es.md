# CreatorPulse Analytics

Dashboard académico de ejemplo para analizar comisiones y campañas de una creadora en Instagram, TikTok y YouTube.

## Abrir el proyecto

Abre `index.html` en un navegador. Tailwind CSS v4 se carga con el CDN indicado en el enunciado, por lo que hace falta conexión a Internet para que se apliquen los estilos.

## Tecnologías

- HTML5 semántico.
- Tailwind CSS v4 mediante `@tailwindcss/browser@4`.
- Sin JavaScript personalizado, frameworks, backend ni APIs.

## Datos de demostración

Se muestran 340 conversiones distribuidas entre tres plataformas y tres productos. Cada venta genera una comisión del 15 % sobre el precio:

| Producto | Precio | Comisión por venta | Ventas de ejemplo | Comisiones |
|---|---:|---:|---:|---:|
| A | 50 € | 7,50 € | 120 | 900 € |
| B | 120 € | 18 € | 100 | 1.800 € |
| C | 80 € | 12 € | 120 | 1.440 € |
| **Total** | — | — | **340** | **4.140 €** |

Los costes de campaña (2.200 € en total) son un supuesto creado para ilustrar ROI y coste por conversión. No representan gastos reales. Las métricas no proceden de cuentas conectadas.

## Métricas mostradas

- Tasa de conversión: conversiones ÷ alcance × 100 = 340 ÷ 274.000 × 100 ≈ 0,12 %.
- Engagement rate: interacciones ÷ alcance × 100 = 44.820 ÷ 274.000 × 100 ≈ 16,36 %.
- ROI: (comisiones − coste publicitario) ÷ coste publicitario × 100 = (4.140 − 2.200) ÷ 2.200 × 100 ≈ 88,2 %.
- Las comisiones por plataforma y producto suman 4.140 €. Las ventas brutas serían 27.600 € y no deben confundirse con las comisiones recibidas.

## Secciones

1. KPIs principales.
2. Drivers: comisiones por plataforma, embudo y rendimiento por producto.
3. Tablas de productos, plataformas y campañas, más alertas con oportunidades.

El diseño es mobile-first y utiliza breakpoints `sm`, `xl` y `2xl`. Las tablas usan contenedores con desplazamiento propio en pantallas estrechas.

## Limitaciones

Los filtros y el selector de periodo son elementos visuales; no filtran datos. No hay conexión ni sincronización automática con redes sociales. Las variaciones respecto al periodo anterior son ilustrativas.
