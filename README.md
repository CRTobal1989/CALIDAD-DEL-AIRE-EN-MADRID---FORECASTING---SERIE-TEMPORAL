# 📊 Evaluación Predictiva de la Calidad del Aire en Madrid  
## Modelización Comparativa entre Métodos Estadísticos Clásicos y Técnicas Avanzadas de Machine Learning

---

## 📌 Descripción del Proyecto

Este repositorio contiene el desarrollo íntegro de un trabajo orientado a evaluar la viabilidad de cumplimiento de los objetivos de calidad del aire establecidos en la Agenda 2030, mediante el análisis y modelización predictiva de los niveles de partículas en suspensión en la ciudad de Madrid.

El trabajo aborda el problema desde una perspectiva cuantitativa y predictiva, combinando metodologías estadísticas tradicionales con técnicas avanzadas de *machine learning* y *deep learning*, con el objetivo de identificar qué enfoques ofrecen mayor robustez, capacidad explicativa y precisión predictiva en series temporales ambientales.

---

## 🎯 Objetivos

- Analizar la evolución histórica de los niveles de partículas en suspensión (PM).
- Construir series temporales completas a partir de datos reales procedentes de estaciones de medición.
- Implementar modelos clásicos de predicción (ARIMA, SARIMAX).
- Comparar su desempeño con modelos de *machine learning* (CatBoost, LightGBM, XGBoost).
- Evaluar arquitecturas de *deep learning* (LSTM, redes convolucionales).
- Medir el rendimiento predictivo mediante métricas robustas (RMSE, MAE, etc.).
- Determinar la capacidad de los modelos para anticipar posibles incumplimientos normativos.

---

## 🧠 Enfoque Metodológico

### 1️⃣ Preparación y Tratamiento de Datos
- Integración de múltiples ficheros CSV.
- Identificación y gestión de valores faltantes.
- Transformación de datos a formato largo.
- Construcción de series temporales completas y consistentes.
- Análisis exploratorio y detección de estacionalidad y tendencias.

### 2️⃣ Modelización Estadística Clásica
- Modelos ARIMA.
- Modelos SARIMAX con variables exógenas.
- Descomposición temporal y análisis de residuos.

### 3️⃣ Machine Learning
- CatBoost  
- LightGBM  
- XGBoost  

Se incorporan variables temporales derivadas, rezagos (*lags*) y variables exógenas para mejorar la capacidad predictiva.

### 4️⃣ Deep Learning
- Redes neuronales recurrentes (LSTM).
- Redes convolucionales aplicadas a series temporales.
- Evaluación de estabilidad y generalización.

---

## 📈 Métricas de Evaluación

Los modelos se comparan utilizando:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- Capacidad de generalización en conjuntos de validación
- Análisis de residuos
- Robustez ante cambios estructurales

El análisis no se limita únicamente al error predictivo, sino que incorpora una evaluación crítica de la interpretabilidad y aplicabilidad práctica de cada enfoque.

---

## 🌍 Contexto Estratégico

La calidad del aire constituye un eje central en la transición ecológica y en el cumplimiento de los compromisos climáticos europeos. La capacidad de anticipar episodios críticos de contaminación permite:

- Diseñar políticas públicas más eficientes.
- Optimizar medidas restrictivas temporales.
- Reducir impactos sanitarios.
- Mejorar la planificación urbana sostenible.

Este trabajo se enmarca en la intersección entre análisis de datos, sostenibilidad ambiental y toma de decisiones basada en evidencia.

---

## 🛠️ Tecnologías Utilizadas

- R / Python  
- Librerías de series temporales (`forecast`, `prophet`, `statsmodels`)
- Frameworks de *machine learning* (CatBoost, LightGBM, XGBoost)
- Deep learning (Keras / TensorFlow o PyTorch)
- Herramientas de visualización y análisis exploratorio

---

