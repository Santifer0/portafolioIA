title: "Práctico 01 — Exploración Iris"
date: 2025-08-13
---

# Entrada 01 — Exploración del dataset Iris

## Contexto
Primera práctica sobre el dataset Iris para ejercitar carga de datos desde diversas fuentes, chequeos básicos de calidad, análisis exploratorio y visualizaciones comparativas.

## Objetivos
- Levantar un entorno de guardado en la nube para guardar el trabajo
- Comparar fromas de cargar los datos
- Generar visualizaciones para entender el dataset
- Redactar insights sobre el conocimiento que ganamos del dataset

## Actividades (con tiempos estimados)
- Setup de entorno y guardado en la nube (10 min)
- Investigar el dataset (10 min)
- Plantear preguntas previas de negocio (5 min)
- Carga de datos (15 min)
- Investigar plausibilidad y rangos del dataset (10 min)
- Análisis estadístico (15 min)
- Generación de visualizaciones  (30 min)
- Redacción de insights ganados sobre el dataset (10 min)

## Desarrollo
Se creó estructura de carpetas y inicialización del entorno, se redactaron preguntas de negocio para dirigir el análisis y las expectativas (fuerte énfasis en la correlación entre datos), se probó cargar el dataset con distintas fuentes (seaborn, scikit-learn, Kaggle API, CSV manual, URL) se decidió cargar por seaborn por su rapidez y simplicidad, se evaluó integridad de los datos (cantidad de nulos, cantidad de duplicados y tipos), se investigó correlaciones entre los datos numericos, se crearon visualizaciones con seaborn y matplotlib, se guardaron los datos y se redactaron insights sobre lo que aprendimos del dataset.


## Evidencias
![Exploración inicial](docs\assets\exploracionInicial.png)
![Descripción del dataset](docs\assets\descripcion.png)
![Visualizaciones](docs\assets\visualizaciones.png)


## Reflexión
La actividad fué util para empezar a familiarizarnos con los métodos de las librerías utilizadas para análisis de datos en python (pandas, seaborn, matplotlib, etc.) ademas de aprender como inicializar un entorno en la nube apto para el análisis de datos. También aprendimos sobre distintos métodos para explorar y visualizar el dataset con el objetivo de ganar insights valiosos sobre los datos. Mejoraría la carga de datos ya que la carga en seaborn fué utilizada por ser la más sencilla en este caso, en otros proyectos puede no haber esta opción y tendré que utilizar alguna de las formas más universales que inicialmente descarté.

## Referencias
- Documentación oficial de pandas, matplotlib y seaborn
