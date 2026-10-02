Proyecto de Modelos de Machine Learning

Proyecto académico de Machine Learning en el que se aplican y comparan diferentes modelos para resolver problemas de regresión y clasificación, utilizando datasets obtenidos de OpenML.

Objetivo

Aplicar diferentes técnicas de aprendizaje automático, analizar los datos, entrenar modelos y evaluar su desempeño mediante métricas para comprender sus resultados y limitaciones.

Datasets

Los datasets utilizados fueron obtenidos de OpenML:

kin8nm (ID: 189): utilizado para el problema de Regresión. El dataset contiene variables relacionadas con los ángulos de un brazo robótico.
Hill-Valley (ID: 1479): utilizado para el problema de Clasificación, con dos clases.
Regresión

Para el dataset kin8nm se realizaron:

Análisis exploratorio de los datos.
Análisis de correlación entre las variables.
Selección de variables.
Entrenamiento de diferentes modelos de regresión.
Evaluación mediante MAE, MSE, RMSE y R².
Comparación de los resultados obtenidos.

Modelos utilizados:

Regresión Lineal
Ridge
Lasso
MLP
Clasificación

Para el dataset Hill-Valley se implementaron y compararon diferentes modelos de clasificación:

Regresión Logística
Árbol de Decisión
KNN
MLP

Los modelos fueron evaluados mediante:

Accuracy
Precision
Recall
F1-score
Matriz de confusión

La matriz de confusión permitió analizar los aciertos y errores de cada modelo y revisar el comportamiento de las diferentes clases.

Tecnologías utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Estructura del proyecto
proyecto-modelos/
│
├── proyecto_modelos.ipynb
├── README.md


Resultados

Se realizó una comparación de los modelos utilizando diferentes métricas de evaluación. En regresión se analizaron los errores de predicción y el coeficiente de determinación R².

En clasificación se compararon Accuracy, Precision, Recall y F1-score, complementando el análisis con las matrices de confusión para identificar los aciertos y errores de cada modelo.

Conclusiones

El proyecto permitió aplicar diferentes algoritmos de Machine Learning y comprender cómo las características de los datos influyen en el desempeño de los modelos. La comparación de varias métricas permitió realizar un análisis más completo que utilizando únicamente una métrica de evaluación.

Autor

Camila López Cárdenas
