# Predicción del precio del diésel en Colombia (2014–2024)

**Data Analytics | Python | Series Temporales | Machine Learning**

## Descripción del proyecto

Proyecto de ciencia de datos desarrollado durante mi Especialización en Ciencia de Datos y Analítica en la UNAD.

Su objetivo es analizar la evolución del precio del diésel en Colombia, identificar su relación con variables económicas y construir modelos predictivos que permitan evaluar escenarios de costos para el transporte de carga.

## Tecnologías utilizadas

- **Python:** pandas, NumPy, Matplotlib y Seaborn.
- **Modelado estadístico:** statsmodels y SARIMAX.
- **Herramientas:** Google Colab y Jupyter Notebook.
- **Técnicas:** análisis exploratorio de datos (EDA), correlaciones, series temporales y pronósticos.

## Datos y metodología

Se analizaron **132 registros mensuales entre enero de 2014 y diciembre de 2024**, considerando las siguientes variables:

- Precio del diésel (COP/galón).
- Precio internacional del petróleo Brent.
- Tasa Representativa del Mercado (TRM).
- Índice de Costos del Transporte de Carga (ICTC).

Se desarrolló un análisis estadístico y se implementó un modelo SARIMAX para generar proyecciones del precio del diésel bajo tres escenarios económicos.

## Principales resultados

- Análisis de tendencias y variaciones históricas del precio del diésel.
- Identificación de relaciones estadísticas entre las variables económicas.
- Construcción de pronósticos exploratorios para 2025 bajo escenarios optimista, base y pesimista.
- Estimación del costo del combustible por kilómetro recorrido.

**Ejemplo de proyección para enero de 2025:**

| Escenario | Precio estimado (COP/galón) |
|---|---:|
| Optimista | $10.514 |
| Base | $10.571 |
| Pesimista | $10.647 |

*Los valores corresponden a simulaciones del notebook académico, no a pronósticos validados fuera de muestra.*

## Archivos del proyecto

- [Código Python y modelo SARIMAX](notebooks/Modelado%20combustibles.ipynb)
- [Base de datos CSV](notebooks/Data_Combustibles_2014_2024_COLAB%20%281%29.csv)
- [Documento de tesis](tesis/Tesis_Juan_Soto_2025.pdf)
- [Presentación académica](presentacion/Tesis_Juan_Soto_2025.pptx)

**Nota:** El notebook utiliza una ruta original de Google Drive. Para ejecutarlo en otro entorno es necesario ajustar la carga de datos.

## Autor

**Juan David Soto D'Alleman**  
Administrador de Empresas | Especialista en Ciencia de Datos y Analítica — UNAD

[LinkedIn](https://www.linkedin.com/in/juan-david-soto-dalleman-56049a171/)
