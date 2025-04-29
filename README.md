
# 🥑 Predicción del Precio del Aguacate

Este proyecto tiene como objetivo predecir el precio promedio del aguacate en Estados Unidos, utilizando técnicas de análisis exploratorio de datos, limpieza y normalización, y modelos de aprendizaje automático supervisado.

## 📊 Dataset

- Fuente: [Kaggle - Avocado Prices](https://www.kaggle.com/datasets/neuromusic/avocado-prices)
- Registros: 18,249
- Variables: Precios, volúmenes de venta, tipo de producto, región y fecha.

## 🧩 Estructura del Proyecto

1. **Análisis Descriptivo (`AnalisisDescriptivo.ipynb`)**  
   - Visualización de distribuciones, outliers, correlaciones y estacionalidad.

2. **Limpieza y Normalización (`LimpiezaNormalizacion.ipynb`)**  
   - Eliminación de columnas innecesarias, detección y tratamiento de outliers, normalización de variables y codificación categórica.

3. **Modelado Predictivo (`ModelosPredictivos.ipynb`)**  
   - Entrenamiento de modelos: Regresión Lineal, Árbol de Decisión, Random Forest, Gradient Boosting y Red Neuronal (MLP).
   - Evaluación con métricas como MSE y R².

## ⚙️ Tecnologías utilizadas

- Python 3
- Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 🧠 Hallazgos clave

- Gradient Boosting fue el modelo más preciso con un R² de 0.93.
- Se observó estacionalidad clara en los precios y diferencias relevantes por tipo y región.
- La limpieza y normalización mejoraron significativamente la calidad del modelado.

## 🚀 Posibles mejoras

- Incorporar variables exógenas (eventos, clima, fechas clave).
- Aplicar modelos de series temporales (ARIMA, Prophet).
- Entrenar modelos especializados por tipo o región.

## 👥 Integrantes del equipo

- SebastianGomez5
- vicmaHo
- StivenHenao
---

Proyecto académico – Universidad del Valle, Ciencia de Datos – 2025.
