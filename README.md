# 📊 Proyecto Final – Data Science II (CoderHouse)

## 📌 Descripción
Este proyecto tiene como objetivo predecir el **Precio_Total de ventas** de la empresa ficticia **Digital Soluciones S.A.**  
Se aplicó un flujo completo de **Data Science**: limpieza de datos, análisis exploratorio (EDA), preprocesamiento, modelado y optimización de modelos de regresión lineal.  

El trabajo fue realizado en el marco del curso **Data Science II de CoderHouse (Comisión #67485)**.

---

## 📂 Archivos del repositorio
- **`Digital_Soluciones.xlsx`** → Dataset utilizado para el análisis.  
- **`proyecto_final.py`** → Script en Python con todo el proceso: carga, limpieza, EDA, preprocesamiento, modelado y conclusiones.  
- **`Presentacion.pdf`** → Documento ejecutivo con el resumen del proyecto, pensado para stakeholders no técnicos.  

---

## 🔍 Metodología
1. **Data Wrangling**  
   - Eliminación de duplicados y columnas irrelevantes  
   - Imputación de valores nulos (moda y media)  
   - Corrección de categorías y tratamiento de outliers  

2. **EDA (Exploratory Data Analysis)**  
   - Identificación de patrones en productos, clientes y métodos de pago  
   - Estacionalidad de ventas y tiempos de envío  

3. **Preprocesamiento**  
   - Codificación de variables categóricas (One-Hot Encoding)  
   - Escalado de variables numéricas (StandardScaler)  
   - División del dataset: 80% entrenamiento / 20% prueba  

4. **Modelado**  
   - Regresión Lineal (baseline)  
   - Ridge  
   - Lasso  
   - Elastic Net  
   - Random Forest (benchmark)  

5. **Optimización**  
   - Validación cruzada (5 folds)  
   - Búsqueda de hiperparámetros (GridSearchCV)  
   - Comparación de métricas  

---

## 📊 Resultados principales
- Productos más vendidos: **remeras, muebles y cómics**  
- Picos de ventas: **septiembre y diciembre**  
- La mayoría de pedidos: **Precio_Total < 1000**  
- Modelo seleccionado: **Lasso optimizado (alpha = 1)**  

### Métricas del modelo Lasso:
- **MAE:** 272.0  
- **RMSE:** 365.1  
- **R²:** 0.877  

👉 El modelo explica aproximadamente el **87% de la variabilidad** del Precio_Total y mantiene una buena interpretabilidad.

---

## 🚀 Líneas futuras
- Ampliar el dataset con información más reciente  
- Incorporar variables adicionales (ejemplo: promociones o datos de clientes)  
- Implementar un sistema de reentrenamiento periódico para mantener el modelo actualizado  

---

## 🛠️ Tecnologías utilizadas
- Python → Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn  
- Excel (dataset original)  
- Google Colab / Jupyter Notebook  

---

## 👨‍💻 Autor
**Daniel Kresisch**  
Proyecto final presentado en **CoderHouse – Data Science II**  
