# Proyecto de Modelos de Machine Learning

Proyecto académico de **Machine Learning** en el que se aplican y comparan diferentes modelos para resolver problemas de **regresión y clasificación**, utilizando datasets obtenidos de **OpenML**.

## Objetivo

Aplicar diferentes técnicas de aprendizaje automático, analizar los datos, entrenar modelos y evaluar su desempeño mediante diferentes métricas.

## Datasets

Los datasets utilizados fueron obtenidos de **OpenML**:

- **kin8nm (ID: 189):** utilizado para el problema de **Regresión**. Sus variables representan ángulos relacionados con un brazo robótico.
- **Hill-Valley (ID: 1479):** utilizado para el problema de **Clasificación**, con dos clases.

## Regresión

Para el dataset **kin8nm** se realizaron:

- Análisis exploratorio de los datos.
- Análisis de correlación entre las variables.
- Selección de variables.
- Entrenamiento de diferentes modelos.
- Evaluación mediante **MAE, MSE, RMSE y R²**.
- Comparación de los resultados.

### Modelos utilizados

- Regresión Lineal
- Ridge
- Lasso
- MLP

## Clasificación

Para el dataset **Hill-Valley** se implementaron y compararon los siguientes modelos:

- Regresión Logística
- Árbol de Decisión
- KNN
- MLP

### Métricas utilizadas

- Accuracy
- Precision
- Recall
- F1-score
- Matriz de confusión

La matriz de confusión permitió analizar los aciertos y errores de cada modelo y verificar el comportamiento de las diferentes clases.

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Estructura del proyecto

```text
proyecto-modelos/
│
├── proyecto_modelos.ipynb
├── README.md

## Autor

Camila López Cárdenas

Este proyecto es de uso académico y forma parte de mi portafolio personal.

