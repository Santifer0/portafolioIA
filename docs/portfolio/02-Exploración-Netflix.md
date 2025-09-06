title: "Práctico 02 — Exploración Netflix"
date: 2025-09-06
---

# Entrada 02 — Exploración del dataset de Netflix

## Contexto
Práctica de análisis exploratorio sobre el dataset público de títulos de Netflix (películas y series) para familiarizarnos con carga de datos, revisión de calidad, creación de visualizaciones y redacción de insights iniciales sobre catálogo y tendencias.

## Objetivos
- Probar carga del CSV remoto y ver estructura
- Identificar columnas con mayor cantidad de valores faltantes
- Generar visualizaciones básicas (tipos, países, ratings, línea temporal)
- Redactar insights iniciales sobre evolución y composición del catálogo

## Actividades (con tiempos estimados)
- Setup y carga de datos (10 min)
- Revisión de columnas y tipos (10 min)
- Análisis de valores faltantes y duplicados (15 min)
- Visualizaciones de tipos de contenido y ratings (25 min)
- Análisis temporal (línea años recientes) (20 min)
- Análisis Geográfico (15 min)
- Análisis de Géneros y Ratings (15 min)
- Creación de dashboard final (10 min)
- Análisis de Géneros y Duración (10 min)

## Desarrollo
Se cargó el dataset desde una URL pública usando pandas y se hizo una exploración básica sobre las filas, columnas y estadísticas del dataset. Se detectaron datos faltantes y datos atípicos en el dataset. Se analizaron y se generaron visualizaciones sobre las tendiencias temporales y geográficas del dataset, se generó un dashboard final que engloba el análisis anterior.

## Evidencias
- ![Visualización de datos faltantes](\assets\dataFaltanteVisualE2.png)
- ![Visualización de datos atípicos](\assets\analisisDatosAtipicosE2.png)
- ![Visualización de análisis temporal](\assets\analisisTemporalE2.png)
- ![Visualización de análisis geográfico](\assets\analisisGeograficoE2.png)

## Reflexión
La actividad fué util para profundizar en técnicas de análisis y visualización de un dataset con componentes más complejos como el componente temporal y geográfico. Asi como para asentar los conocimientos sobre métodos de las librerías más conocidas para el análisis de datos en python.


## Referencias
- Dataset público de Netflix en Kaggle
- Documentación oficial de pandas y seaborn


