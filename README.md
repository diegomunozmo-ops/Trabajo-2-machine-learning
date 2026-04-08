# Machine Learning – Unidad 2  
## Clasificación binaria de precios de viviendas

---

## 📌 Descripción del proyecto

Este proyecto corresponde al desarrollo de la Unidad 2 de la asignatura de Machine Learning.

En la Unidad 1 se construyó un pipeline reproducible para la predicción del precio de viviendas (problema de regresión).  

En esta segunda etapa, el problema fue reformulado como **clasificación binaria**, con el objetivo de alinearse con las métricas solicitadas en la pauta.

Se definió la variable objetivo **HighPrice**, donde:

- 1 → viviendas con precio sobre la mediana  
- 0 → viviendas con precio bajo o igual a la mediana  

---

## 🎯 Objetivo

Comparar distintos modelos de machine learning supervisado, evaluar su desempeño y seleccionar el mejor modelo en base a métricas de clasificación.

---

## ⚙️ Metodología

El desarrollo del proyecto incluye las siguientes etapas:

1. Preparación de datos (pipeline de Unidad 1)
2. Reformulación del problema a clasificación binaria
3. Entrenamiento de modelos:
   - Regresión logística (L1, L2 y Elastic Net)
   - Random Forest
   - XGBoost
   - Red neuronal simple
4. Evaluación de modelos mediante métricas:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - AUC
   - KS
5. Optimización de hiperparámetros (RandomizedSearchCV)
6. Selección del modelo final

---

## 📊 Resultados

El modelo con mejor desempeño fue **XGBoost**, alcanzando un AUC cercano a 0.98 en la muestra de validación.

Esto indica una alta capacidad de discriminación entre viviendas de alto y bajo precio.

Random Forest también mostró resultados competitivos, mientras que los modelos lineales presentaron un desempeño adecuado pero inferior.

---

## 🧠 Conclusión

El trabajo demuestra la importancia de:

- seleccionar métricas adecuadas al problema
- comparar distintos modelos
- optimizar hiperparámetros
- construir pipelines reproducibles

Se concluye que **XGBoost es el modelo más adecuado** para este problema, debido a su mejor desempeño en validación.

---

## 🔁 Reproducibilidad

El proyecto se encuentra desarrollado en un cuaderno Python (.ipynb), el cual puede ejecutarse completamente para replicar los resultados.

Se utilizó una semilla fija (`random_state=42`) para asegurar consistencia en los resultados.

---

## 📂 Dataset

Dataset utilizado:  
House Prices – Advanced Regression Techniques (Kaggle)

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

---

## 👥 Integrantes

- Muñoz Morales, Diego Ignacio
- Villarroel Montecinos, Yenny Vanessa
- Matujara Contreras, Jordan Hernán
- Sepúlveda Alvial, Segundo Alejandro

---

## 🔗 Repositorio

Link del repositorio:  
https://github.com/diegomunozmo-ops/Trabajo-2-machine-learning