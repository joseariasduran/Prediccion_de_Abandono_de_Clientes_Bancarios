📊 Beta Bank – Predicción de Cancelación de Clientes (Churn)
📌 Descripción del Proyecto

Este proyecto tiene como objetivo predecir la cancelación de clientes (churn) en un banco utilizando técnicas de análisis de datos y Machine Learning.

La cancelación de clientes representa una pérdida significativa para las instituciones financieras. Mediante modelos predictivos, es posible anticipar qué clientes tienen mayor probabilidad de abandonar el banco y tomar acciones preventivas.

🎯 Objetivos

Analizar el comportamiento de los clientes.

Identificar variables relevantes que influyen en la cancelación.

Construir modelos de Machine Learning para predecir churn.

Evaluar el desempeño de los modelos utilizando métricas adecuadas.

Optimizar el modelo para mejorar su capacidad predictiva.

🗂 Dataset

El dataset contiene información de clientes del banco, incluyendo:

Score crediticio

País

Género

Edad

Antigüedad

Balance

Número de productos

Uso de tarjeta de crédito

Membresía activa

Salario estimado

Variable objetivo: Exited (0 = No canceló, 1 = Canceló)

🧪 Metodología

Exploratory Data Analysis (EDA)

Análisis estadístico descriptivo

Visualización de distribución de variables

Detección de desbalance de clases

Preprocesamiento

Codificación de variables categóricas

Escalado de variables numéricas

División en entrenamiento y prueba

Modelado

Regresión Logística

Random Forest

(Opcional) Gradient Boosting / XGBoost

Evaluación

Accuracy

Precision

Recall

F1-Score

ROC-AUC

📈 Resultados

El modelo final logra identificar clientes con alta probabilidad de churn con un balance adecuado entre precisión y recall, priorizando la detección de clientes en riesgo.

(Aquí puedes agregar métricas reales de tu notebook si quieres hacerlo más sólido.)

🛠 Tecnologías Utilizadas

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

Jupyter Notebook

▶️ Cómo Ejecutar el Proyecto

Clonar el repositorio:

git clone https://github.com/tu-usuario/beta-bank-churn.git

Instalar dependencias:

pip install -r requirements.txt

Abrir el notebook:

jupyter notebook Beta_Bank_Churn.ipynb
📊 Posibles Mejoras Futuras

Implementar técnicas de balanceo (SMOTE)

Ajuste de hiperparámetros con GridSearch

Deploy del modelo con Flask o FastAPI

Creación de dashboard con Streamlit

Interpretabilidad con SHAP

👤 Autor

José Arias
Data Scientist Jr | Python | SQL | Machine Learning

📫 Conecta conmigo en LinkedIn
📂 Portafolio en constante actualización
