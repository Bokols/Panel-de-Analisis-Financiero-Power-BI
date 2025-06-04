💼 **Panel de Análisis Financiero**

Un proyecto en Power BI que simula un panel financiero y operativo para una empresa de gestión de residuos usando datos sintéticos.

📌 **Resumen del Proyecto**

Como parte de mi portafolio de ciencia de datos, desarrollé un panel financiero y operativo integral para una empresa ficticia de gestión de residuos en Chile. El conjunto de datos fue generado 100% de forma sintética para simular condiciones financieras y operativas realistas, como estructuras de costos, retrasos en servicios, pagos tardíos y rentabilidad en múltiples regiones.

El panel fue construido en Power BI Desktop, con énfasis en un diseño UX/UI moderno, interactividad y narración de datos. Permite a los tomadores de decisiones obtener rápidamente insights accionables sobre la salud financiera y el desempeño operativo.

[🖋️ **Ver Capturas del Panel (PDF)**](https://github.com/Bokols/Panel-de-Analisis-Financiero-Power-BI/blob/main/Panel%20de%20An%C3%A1lisis%20Financiero%20%E2%80%93%20Empresa%20de%20Gesti%C3%B3n%20de%20Residuos%20(Conjunto%20de%20Datos%20Sint%C3%A9tico).pdf)

🔧 **Lo que Hice**

1️⃣ **Conexión a Datos**

- Importé datos sintéticos desde Excel.  
- Limpieza, filtrado y remodelado con Power Query.  
- Verifiqué tipos de datos y apliqué transformaciones.

2️⃣ **Modelado de Datos**

- Definí relaciones entre tablas de hechos y dimensiones.  
- Creé columnas calculadas y medidas DAX.  
- Construí jerarquías, lógica de ordenamiento y formateo adecuado.

3️⃣ **Creación de Visuales**

- Visuales interactivos como:  
  Tarjetas KPI  
  Gráficos de líneas y áreas  
  Barras apiladas  
  Tablas matriz con drill-down  
  Mapas geográficos  
  Gráficos de dona y pie  
- Aplicación de temas consistentes y etiquetas claras para la narrativa.

4️⃣ **Agregar Interactividad**

- Filtros (slicers) por región, tipo de servicio, tipo de cliente, tipo de contrato y estado de facturación.  
- Habilitación de drill-through, resaltado cruzado y filtros.  
- Uso de marcadores y botones toggle para narrativa dinámica.

5️⃣ **Revisión y Optimización**

- Verificación de lógica DAX, comportamiento de filtros y visuales.  
- Uso de Performance Analyzer para optimizar tiempos de carga.  
- Diseño limpio basado en cuadrícula para respuesta en escritorio y móvil.

🧠 **Objetivos Clave**

- Proveer una visión financiera ejecutiva.  
- Permitir análisis detallado por servicio, región y cliente.  
- Destacar tendencias de rentabilidad, precisión de pronósticos y salud de facturación.  
- Asegurar un diseño moderno y responsivo.  
- Usar DAX avanzado para simular lógica real de negocio.

📁 **Páginas y Funciones del Panel**

🧐 1. Resumen Ejecutivo – Insights a simple vista  
✅ Tarjetas KPI  
💰 Ingresos Totales: $221M  
📉 Costos Totales: $170M  
📈 Utilidad Neta: $33M  
🔮 Utilidad Neta Pronosticada: $33M  
📊 Margen Promedio: 15%  
⚙ Utilidad por Servicio: $16K  
📂 Ingresos vs Costos en el Tiempo  
Gráfico de líneas suave con tooltip  
🌍 Rentabilidad por Región  
Mapa de Chile con colores condicionales  
🧁 Desglose de Servicios (Dona/Barras)  
Recolección, Transporte, Disposición Final

📊 2. Desglose de Ingresos y Costos  
Matriz drill-down por Tipo de Servicio > Región > Cliente  
Gráficos de barras apiladas y de pie

📈 3. Pronóstico y Tendencias  
Líneas de utilidad pronosticada vs real  
Matriz de pronóstico regional  
Gráficos combinados con tendencias acumuladas

🤝 4. Análisis de Clientes y Contratos  
Tipos de contrato y segmentación de clientes  
Tasas de descuento y comportamiento de facturación

⚙ 5. Desempeño Operativo  
Análisis de retrasos por tipo de servicio  
Métricas de servicios peligrosos y reciclables

📋 6. Análisis de Pagos y Facturación  
Retrasos en pagos, totales de facturas, uso de métodos  
Comportamiento de descuentos por método de pago  
Top 10 servicios facturados

🛠️ **Tecnologías Utilizadas**

| Herramienta      | Propósito                        |  
|------------------|---------------------------------|  
| Power BI         | Diseño del panel, modelado de datos |  
| DAX              | KPIs, inteligencia temporal, pronósticos |  
| Visuales personalizados | KPI Indicator, Chiclet Slicer, Mapbox |  
| Python (offline) | Generación de datos sintéticos  |

🧪 **Generación y Modelado de Datos**

Construido con datos 100% sintéticos que simulan:  
- Operaciones multi-región  
- Estructuras de costos, tipos de facturación  
- Tendencias pronosticables  
- Atributos realistas de servicios  

Limpiados, validados y tipados en Power BI. Se evitaron nulos para simular un dataset listo para producción.

✅ ** Insights Clave

📍 - Biobío y Valparaíso aportan más del 40% de las ganancias.
💾 - La disposición final representa el 33% de las ganancias totales.
💸 - Servicios residenciales tienen alto volumen pero bajo margen.
⏱ - Más del 96% de los contratos presentaron pagos tardíos.
📉 - La utilidad neta bajó un 22.76% respecto al pronóstico el mes pasado.

🚀 ** Conclusión

Este proyecto demuestra cómo DAX avanzado, modelado con datos sintéticos y diseño moderno de paneles pueden transformar datos operativos crudos en insights claros de negocio. Creado para exhibir en portafolio y como demostración práctica de inteligencia de negocios.
