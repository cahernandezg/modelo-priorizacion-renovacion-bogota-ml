# Modelo de priorización de renovación urbana en Bogotá

Este repositorio contiene el desarrollo de un modelo exploratorio para identificar manzanas con potencial de renovación urbana dentro de las Actuaciones Estratégicas del Plan de Ordenamiento Territorial (POT) de Bogotá.

El análisis combina análisis espacial, exploración estadística y técnicas de aprendizaje no supervisado para identificar patrones territoriales.

## Metodología

El modelo se construyó en las siguientes etapas:

1. Preparación y limpieza de datos espaciales
2. Análisis exploratorio de datos (EDA)
3. Normalización de variables
4. Reducción de dimensionalidad mediante PCA
5. Clustering no supervisado usando K-Means
6. Clasificación de prioridad de renovación (alta, media, baja)

## Variables utilizadas

Las variables incluidas en el modelo representan distintas dimensiones del territorio urbano:

- Área de la manzana
- Densidad poblacional
- Número de viviendas
- Población
- Distancia a estaciones de TransMilenio
- Actividad económica (comercio + industria)
- Viviendas desocupadas

## Archivos del repositorio

- `EDA_MODELO_RENOVACION_F_CAHG.ipynb`  
  Notebook con el análisis exploratorio, PCA y clustering.

- `manzanas_final.xlsx`  
  Base de datos utilizada para el modelo.

- `resultado_clusters.xlsx`  
  Resultados del modelo con clasificación de prioridad.

## Objetivo

El objetivo del modelo es identificar manzanas con mayor potencial de intervención urbana, considerando factores demográficos, espaciales y de accesibilidad.

## Autor

Camila Andrea Hernández  
Especialización en Estadística Aplicada
