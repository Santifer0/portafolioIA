title: "Práctico 03 — Taxis NYC"
date: 2025-09-06
---

# Entrada 03 — Exploración Taxis

## Contexto
Práctica de integración de datos combinando viajes de taxis de NYC, tabla de zonas y un calendario de eventos para ejercitar carga multi-formato, normalización, joins y agregaciones exploratorias.

## Objetivos
- Cargar datasets en formatos diferentes (parquet, csv, json)
- Dominar el uso de joins con pandas
- Realizar análisis agregados con groupby
- Crear reportes consolidados de datos integrados


## Actividades (con tiempos estimados)
- Carga de Datos desde Múltiples Fuentes (15 min)T
- Normalización de Datos (15 min)
- Joins de distintas tablas (25 min)
- Análisis por Borough  (20 min)
- Análisis por Borough y Día Especial  (15 min)
- Aplicación de técnicas para datasets grandes (15 min)

## Desarrollo
Se cargó el dataset de viajes en formato parquet (forma mas eficiente), la tabla de zonas en csv y un calendario de eventos en json. Se normalizaron los datos y se prepararon para un posterior join. Se realizaron dos joins, primero trips con zonas  y después el resultado de el primer join con el calendario (flag de día especial). Se calcularon métricas agregadas por borough y métricas como beneficio por kilometro y tasa de propina. También se hizo un análisis de las metricas en días "Especiales" comparado con días normales. Por último se hizo un análisis de correlaciones, útil para ganar insights de negocio valiosos.

## Evidencias
- ![Análisis por borough](\assets\analisisPorBoroughE3.png)
- ![Técnicas para manejar datasets grandes](\assets\tecnicasDatasetE3.png)
- ![Matriz de correlaciones](\assets\matrizCorrelacionesE3.png)

## Reflexión
Esta actividad conlleva nuevos retos ya que tuvimos que trabajar con distintas tablas de distintas fuentes lo que agrega un componente de normalización y join de datos que anteriormente no lo tomabamos tanto en cuenta y el dataset con el que se trabajó era excepcionalmente grande por lo que fué muy útil ver técticas para hacer mas eficiente el procesado de los datos.

## Referencias
- Datasets públicos NYC Taxi
- Documentación oficial de pandas
