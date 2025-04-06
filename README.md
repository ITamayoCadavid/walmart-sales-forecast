<p align="center">
  <img src="cover.png" alt="Walmart Sales Forecasting" width="600"/>
</p>

<h1 align="center">🛒 Walmart Sales Forecasting</h1>
<p align="center">Predicción de ventas semanales en tiendas Walmart con Machine Learning</p>

---

## 📌 Descripción

Este proyecto analiza datos reales proporcionados por Walmart para estudiar el comportamiento de las ventas semanales, con especial énfasis en el impacto de fechas festivas como **Navidad**, **Thanksgiving**, **Super Bowl** y **Labor Day**.

Se desarrolló un modelo de aprendizaje automático que permite predecir las ventas semanales por tienda, incorporando factores como el tiempo, el desempleo, la inflación, promociones y estacionalidad.

---

## 🎯 Objetivos

- Analizar los factores que impactan las ventas semanales.
- Evaluar la influencia de las semanas festivas en el comportamiento de compra.
- Predecir ventas semanales utilizando técnicas de Machine Learning.
- Desarrollar un portafolio profesional que demuestre habilidades en EDA, modelado y visualización de datos.

---

## 🧰 Herramientas y tecnologías

- 🐍 Python (Google Colab)
- 📊 Pandas, Matplotlib, Seaborn
- 🧠 Scikit-learn (Random Forest)
- 💾 Dataset: [Walmart Sales Forecast - Kaggle](https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast)

---

## 📈 Análisis Exploratorio (EDA)

- Limpieza y tratamiento de valores nulos.
- Visualizaciones de tendencias de ventas.
- Análisis de correlación entre variables.
- Estudio del impacto de días festivos.

---

## 🤖 Modelado

- División de datos: Train/Test.
- Modelo aplicado: `RandomForestRegressor`.
- Métricas de evaluación:
  - RMSE: 21,962.37
  - R²: 0.0750

---

## 🧠 Conclusiones

- Las semanas festivas tienen un impacto relevante en el volumen de ventas.
- Variables como el desempleo y la temperatura muestran cierta relación con la variabilidad en ventas.
- Se recomienda seguir optimizando el modelo con:
  - Ingeniería de características
  - Algoritmos más avanzados (XGBoost, LightGBM)
  - Ajuste de hiperparámetros

---

## 🚀 Cómo ejecutar

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/ITamayoCadavid/walmart-sales-forecast.git

   # 📊 Dashboard: Pronóstico de Ventas de Walmart

🔗 [Ver Dashboard en Looker Studio]([https://lookerstudio.google.com/reporting/YOUR_LINK_HERE](https://lookerstudio.google.com/reporting/17931a0e-87fe-462d-aef1-a71fded29e77))

Este dashboard fue creado con **Looker Studio** y conectado a **Google Sheets** como fuente de datos. Incluye:

- 📈 Comparación en series temporales de ventas reales vs. ventas pronosticadas  
- 📊 Gráfico de barras por mes para análisis de estacionalidad  
- 📅 Filtro de fechas para análisis por periodo  
- 🏬 Filtros dinámicos por tienda y departamento  
- 🧠 Gráfico de dispersión para explorar la relación entre el **IPC (CPI)** y las ventas semanales  
- 🎯 Scorecards con métricas clave como ventas máximas, número de tiendas, etc.

---

## 🎯 Objetivo

El objetivo del dashboard es ofrecer una **visión completa del comportamiento de las ventas** a lo largo del tiempo

