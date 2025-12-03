---
title: "16 — Dataprep: Pipeline de Transformación de Datos"
date: 2025-11-26
---

# 16 — Dataprep: Pipeline de Transformación de Datos

Creación de flujos de limpieza y transformación de datos sin servidor (serverless) utilizando Cloud Dataprep by Trifacta en Google Cloud.

## Contexto
La preparación de datos suele consumir la mayor parte del tiempo en proyectos de analítica. Cloud Dataprep ofrece una interfaz visual inteligente para explorar, limpiar y preparar datos estructurados y no estructurados para su análisis, integrándose nativamente con BigQuery y Cloud Storage.

## Objetivos
- Conectar fuentes de datos (Cloud Storage, BigQuery) a Dataprep.
- Crear "Recipes" (recetas) de transformación visual.
- Identificar y corregir anomalías, valores faltantes y formatos inconsistentes.
- Ejecutar trabajos de Dataflow para procesar datos a escala.
- Exportar resultados limpios a BigQuery.

## Actividades (con tiempos estimados)
- Creación de Dataset y conexión a Dataprep — 10 min
- Exploración visual de distribuciones y calidad de datos — 15 min
- Construcción de Recipe: filtrado, split, regex — 25 min
- Ejecución del Job (Cloud Dataflow) — 15 min
- Verificación de resultados en BigQuery — 10 min

## Desarrollo
### 1. Importación y Exploración
Ingestamos un dataset crudo de transacciones de comercio electrónico. La interfaz de Dataprep generó automáticamente histogramas y estadísticas de calidad para cada columna, permitiendo identificar visualmente valores atípicos (outliers) y nulos.

### 2. Transformación (Recipes)
Construimos una receta de pasos de transformación:
- Parseo de fechas con formatos inconsistentes.
- Separación de columnas compuestas.
- Filtrado de registros inválidos basado en reglas visuales.
La herramienta sugiere transformaciones predictivas basadas en la selección del usuario.

### 3. Ejecución del Pipeline
Una vez definida la lógica, lanzamos el trabajo. Dataprep traduce la receta visual a un job de Apache Beam que se ejecuta en Cloud Dataflow, permitiendo escalar el procesamiento a datasets masivos sin gestionar infraestructura.

### 4. Resultados
Los datos procesados se exportaron a una tabla de BigQuery, quedando listos para ser consultados vía SQL o visualizados en Looker Studio.


## Reflexión
Cloud Dataprep democratiza la ingeniería de datos al permitir transformaciones complejas sin escribir código (ETL visual). Su capacidad de mostrar el impacto de cada paso en tiempo real sobre una muestra acelera el desarrollo. Sin embargo, para pipelines muy complejos o con lógica de negocio muy específica, puede ser necesario caer a código (Python/Beam) para mayor control.

## Referencias
- Google Skills Lab GSP430
