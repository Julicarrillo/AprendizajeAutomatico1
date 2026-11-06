🤖 Aprendizaje Automático I

Repositorio correspondiente a la materia Aprendizaje Automático I de la Tecnicatura en Inteligencia Artificial y Ciencia de Datos.

📚 Trabajos Prácticos

TP1 - Introducción a la Regresión Lineal con Scikit-Learn

En este trabajo práctico se aplicaron conceptos fundamentales de Aprendizaje Automático mediante la implementación de modelos de regresión lineal utilizando Python y la biblioteca scikit-learn.

Se trabajó con un dataset sintético que relaciona las horas de estudio de un grupo de estudiantes con las calificaciones obtenidas en un examen.

Se realizaron las siguientes actividades:

Generación, exploración y visualización de datos utilizando NumPy, Pandas y Matplotlib.

División de los datos en conjuntos de entrenamiento y prueba mediante train_test_split.

Entrenamiento de modelos de regresión lineal simple y múltiple.

Interpretación de los coeficientes e interceptos de los modelos.

Evaluación del rendimiento mediante MAE, MSE, RMSE y R².

Realización de predicciones sobre nuevos datos.

Análisis de la relación entre las variables independientes y la variable objetivo.

Comparación de modelos modificando la proporción de datos de entrenamiento y prueba.

Incorporación de nuevas variables independientes para analizar su influencia en las predicciones.

Introducción al escalado de variables con StandardScaler y a la regularización con Ridge.

📊 Ejercicios prácticos

Ejercicio 1 - Regresión lineal simple

Se analizó la relación entre las horas de estudio y las calificaciones, interpretando la pendiente, el intercepto y el coeficiente de determinación R².

Ejercicio 2 - Predicciones

Se utilizó el modelo entrenado para estimar las calificaciones correspondientes a nuevas cantidades de horas de estudio.

Ejercicio 3 - Comparación de modelos

Se modificó el porcentaje de datos destinados a prueba del 20 % al 30 %, comparando los coeficientes y el rendimiento de ambos modelos.

Ejercicio 4 - Regresión lineal múltiple

Se incorporó una tercera variable independiente, horas_de_celular, para analizar su relación con las calificaciones junto con las horas de estudio y de sueño.

Resultados obtenidos:

Variable

Coeficiente aproximado

Horas de estudio

5.80

Horas de sueño

2.87

Horas de celular

-4.01

El modelo obtuvo un R² de 0.85, explicando aproximadamente el 85 % de la variabilidad de las calificaciones en los datos de prueba.

💡 Conclusiones

Este trabajo permitió comprender cómo se entrenan y evalúan modelos de regresión lineal y cómo interpretar sus resultados.

También se observó que incorporar nuevas variables puede ayudar a explicar el comportamiento de la variable objetivo, y que modificar la proporción de datos de entrenamiento y prueba no necesariamente produce grandes cambios en el rendimiento del modelo.

TP2 - Redes Neuronales y Optimización de Hiperparámetros

En este trabajo práctico se aplicaron técnicas de Aprendizaje Automático mediante la implementación, entrenamiento y evaluación de redes neuronales artificiales utilizando Python y la biblioteca scikit-learn.

Se trabajó con diferentes conjuntos de datos, incluyendo un dataset de diamantes, para analizar el comportamiento de los modelos de regresión y mejorar su rendimiento mediante la optimización de hiperparámetros.

Se realizaron las siguientes actividades:

Exploración y preparación de datos utilizando Pandas y NumPy.

División de los datos en conjuntos de entrenamiento y prueba.

Preprocesamiento y escalado de variables mediante StandardScaler.

Implementación de redes neuronales utilizando MLPRegressor.

Entrenamiento y evaluación de modelos de regresión.

Análisis de curvas de aprendizaje y validación.

Identificación de posibles problemas de sobreajuste y subajuste.

