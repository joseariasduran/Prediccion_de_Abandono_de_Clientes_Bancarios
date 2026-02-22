# 📊 Beta Bank -- Predicción de Cancelación de Clientes (Churn)

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo predecir la cancelación de clientes
(churn) en un banco utilizando técnicas de análisis de datos y Machine
Learning.

La cancelación de clientes representa una pérdida significativa para las
instituciones financieras. Mediante modelos predictivos, es posible
anticipar qué clientes tienen mayor probabilidad de abandonar el banco y
tomar acciones preventivas.

------------------------------------------------------------------------

## 🎯 Objetivos

-   Analizar el comportamiento de los clientes.
-   Identificar variables relevantes que influyen en la cancelación.
-   Construir modelos de Machine Learning para predecir churn.
-   Evaluar el desempeño de los modelos utilizando métricas adecuadas.
-   Optimizar el modelo para mejorar su capacidad predictiva.

------------------------------------------------------------------------

## 🗂 Dataset

El dataset contiene información de clientes del banco, incluyendo:

-   Score crediticio
-   País
-   Género
-   Edad
-   Antigüedad
-   Balance
-   Número de productos
-   Uso de tarjeta de crédito
-   Membresía activa
-   Salario estimado
-   Variable objetivo: **Exited (0 = No canceló, 1 = Canceló)**

------------------------------------------------------------------------

## 🧪 Metodología

1.  **Exploratory Data Analysis (EDA)**
    -   Análisis estadístico descriptivo
    -   Visualización de distribución de variables
    -   Detección de desbalance de clases
2.  **Preprocesamiento**
    -   Codificación de variables categóricas
    -   Escalado de variables numéricas
    -   División en entrenamiento y prueba
3.  **Modelado**
    -   Regresión Logística
    -   Random Forest
    -   Gradient Boosting (opcional)
4.  **Evaluación**
    -   Accuracy
    -   Precision
    -   Recall
    -   F1-Score
    -   ROC-AUC

------------------------------------------------------------------------

## 📈 Resultados

El modelo final logra identificar clientes con alta probabilidad de
churn con un balance adecuado entre precisión y recall, priorizando la
detección de clientes en riesgo.

------------------------------------------------------------------------

## 🛠 Tecnologías Utilizadas

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Scikit-learn
-   Jupyter Notebook

------------------------------------------------------------------------

## ▶️ Cómo Ejecutar el Proyecto

1.  Clonar el repositorio:

git clone https://github.com/joseariasduran/Prediccion_de_Abandono_de_Clientes_Bancarios.git

2.  Instalar dependencias:

pip install -r requirements.txt

3.  Abrir el notebook:

jupyter notebook Beta_Bank_Churn.ipynb

------------------------------------------------------------------------

## 📊 Posibles Mejoras Futuras

-   Implementar técnicas de balanceo (SMOTE)
-   Ajuste de hiperparámetros con GridSearch
-   Deploy del modelo con Flask o FastAPI
-   Creación de dashboard con Streamlit
-   Interpretabilidad con SHAP

------------------------------------------------------------------------

## 👤 Autor

José de Jesús Arias Durán\
Data Scientist Jr \| Python \| SQL \| Machine Learning
