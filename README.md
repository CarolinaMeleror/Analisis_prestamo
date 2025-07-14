# 📊 Análisis de Préstamos Bancarios con Machine Learning

  ## 🎯 Descripción
  Proyecto de clasificación binaria para predecir la aprobación/rechazo de préstamos bancarios usando Gradient Boosting.

  ## 📁 Dataset
  - **614 solicitudes** de préstamo
  - **13 características** (ingresos, educación, historial crediticio, etc.)
  - **Variable objetivo**: Loan_Status (Y=Aprobado, N=Rechazado)
  - **Valores faltantes**: 149 (limpiados automáticamente)

  ## 🔧 Metodología
  1. **Exploración de datos**: Análisis estadístico y visualizaciones
  2. **Limpieza**: Imputación con moda (categóricas) y mediana (numéricas)
  3. **Preprocesamiento**: Codificación de variables categóricas
  4. **Modelado**: Gradient Boosting Classifier
  5. **Evaluación**: Métricas de clasificación

  ## 📈 Resultados
  - **Precisión**: 74%
  - **Factor más importante**: Credit_History (46.1%)
  - **Mejor prediciendo**: Aprobaciones (90% recall)