Optimización de hiperparámetros mediante GridSearchCV.

Aplicación de validación cruzada para comparar diferentes configuraciones.

Evaluación del rendimiento mediante MAE, MSE, RMSE y R².

Comparación de modelos originales y optimizados.

📊 Ejercicios prácticos

Entrenamiento de redes neuronales

Se implementaron modelos de regresión utilizando redes neuronales multicapa (MLP), analizando su capacidad para aprender relaciones entre las variables independientes y la variable objetivo.

Análisis de curvas de aprendizaje y validación

Se analizaron las curvas de entrenamiento y validación para observar cómo cambia el rendimiento de los modelos y detectar posibles problemas de sobreajuste o subajuste.

Optimización de hiperparámetros

Se utilizó GridSearchCV para buscar las mejores combinaciones de hiperparámetros mediante validación cruzada.

Se analizaron los siguientes hiperparámetros:

hidden_layer_sizes: cantidad de capas ocultas y neuronas de la red.

alpha: parámetro que controla la regularización.

learning_rate_init: tasa de aprendizaje inicial.

Evaluación y comparación de modelos

Se seleccionaron las mejores configuraciones obtenidas mediante GridSearchCV y se evaluaron sobre el conjunto de prueba.

Se compararon los resultados utilizando diferentes métricas de regresión para analizar la precisión de las predicciones y el rendimiento de los modelos.

💡 Conclusiones

Este trabajo permitió comprender cómo funcionan las redes neuronales artificiales y la importancia de seleccionar adecuadamente sus hiperparámetros.

Se observó que la validación cruzada permite comparar diferentes configuraciones utilizando los datos de entrenamiento, sin utilizar el conjunto de prueba durante la optimización.

Además, el análisis de las métricas permitió comparar el rendimiento de los modelos y comprender que aumentar la complejidad de una red neuronal no siempre garantiza mejores predicciones.

TP3 - Redes Neuronales para Clasificación con Scikit-Learn

En este trabajo práctico se aplicaron redes neuronales artificiales para resolver problemas de clasificación utilizando Python y la biblioteca scikit-learn.

Se trabajó con los datasets Palmer Penguins y Titanic, implementando modelos de clasificación, comparando sus resultados y analizando cómo influyen los hiperparámetros en el rendimiento.

Se realizaron las siguientes actividades:

Exploración y visualización de datos con Pandas, Matplotlib y Seaborn.

Identificación y tratamiento de valores faltantes.

División de datos en entrenamiento y prueba utilizando stratify.

Preprocesamiento de variables numéricas y categóricas mediante Pipeline y ColumnTransformer.

Escalado de variables y codificación mediante OneHotEncoder.

Implementación de redes neuronales con MLPClassifier.

Comparación con DummyClassifier y LogisticRegression.

Evaluación mediante Accuracy, Precision, Recall y F1-score.

Interpretación de matrices de confusión y reportes de clasificación.

Análisis de probabilidades mediante predict_proba.

Optimización de hiperparámetros utilizando RandomizedSearchCV.

Aplicación de validación cruzada con StratifiedKFold.

Análisis de importancia de variables mediante permutación.

Modificación del umbral de decisión para comparar precisión y sensibilidad.

Análisis de curvas de validación para identificar sobreajuste y subajuste.

📊 Ejercicios prácticos

Actividad 1 - Clasificación de especies de pingüinos

Se utilizó el dataset Palmer Penguins para entrenar una red neuronal capaz de clasificar pingüinos según sus características físicas.

Se compararon tres modelos:

DummyClassifier.

LogisticRegression.

MLPClassifier.

Se analizaron las métricas de clasificación, la matriz de confusión y las probabilidades estimadas para cada especie.

Resultados obtenidos:

La regresión logística obtuvo un Accuracy del 100 %, mientras que la red neuronal alcanzó un 98,6 %, equivocándose solamente en un pingüino.

