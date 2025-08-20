# Challenge-TelecomX2
# 🔮 Predicción de Cancelación de Clientes (Churn Prediction)

Este repositorio contiene un pipeline completo de **Machine Learning** para predecir la **probabilidad de cancelación de clientes**.  
El objetivo principal es ayudar a la empresa a **anticipar la baja de usuarios** y diseñar estrategias de **retención proactiva**.

---

## 📌 Objetivos del Proyecto

1. **Preparación de datos**: tratamiento de valores faltantes, codificación de variables categóricas y normalización.  
2. **Análisis exploratorio (EDA)**: distribución de variables, correlaciones y detección de patrones relevantes.  
3. **Selección de variables**: análisis de correlación, información mutua (*mutual information*) y reducción de colinealidad.  
4. **Entrenamiento de modelos**: comparar al menos dos modelos de clasificación (Regresión Logística, Random Forest, XGBoost).  
5. **Evaluación de desempeño**: métricas ROC AUC, PR AUC, F1, Precisión, Recall y validación cruzada.  
6. **Interpretación**: análisis de importancia de variables (Permutation Importance, SHAP).  
7. **Conclusión estratégica**: identificar los factores clave de la cancelación y proponer recomendaciones de negocio.

---

## 📂 Estructura del Repositorio

```bash
├── datos_final.csv              # Dataset principal
├── modelo_final.ipynb           # Notebook de referencia con pruebas previas
├── challenge_final.ipynb        # Notebook original del desafío
├── churn_pipeline.ipynb         # Notebook principal con el pipeline final
├── outputs/                     # Resultados y artefactos generados
│   ├── best_model_*.pkl         # Modelo entrenado y serializado
│   ├── model_results.csv        # Métricas de los modelos
│   ├── permutation_importance.csv
│   ├── conclusion_estrategica.json
│   └── gráficos (.png)          # ROC, PR, Matriz de confusión, SHAP, etc.
└── README.md
