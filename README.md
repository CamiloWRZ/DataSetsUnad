# DataSetsUnad
# Modelos de Regresión

Este repositorio contiene dos ejemplos de modelos predictivos utilizando regresión lineal y regresión logística. Estos modelos son utilizados para analizar y predecir comportamientos de datos estructurados, cada uno adecuado para diferentes tipos de problemas de predicción.

## Regresión Lineal

### Descripción
El modelo de regresión lineal en este repositorio está diseñado para predecir precios de venta de vehículos basados en diversas características como el año, marca, kilometraje, etc. El código realiza un análisis exploratorio de los datos, preparación y limpieza de datos, selección de características, y finalmente, entrenamiento y evaluación del modelo.

### Visualización
El modelo proporciona gráficos de dispersión para comparar los valores reales con las predicciones y visualizar la efectividad del modelo. También se incluyen histogramas y diagramas de caja para entender la distribución de los datos y la presencia de valores atípicos.

## Regresión Logística

### Descripción
El modelo de regresión logística está aplicado para predecir la presencia de enfermedades cardíacas en pacientes utilizando datos clínicos. Similar al modelo de regresión lineal, este código sigue pasos de análisis exploratorio, preprocesamiento de datos, selección de características y evaluación del modelo usando métricas como precisión, recall y F1-score.

### Visualización
El código incluye gráficos de dispersión para los valores reales contra las predicciones, matrices de correlación para entender las relaciones entre variables, y gráficos para mostrar los resultados de la evaluación del modelo.

## Arbol de decisión:

### Descripción
Este modelo utiliza un árbol de decisión para clasificar la calidad del vino rojo basado en características físico-químicas. El código sigue los pasos de análisis exploratorio de datos, preparación de datos, entrenamiento del modelo y evaluación de su desempeño.

### Visualización
El modelo incluye un gráfico del árbol de decisión y diagramas de dispersión para entender las relaciones entre variables. Además, se proporcionan histogramas de las calidades del vino y un mapa de calor para visualizar las correlaciones entre predictores.

Para ejecutar cada uno de estos scripts, es necesario tener instaladas las librerías `pandas`, `numpy`, `matplotlib`, `seaborn`, y `sklearn`. Puede instalar estas librerías usando pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
