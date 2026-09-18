# Predicción de Viralidad en TikTok — TFM

**Dataset:** Tik Tok Video Engagement 200k
**Fuente:** HuggingFace - https://huggingface.co/datasets/lingbow/tiktok-video-engagement-200k/tree/main

> *Nota: El dataset original no se incluye en este repositorio debido a su tamaño.*

---

## Estructura del Repositorio:

El flujo de trabajo se divide en 3 cuadernos principales ejecutados de forma secuencial:

* **`01_extraccion_y_eda.ipynb`**: Extracción de datos, limpieza inicial, análisis exploratorio de datos (EDA) y estudio de las distribuciones clave (frecuencias, engagement y visualizaciones).
* **`02_procesamiento_y_feature_engineering.ipynb`**: Transformación de variables, tratamiento de datos temporales, codificación y construcción de la variable objetivo binaria (`viral`).
* **`03_modelado_y_evaluacion.ipynb`**: Entrenamiento de modelos de clasificación supervisada, validación cruzada con `TimeSeriesSplit`, optimización de hiperparámetros y evaluación de métricas (ROC-AUC, Precision, Recall, F1-Score).
