# Modelado Exhaustivo con Regresión Lineal

Este repositorio contiene varios estudios de caso enfocados en la aplicación de modelos de Regresión Lineal Simple (RLS) y Múltiple (RLM) para predicción e inferencia. Los proyectos buscan principalmente cuantificar el impacto de las variables y realizar diagnósticos.
## Proyectos Destacados y Resultados Clave

- **Modelo de Ventas/Publicidad (RLM):**
    - **Logro Principal:** El modelo lineal múltiple explicó el impacto del gasto en TV, Radio y Prensa sobre las ventas, alcanzando un coeficiente de determinación **(R²)** de **0.9677**.
    - **Archivo:** [`advertising.ipynb`](./advertising.ipynb)
 
- **Regresión Lineal Simple (Boston):**
    - **Logro Principal:** Demostración de la inferencia estadística básica con un único predictor, sentando las bases para modelos más complejos. Se hace hincapie en lo conceptual no en los resultados del modelo. 
    - **Archivo:** [`Boston_SIMPLE_Linear_Regression.ipynb`](./Boston_SIMPLE_Linear_Regression.ipynb)

    
- **Precios de Viviendas en Boston (RLM):**
    - **Logro Principal:** Aplicación de RLM para predecir precios de viviendas. Este ejercicio fue clave para dominar la **selección de variables** (Feature Selection) y la gestión de la multicolinealidad.
    - **Archivo:** [`Boston_MULTIPLE_regression_lineal.ipynb`](./Boston_MULTIPLE_regression_lineal.ipynb)
    - 

- **Análisis de Variables Automotrices (RLM):**
    - **Logro Principal:** Aplicación de RLM sobre el Auto Dataset para estudiar la relación entre el peso, la potencia y la eficiencia de combustible. Elegi este dataset ya tiene la **particualridad de no ser estrictamente lineal** (forma de U y patron en los residuos) y usamos una **regresion polinomica** para resolverlo
    - **Archivo:** [`Autodataset LinearRegression.ipynb`](./Autodataset%20LinearRegression.ipynb)

***

## Conclusión sobre Habilidades

Estos ejercicios buscan enseñar **inferencia estadística**, **validación de modelos** (incluyendo el análisis de residuales) y la capacidad para **cuantificar el impacto** de las variables. Todas las implementaciones se realizaron en Python.
