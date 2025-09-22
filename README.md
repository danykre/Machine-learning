Proyecto Final – Data Science II (CoderHouse)
📌 Descripción

Este proyecto tiene como objetivo predecir el Precio_Total de ventas de la empresa ficticia Digital Soluciones S.A..
A través de un flujo completo de Data Science, se aplicaron técnicas de limpieza, análisis exploratorio de datos (EDA) y modelado predictivo con algoritmos de regresión lineal, evaluando su desempeño para seleccionar el modelo más adecuado.

El trabajo fue realizado en el marco del curso Data Science II de CoderHouse.

📂 Archivos del repositorio

Digital_Soluciones.xlsx → Dataset utilizado para el análisis.

proyecto_final.py → Script en Python con todo el proceso: carga, limpieza, EDA, preprocesamiento, modelado y conclusiones.

Presentacion.pdf → Documento ejecutivo con el resumen del proyecto, pensado para stakeholders no técnicos.

🔍 Metodología

Data Wrangling → Limpieza de datos, imputación de nulos, estandarización y tratamiento de outliers.

EDA (Análisis exploratorio) → Identificación de patrones en métodos de pago, productos más vendidos, descuentos, estacionalidad y tiempos de envío.

Preprocesamiento → Codificación de variables categóricas y escalado de variables numéricas.

Modelado → Se entrenaron varios modelos de regresión:

Regresión Lineal (baseline)

Ridge

Lasso

Elastic Net

Random Forest (como benchmark)

Selección del modelo → El modelo Lasso optimizado fue el elegido por su equilibrio entre precisión (R² ≈ 0.87) e interpretabilidad.

📊 Resultados principales

Los productos más vendidos fueron remeras, muebles y cómics.

Los métodos de pago más utilizados fueron tarjeta de crédito, PayPal y transferencia bancaria.

Se identificaron picos de ventas en septiembre y diciembre.

El modelo Lasso optimizado explicó alrededor del 87% de la variabilidad en el monto de ventas, brindando además claridad sobre las variables más influyentes.

🚀 Futuras líneas de trabajo

Ampliar el dataset con información más reciente.

Incorporar nuevas variables relevantes (ej. promociones o características adicionales de clientes).

Implementar un sistema de reentrenamiento periódico para mantener actualizado el modelo frente a cambios en el negocio.

🛠️ Tecnologías utilizadas

Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn)

Jupyter/Colab

Excel

👨‍💻 Autor

Daniel Kresisch
Proyecto final presentado en CoderHouse – Data Science II, Comisión #67485
