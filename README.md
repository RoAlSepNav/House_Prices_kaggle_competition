# <span style="color:cyan"> House Prices - Advanced Regression Techniques :house:
### <span style="color:lightblue"> Descripción del Proyecto
Este proyecto utiliza el conjunto de datos disponible en Kaggle (https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) para realizar un análisis de datos utilizando Python. El objetivo principal es predecir el precio de venta para las casas aplicando técnicas de aprendizaje automático.

### <span style="color:lightblue"> Evaluación :chart_with_upwards_trend:
La métrica que se busca mejorar es el micro-averaged F1-Score. Este valor se calcula usando la totalidad de verdaderos positivos, falsos positivos y falsos negativos, en lugar de calcular el f1 score individualmente para cada clase.

### <span style="color:orange"> Herramientas Utilizadas :wrench:
- Python 3.9.17
- Bibliotecas de análisis de datos: Pandas, NumPy.
- Bibliotecas de visualización: Matplotlib, Seaborn.
- Biblioteca de aprendizaje automático: scikit-learn.

### <span style="color:orange"> Estructura del Proyecto :open_file_folder:
- train.csv: Archivo CSV que contiene los datos de entrenamiento.
- test.csv: Archivo CSV que contiene los datos de validación.
- horse.csv: Archivo CSV que contiene los datos originales del dataset.
- horses_kaggle.ipynb: Un Jupyter notebook que contiene el código Python para el análisis de datos.
- funciones.py: Archivo Python que contiene las funciones utilizadas para este proyecto.
- submission.csv: Archivo CSV que contiene las predicciones para el archivo test.csv de acuerdo a las instrucciones proporcionadas por Kaggle.

### <span style="color:orange"> Cómo usar este proyecto :question:
1. Descarga el conjunto de datos desde Kaggle: https://www.kaggle.com/competitions/playground-series-s3e22/data
2. Coloca los archivos CSV descargados (train.csv, test.csv, original.csv) en la misma carpeta que este proyecto.
3. Abre el Jupyter notebook horses_kaggle.ipynb y ejecuta las celdas de código paso a paso para explorar y analizar los datos.

### <span style="color:orange"> Contenido del Jupyter notebook :page_facing_up:
El Jupyter notebook proporciona un análisis completo de los datos, que incluye:
- Exploración de datos: Resumen estadístico, visualización de datos, identificación de valores nulos, etc.
- Preprocesamiento de datos: Limpieza de datos, manejo de valores faltantes, codificación de variables categóricas, etc.
- Análisis de características: Visualización de relaciones entre características y supervivencia.
- Modelado y predicción: Entrenamiento de modelos de aprendizaje automático para predecir estado de salud de los caballos.
- Evaluación del modelo: Evaluación del  micro-averaged F1-Score y rendimiento del modelo.