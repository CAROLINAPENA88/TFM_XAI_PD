# TFM_XAI_PD
Repositorio del TFE sobre explicabilidad de modelos de ML para estimación de PD, incluye código, datos y análisis de XAI (SHAP, LIME, PDP).
Este repositorio contiene el código y los datos utilizados en el Trabajo de Fin de Master: “Explicabilidad en modelos de Machine Learning para la probabilidad de default.”

El objetivo del trabajo es evaluar la capacidad explicativa de distintas técnicas de Explainable Artificial Intelligence (XAI), tales como SHAP, LIME, Feature Importance y Partial Dependence Plots, aplicadas a modelos de Machine Learning utilizados para la estimación de la Probabilidad de Incumplimiento (PD) en ejercicios de proyección de riesgo de crédito.

Estructura del repositorio:
- codigo/: scripts y notebooks utilizados para el procesamiento de datos, estimación de modelos (Regresión Lineal, Random Forest y XGBoost) y análisis de explicabilidad.
- datos/: conjuntos de datos públicos para la reproducción del análisis.
- resultados/: gráficos y tablas generados.
- README.md: descripción general del proyecto.

Requisitos técnicos:
Python 3.13

Principales librerías utilizadas:
numpy, pandas, scikit-learn, xgboost, shap, lime, matplotlib
