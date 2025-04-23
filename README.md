Análisis de Datos - Mobiles Dataset (2025)

Este proyecto consiste en un análisis exploratorio de un dataset que contiene información sobre teléfonos móviles: precios de lanzamiento en distintos países, especificaciones como RAM, batería, cámaras, peso, pantalla, compañía fabricante y modelo. El objetivo es aplicar técnicas básicas de limpieza, análisis y visualización de datos usando Python y las librerías pandas y matplotlib, y presentar hallazgos interesantes para mi portafolio como principiante en ciencia de datos.

Habilidades aplicadas:

- Lectura de datos con pandas

- Limpieza de columnas con valores tipo texto ("8GB", "5000mAh", etc.)

- Conversión de tipos de datos

- Agrupaciones con .groupby() y cálculo de medias

- Gráficas de barras y dispersión

- Interpretación de visualizaciones


Ejercicios realizados:

Limpieza de datos:

- Conversión de valores como "8GB" o "1.5MP" a números flotantes.

- Remoción de unidades y comas en columnas como RAM, Cámara, Batería.

Análisis por compañía:

- Cálculo del precio promedio por compañía.

- Comparación visual de compañías con precios promedio más altos.

Comparativa de precios por país:

- Extracción automática de columnas con la palabra "Price".

- Cálculo de promedio por país.

Relación entre características:

- Scatter plot entre RAM y Batería para ver si existe una tendencia.

Visualizaciones con etiquetas:

- Barras con etiquetas de valores numéricos encima (usando plt.text).

Hallazgos interesantes

Las compañías con celulares más caros en promedio son Apple y Samsung.

A mayor cantidad de RAM, en general, también se incrementa la capacidad de batería.

Existen celulares con RAM muy alta (hasta 16 GB) y baterías enormes (hasta 12000 mAh).
