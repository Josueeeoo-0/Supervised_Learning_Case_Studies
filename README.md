# Aprendizaje Supervisado – Estudios de Caso en Clasificación

Este repositorio forma parte del proyecto del curso de *Machine Learning* que cursé en la **SIAFI**, desarrollado durante el **Curso Propedéutico**.

El objetivo del proyecto es aplicar técnicas de **aprendizaje supervisado** a problemas clásicos de **clasificación**, siguiendo un flujo de trabajo completo que incluye preprocesamiento de datos, entrenamiento de modelos, ajuste de hiperparámetros y evaluación del desempeño.  
El trabajo se documenta paso a paso mediante cuadernos de Jupyter.

## Temas principales abordados
- Carga y exploración de datos
- Preprocesamiento y preparación de características
- Modelos de clasificación supervisada
- Ajuste de hiperparámetros mediante *Grid Search*
- Evaluación del desempeño en conjuntos de prueba

Todos los resultados, análisis y explicaciones se incluyen directamente en los cuadernos.

---

## **Proyecto 1 — Clasificación de Dígitos (MNIST)**  
[`MNIST_Classification.ipynb`](MNIST_Classification.ipynb)

Se construye un clasificador para el conjunto de datos **MNIST**, con el objetivo de alcanzar una precisión superior al **97 %** en el conjunto de prueba.

El proyecto explora el uso del algoritmo **k-Nearest Neighbors (kNN)**, evaluando el impacto de distintos hiperparámetros como:
- Número de vecinos (`n_neighbors`)
- Estrategia de ponderación (`weights`)

El ajuste de hiperparámetros se realiza mediante **Grid Search**, y se analizan los resultados obtenidos en términos de precisión y generalización.

> **Project description**  
>  
> Try to build a classifier for the MNIST dataset that achieves over 97% accuracy on the test set.  
> The `KNeighborsClassifier` is used, and hyperparameters such as `weights` and `n_neighbors` are tuned using grid search.

---

## **Proyecto 2 — Predicción de Supervivencia (Titanic)**  
[`Titanic_Classification.ipynb`](Titanic_Classification.ipynb)

En este proyecto se aborda el conjunto de datos **Titanic**, con el objetivo de predecir la variable **`Survived`** a partir de las demás características disponibles.

El trabajo incluye:
- Análisis exploratorio de datos
- Manejo de valores faltantes
- Codificación de variables categóricas
- Entrenamiento de modelos de clasificación supervisada
- Evaluación del desempeño del modelo

> **Project description**  
>  
> Tackle the Titanic dataset to train a classifier capable of predicting the `Survived` column based on the remaining features.  
> The dataset is loaded using `pandas.read_csv()`, and standard preprocessing and classification techniques are applied.

---