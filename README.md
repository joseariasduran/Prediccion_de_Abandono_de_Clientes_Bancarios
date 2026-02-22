# Prediccion_de_Abandono_de_Clientes_Bancarios
Modelo de Machine Learning en Python para predecir el abandono de clientes (churn) en el sector bancario, priorizando técnicas de balanceo de clases y optimización de la métrica F1.

# OpenRisk XAI: Transparent Credit Scoring Engine 🏦

## Descripción
OpenRisk es un motor de decisión crediticia diseñado para mitigar la "caja negra" en la banca. Utiliza algoritmos de **Machine Learning (XGBoost)** para predecir la probabilidad de default, integrando **SHAP (Shapley Additive Explanations)** para proporcionar explicabilidad regulatoria a cada decisión.

## Problema de Negocio
En el sector bancario, no basta con predecir quién pagará; las normativas (como Basilea o leyes locales) exigen explicar por qué se rechaza un crédito. Este proyecto resuelve:
1. **Precisión:** Uso de Gradient Boosting sobre métodos estadísticos tradicionales.
2. **Transparencia:** Generación automática de razones de rechazo para el oficial de cumplimiento.

## Tech Stack
* **Core:** Python, Pandas, NumPy.
* **Modelo:** XGBoost Classifier.
* **Métrica de Desempeño:** Gini Coefficient & AUC.
* **XAI (Explicabilidad):** SHAP Library.
* **Interfaz:** Streamlit.

## Cómo ejecutarlo localmente

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/TU_USUARIO/OpenRisk-XAI.git](https://github.com/TU_USUARIO/OpenRisk-XAI.git)
