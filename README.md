> ⚠Es posible que algunas salidas interactivas no se visualicen correctamente en GitHub.
> Para una visualización completa, consulta el cuaderno con **nbviewer**:
> - Cuaderno MNIST: https://nbviewer.org/github/Josueeeoo-0/Supervised_Learning_Case_Studies/blob/main/PROYECTO_A2A_1.ipynb
> - Cuaderno Titanic: https://nbviewer.org/github/Josueeeoo-0/Supervised_Learning_Case_Studies/blob/main/PROYECTO_A2A_2.ipynb

---

# Aprendizaje Supervisado – Estudios de Caso en Clasificación

Este repositorio forma parte del proyecto del curso de *Machine Learning* que cursé en la **SIAFI**, desarrollado durante el **Curso Propedéutico**.

El objetivo del proyecto es aplicar técnicas de **aprendizaje supervisado** a problemas clásicos de **clasificación**, siguiendo un flujo de trabajo completo que incluye preprocesamiento de datos, entrenamiento de modelos, ajuste de hiperparámetros y evaluación del desempeño.  
El trabajo se documenta paso a paso mediante cuadernos de Jupyter.

Temas principales abordados
- Carga y exploración de datos
- Preprocesamiento y preparación de características
- Modelos de clasificación supervisada
- Ajuste de hiperparámetros mediante *Grid Search*
- Evaluación del desempeño en conjuntos de prueba

Todos los resultados, análisis y explicaciones se incluyen directamente en los cuadernos.


## **Proyecto 1 — Clasificación de Dígitos (MNIST)**  
[`PROYECTO_A2A_1.ipynb`](PROYECTO_A2A_1.ipynb)

Se construye un clasificador para el conjunto de datos **MNIST**, con el objetivo de alcanzar una precisión superior al **97 %** en el conjunto de prueba.

El proyecto explora el uso del algoritmo **k-Nearest Neighbors (kNN)**, evaluando el impacto de distintos hiperparámetros como:
- Número de vecinos (`n_neighbors`)
- Estrategia de ponderación (`weights`)

El ajuste de hiperparámetros se realiza mediante **Grid Search**, y se analizan los resultados obtenidos en términos de precisión y generalización.

> **Project description**  
>  
> Try to build a classifier for the MNIST dataset that achieves over 97% accuracy on the test set.  
> Hint: the `KNeighborsClassifier` works quite well for this task; you just need to find good hyperparameter
> values (try a grid search on the `weights` and `n_neighbors` hyperparameters).



## **Proyecto 2 — Predicción de Supervivencia (Titanic)**  
[`PROYECTO_A2A_2.ipynb`](PROYECTO_A2A_2.ipynb)

En este proyecto se aborda el conjunto de datos **Titanic**, con el objetivo de predecir la variable **`Survived`** a partir de las demás características disponibles.

El trabajo incluye:
- Análisis exploratorio de datos
- Manejo de valores faltantes
- Codificación de variables categóricas
- Entrenamiento de modelos de clasificación supervisada
- Evaluación del desempeño del modelo

> **Project description**  
>  
> Tackle the [Titanic dataset](https://homl.info/titanic.tgz), or download from [Kaggle]
> (https://www.kaggle.com/c/titanic). This will give you two CSV files, train.csv and test.csv, which you can load using
> `pandas.read_csv()`. The goal is to train a classifier that can predict the `Survived` column based on the other columns.