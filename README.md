# Predicción de Emisiones de CO₂ con Regresión Lineal, Ridge y Lasso

Este repositorio contiene un proyecto de análisis predictivo enfocado en estimar las emisiones de dióxido de carbono (CO₂) a partir de variables numéricas. Se implementan tres modelos de regresión y se comparan sus resultados para determinar el más adecuado.

## Contenido del análisis

- **Preparación de la base de datos**  
  - Eliminación de columnas categóricas  
  - Revisión de valores nulos mediante mapa de calor y código  
  - Separación correcta de variables independientes y dependientes  

- **Modelado predictivo**  
  - Aplicación de regresión lineal múltiple (`LinearRegression()`)  
  - Predicción para conjunto de prueba y evaluación con:
    - Coeficiente de determinación R²  
    - Error absoluto medio (MAE)  
    - Error cuadrático medio (MSE)  

- **Modelos avanzados**  
  - Implementación de regresión Ridge y Lasso  
  - Búsqueda en malla (`GridSearchCV`) para encontrar el valor óptimo de alpha  
  - Comparación estructurada de desempeño entre los tres modelos  

## Conclusiones

- La regresión múltiple ofrece una base clara para el análisis.
- Ridge y Lasso mejoran el ajuste al penalizar la complejidad del modelo.
- La elección del modelo óptimo se basa en un balance entre precisión y simplicidad.

## Requisitos técnicos

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn

## Recomendación

Ideal para quienes buscan aprender a comparar modelos de regresión y aplicar técnicas de ajuste regularizado en contextos reales. ¡Explora, experimenta y ajusta para mejorar tus predicciones!
