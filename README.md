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

Se realizaron diferentes ejercicios para analizar el comportamiento de los modelos:

Ejercicio 1 - Regresión lineal simple

Se analizó la relación entre las horas de estudio y las calificaciones, interpretando la pendiente, el intercepto y el coeficiente de determinación R².

Ejercicio 2 - Predicciones

Se utilizó el modelo entrenado para estimar las calificaciones correspondientes a nuevas cantidades de horas de estudio.

Ejercicio 3 - Comparación de modelos

Se modificó el porcentaje de datos destinados a prueba del 20 % al 30 %, comparando los coeficientes y el rendimiento de ambos modelos.

Ejercicio 4 - Regresión lineal múltiple

Se incorporó una tercera variable independiente, horas_de_celular, para analizar su relación con las calificaciones junto con las horas de estudio y de sueño.

**Resultados obtenidos:**

| Variable | Coeficiente aproximado |
|---|---:|
| Horas de estudio | 5.80 |
| Horas de sueño | 2.87 |
| Horas de celular | -4.01 |
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

Se realizaron diferentes actividades para analizar el funcionamiento de las redes neuronales y evaluar su capacidad de predicción.

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

🛠️ Tecnologías utilizadas

Python

Google Colab

NumPy

Pandas

Matplotlib

Scikit-learn

📁 Archivos

AA1_TP1_CARRILLO_JULIA.ipynb: notebook correspondiente al Trabajo Práctico N.º 1 sobre regresión lineal.

AA1_TP2_CARRILLO_JULIA.ipynb: notebook correspondiente al Trabajo Práctico N.º 2 sobre redes neuronales y optimización de hiperparámetros.

👩‍💻 Autora

Julia Belén Carrillo

AA1_TP1_CARRILLO_JULIA.ipynb: notebook correspondiente al Trabajo Práctico N.º 1 sobre regresión lineal.

👩‍💻 Autora

Julia Belén Carrillo
