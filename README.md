📊 Walmart Sales Forecasting

Proyecto de análisis y predicción de ventas semanales de tiendas Walmart, tomando en cuenta variables temporales, espaciales y semanas con feriados importantes en EE.UU.

🎯 Objetivo del Proyecto
Predecir las ventas semanales (Weekly_Sales) de cada tienda de Walmart.

Analizar si las ventas se ven afectadas por factores temporales (estaciones, feriados) y geográficos (número de tienda).

Evaluar el impacto de feriados como Navidad, Acción de Gracias, Super Bowl y Día del Trabajo en las ventas.

📁 Estructura del proyecto
Walmart_Sales_Forecasting.ipynb: Notebook principal con todo el análisis, visualizaciones y modelo predictivo.

cover.png: Imagen de portada para este proyecto.

README.md: Documentación del proyecto.

📊 Análisis Exploratorio (EDA)
Se realizó un EDA donde se exploraron:

Comportamientos de ventas por tienda y semana.

Tendencias relacionadas con el clima, el desempleo, el CPI y los precios del combustible.

Comparación de semanas con y sin feriados.

🤖 Modelo Predictivo
Se entrenó un modelo de regresión usando RandomForestRegressor para predecir ventas semanales. Las métricas obtenidas fueron:

✅ RMSE: 21,962.37

✅ R²: 0.0750

Nota: Es un modelo base que puede mejorarse con técnicas de Feature Engineering, optimización de hiperparámetros y modelos más complejos.

🧰 Herramientas y tecnologías
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Google Colab

GitHub

▶ Cómo ejecutar el proyecto
Cloná este repositorio o abrilo directamente desde Google Colab.

Asegurate de tener el archivo kaggle.json configurado para descargar los datasets desde Kaggle.

Ejecutá el notebook paso a paso.

💡 Lecciones aprendidas
Importancia del análisis exploratorio para identificar patrones temporales y espaciales.

Cómo integrar datos externos (feriados) al análisis.

Entrenamiento de modelos base como punto de partida para mejorar predicciones en proyectos reales.

