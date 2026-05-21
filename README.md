# Análisis de Ventas - Superstore Dataset 📊

Este proyecto consiste en un análisis exploratorio de datos (EDA) completo y una etapa de visualización utilizando un dataset de ventas de una "Superstore" (Kaggle). El objetivo principal es transformar datos brutos en insights de negocio accionables para optimizar la toma de decisiones.

## 🛠️ Tecnologías y Herramientas
* **Lenguaje:** Python 3
* **Entorno:** Jupyter Notebook
* **Librerías principales:** * `Pandas`: Carga, limpieza y manipulación de estructuras de datos.
  * `Matplotlib`: Creación de la base de las visualizaciones geográficas y temporales.
  * `Seaborn`: Estilizado avanzado de gráficos profesionales (`whitegrid`).

## 📈 Resumen Estadístico del Dataset
Al realizar la exploración inicial del volumen de datos (`train.csv`), se obtuvieron las siguientes métricas clave:
* **Total de pedidos analizados:** 9,800
* **Ciudades cubiertas:** 529
* **Clientes únicos:** 793
* **Venta media por pedido:** $230.77
* **Venta máxima:** $22,638.48
* **Venta mínima:** $0.44

## 🚀 Conclusiones del Análisis de Negocio
A través de las 5 visualizaciones profesionales generadas en el notebook, se identificaron los siguientes puntos estratégicos:

1. **Categoría más rentable:** *Technology* es la categoría con más ventas totales, seguida de *Furniture* y *Office Supplies*.
2. **Estacionalidad:** Noviembre es el mes con mayor volumen de facturación, impulsado probablemente por la campaña de Black Friday. Se recomienda reforzar stock y campañas de marketing previas (octubre-noviembre).
3. **Ciudades clave:** *New York*, *Los Angeles* y *Seattle* concentran la mayor parte de las ventas, consolidándose como mercados prioritarios.
4. **Segmento principal:** El segmento *Consumer* representa más del 50% de las compras totales, seguido por *Corporate* y *Home Office*.
5. **Región más fuerte:** La región del oeste (*West*) lidera en ventas totales a nivel nacional.

## 📂 Estructura del Repositorio
* `Analisis_de_Ventas.ipynb`: Notebook principal con todo el código documentado, análisis y gráficos.
