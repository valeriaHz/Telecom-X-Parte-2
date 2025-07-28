# Telecom-X-Parte-2

## Predicción y Análisis de Cancelación de Clientes (Churn)

### Descripción

Este proyecto implementa modelos de machine learning para predecir la cancelación de clientes (churn) y analizar los factores que más influyen en dicha cancelación. Se comparan diferentes modelos, se ajustan hiperparámetros y se realiza ingeniería de variables para mejorar el desempeño.

---

### Contenido

- **Preparación de datos:** División en entrenamiento y prueba, normalización y creación de variables polinómicas.  
- **Modelos implementados:**  
  - Regresión Logística con variables polinómicas y normalización.  
  - Random Forest con ajuste de hiperparámetros usando GridSearchCV.  
- **Evaluación:**  
  - Métricas: F1-score, precisión, recall, exactitud y matriz de confusión.  
  - Validación cruzada para estimar desempeño robusto.  
- **Análisis de importancia:**  
  - Interpretación de coeficientes en regresión logística.  
  - Importancia de variables en Random Forest.  
- **Estrategias de retención:** Basadas en variables clave identificadas.

---

### Requisitos

- Python 3.x  
- Librerías:  
  - pandas  
  - numpy  
  - scikit-learn  
  - matplotlib  
  - seaborn (opcional para gráficos adicionales)
