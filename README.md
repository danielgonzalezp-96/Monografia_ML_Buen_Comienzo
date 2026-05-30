# Monograf-a---ML_Buen_Comienzo
Predicción de continuidad en beneficiarios de Buen Comienzo mediante Machine Learning

Repositorio asociado al trabajo de grado orientado al análisis y predicción de continuidad de niños y niñas beneficiarios del programa Buen Comienzo a partir de información sociodemográfica, institucional y territorial correspondiente a las cohortes 2024 y 2025.

El proyecto integra procesos de limpieza y transformación de datos, análisis exploratorio, selección de variables, entrenamiento de modelos supervisados, optimización de hiperparámetros, evaluación temporal y análisis de interpretabilidad utilizando técnicas de Machine Learning.

## **Objetivo**

Predecir la continuidad de los niños y niñas beneficiarios del programa Buen Comienzo mediante el desarrollo y evaluación de modelos de machine learning, basados en información sociodemográfica, institucional y territorial (2024-2025), con el propósito de formular estrategias de intervención y acompañamiento para la vigencia 2026.

## **Contenido del repositorio**

- Analisis_monografia.ipynb
- Notebook principal del proyecto. Incluye:
- limpieza y transformación de datos;
- análisis exploratorio;
- selección y reducción de variables;
- entrenamiento y evaluación de modelos;
- comparación de estrategias de ensamble;
- curvas ROC y Precision-Recall;
- interpretabilidad mediante Permutation Importance.
  
## **Modelos**
- Modelos entrenados y serializados (.pkl) correspondientes a las diferentes versiones evaluadas.

## **Resultados**
- Archivos CSV con métricas, resultados comparativos, predicciones y experimentos realizados durante el proceso.

## **Modelos evaluados**
Durante el desarrollo se evaluaron diferentes algoritmos y estrategias:

- Logistic Regression
- Decision Tree
- Random Forest
- HistGradientBoostingClassifier
- Hard Voting
- Soft Voting
- Stacking Classifier

## **Principales hallazgos**

HistGradientBoostingClassifier presentó el mejor desempeño global entre los modelos individuales evaluados.
Variables como la edad del participante, el mes de matrícula y el prestador mostraron alta incidencia sobre la capacidad predictiva del modelo.
Las estrategias de ensamble generaron mejoras marginales frente al mejor modelo individual.
Se observaron diferencias de desempeño entre las cohortes 2024 y 2025, sugiriendo posibles cambios temporales en la distribución de los datos.

## **Tecnologías utilizadas**

- Python
- Pandas
- NumPy
- Shutil
- Math
- Os
- Scikit-learn
- Scipy.stats
- imblearn
- data_profiling
- itertools
- Matplotlib
- Seaborn
- Google Colab
- Google Drive
- Joblib

# **Autores**
- Daniel González Pabón
- Pablo Peláez Cardona

Monografía de grado — Análisis y Ciencia de Datos - Universidad de Antioquia 2026

> Nota: Por motivos de confidencialidad y protección de datos personales, las bases originales del programa Buen Comienzo no se incluyen públicamente en este repositorio. Paa reproducción del notebook usa esta contraseña con toda responsabilidad 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
>
> ## Visualización del notebook

El archivo principal del análisis está disponible en dos formatos:

- `Analisis_monografia.ipynb`: notebook reproducible con el flujo de análisis y modelado.
- `Analisis_monografia.html`: versión renderizada para lectura, recomendada porque GitHub puede tardar o fallar al visualizar notebooks pesados.