Esto permitió observar que un modelo más complejo no necesariamente obtiene mejores resultados.

Actividad 2 - Predicción de supervivencia en el Titanic

Se trabajó con el dataset Titanic para desarrollar un modelo de clasificación binaria que predice si un pasajero sobrevivió o no.

Se realizaron las siguientes tareas:

Exploración de variables relacionadas con la supervivencia.

Identificación de variables que podían generar fuga de información (data leakage).

Tratamiento de datos faltantes.

Entrenamiento y comparación de modelos.

Análisis de errores mediante matriz de confusión.

Optimización de hiperparámetros.

Análisis de importancia de variables.

Evaluación de diferentes umbrales de decisión.

Resultados obtenidos:

Modelo

Accuracy en prueba

DummyClassifier

61,5 %

LogisticRegression

80,4 %

La regresión logística obtuvo los mejores resultados entre los modelos iniciales, con un F1 macro de 78,6 %.

La optimización de la red neuronal permitió mejorar ligeramente su F1 macro, pasando de 0.767 a 0.780.

Sin embargo, la mejora fue pequeña en comparación con la variabilidad observada durante la validación cruzada.

También se identificó que las variables más importantes para predecir la supervivencia fueron el sexo y la clase del pasajero.

Actividad 3 - Curvas de validación y regularización

Se construyó una curva de validación para analizar cómo influye el hiperparámetro alpha en el comportamiento de la red neuronal.

Se compararon los resultados de entrenamiento y validación utilizando diferentes valores de regularización.

Se observaron señales de sobreajuste con valores bajos de alpha y de subajuste cuando la regularización era demasiado alta.

Actividad 4 - Reflexión final

Se analizaron los resultados obtenidos para comprender:

Por qué la optimización de hiperparámetros no siempre mejora significativamente el rendimiento.

Por qué no alcanza con evaluar un clasificador utilizando solamente Accuracy.

La importancia de comparar modelos complejos con alternativas más simples.

Cómo interpretar el comportamiento de los modelos para seleccionar una configuración adecuada.

💡 Conclusiones

Este trabajo permitió comprender cómo se utilizan las redes neuronales para resolver problemas de clasificación y cómo evaluar su capacidad para identificar correctamente diferentes categorías.

Se observó que una red neuronal no siempre supera a un modelo más simple, como la regresión logística, y que la optimización de hiperparámetros no garantiza mejoras importantes.

También se comprendió la importancia de analizar diferentes métricas de clasificación, especialmente cuando las clases no están equilibradas.

Finalmente, se observó cómo modificar el umbral de decisión permite aumentar la precisión a costa de reducir la sensibilidad, o viceversa, dependiendo de las necesidades del problema.

🛠️ Tecnologías utilizadas

Python

Google Colab

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Técnicas y herramientas aplicadas:

Regresión lineal simple y múltiple.

Redes neuronales MLPRegressor y MLPClassifier.

Preprocesamiento con Pipeline y ColumnTransformer.

StandardScaler y OneHotEncoder.

Validación cruzada.

GridSearchCV y RandomizedSearchCV.

Curvas de aprendizaje y validación.

Métricas de regresión y clasificación.

Matrices de confusión.

Importancia de variables por permutación.

📁 Archivos

TP1 - Regresión Lineal

Ver notebook en GitHub

Abrir en Google Colab

TP2 - Redes Neuronales y Optimización

Ver notebook en GitHub

Abrir en Google Colab

TP3 - Redes Neuronales para Clasificación

Ver notebook en GitHub

Abrir en Google Colab

👩‍💻 Autora

Julia Belén Carrillo

Estudiante de la Tecnicatura en Inteligencia Artificial y Ciencia de Datos.

AA1_TP1_CARRILLO_JULIA.ipynb: notebook correspondiente al Trabajo Práctico N.º 1 sobre regresión lineal.

👩‍💻 Autora

Julia Belén Carrillo
