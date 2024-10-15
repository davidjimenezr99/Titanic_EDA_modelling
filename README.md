# Análisis y Modelo Predictivo del Titanic

Este proyecto realiza un análisis exploratorio de los datos de los pasajeros del Titanic, trata los valores faltantes y los outliers en las variables relevantes y desarrolla un modelo predictivo utilizando PyCaret para predecir la supervivencia de los pasajeros. Se incluye el archivo de datos originales, el notebook con el análisis, y el modelo final entrenado.

## Archivos en el Repositorio

- **train_titanic.csv**: Archivo de datos con información de los pasajeros del Titanic.
- **Titanic_model_predict.ipynb**: Jupyter Notebook que contiene el análisis exploratorio de los datos, el tratamiento de valores faltantes y la creación del modelo predictivo.
- **gbc_titanic.pkl**: Archivo que contiene el modelo entrenado utilizando PyCaret (Gradient Boosting Classifier).

## Requisitos

Las siguientes bibliotecas son necesarias para ejecutar el código en este proyecto:

- pandas
- numpy
- pycaret
- scipy
- scikit-learn
- matplotlib (opcional, para visualizaciones)

## Modelo y Evaluación

Utilizando PyCaret, se entrenó un modelo de **Gradient Boosting Classifier** para predecir la supervivencia de los pasajeros. Los resultados del modelo mostraron una **exactitud (accuracy)** del 82.50% en los datos de prueba.

## Referencias

- Dataset: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
