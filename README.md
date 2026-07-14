🥬 Sano y Fresco – Data Analytics & Market Basket Model

📌 Descripción
Este proyecto implementa un flujo de ETL con Python para limpiar y transformar datos de ventas de la base sanoyfresco.db.
Posteriormente, se construye un modelo de la canasta (Market Basket Analysis) para identificar asociaciones entre productos y patrones de compra.
Los resultados se integran en un dashboard en Power BI que permite visualizar métricas clave de ventas, clientes y productos.

🚀 Funcionalidades
  -Conexión a base de datos SQLite y carga de datos con Pandas.
  -Limpieza de datos: conversión de tipos, eliminación de duplicados y validación de nulos.
  -Transformación de transacciones en formato matricial (0/1) para análisis de asociaciones.
  -Cálculo de métricas de soporte, confianza y lift entre productos.
  -Exportación de reglas de asociación a CSV para integración con Power BI.
  -Dashboard interactivo con KPIs de ventas, clientes y productos más vendidos.

🛠️ Tecnologías utilizadas
  -Python (Pandas, itertools)
  -SQLite
  -Power BI
  -ETL
  -Market Basket Analysis (Apriori-like)

📊 Resultados
Identificación de productos más frecuentes en pedidos (ej. Banana, Bolsa de Bananas Orgánicas, Fresas Orgánicas).

Reglas de asociación con alta confianza y lift (ej. Cilantro Orgánico → Limones con confianza del 25.4% y lift de 3.6).

Exportación de más de 390 reglas de asociación para análisis en Power BI.

Dashboard que resume ventas totales, clientes, ticket promedio y evolución mensual.
