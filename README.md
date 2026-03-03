# Heart-Disease-Prediction-model

Descripcion: Desarrolle un modelo predictivo para detectar usuarios que tengan altas posibilidades de desarrollar enfermedades cardiacas, puede ser usado como base el servicio de salud para identificar pacientes con riesgo de tener enfermedades cardiacas. Las metricas de evaluacion que se utilizo para ver que tan bueno era el modelo fue la Precision, Recall, el F1 y tambien AUC_ROC, pero me enfoque en Recall para detectar mas pacientes enfermos.

Tecnoligia y librerias utilizadas: Utilice Python y las librerias pandas, sklearn, matplotlib, numpy y seaborn. Ademas utilice el modelo RandomForest y el modelo Regresion logistica

Responsabilidad clave: Ademas de la limpieza de datos, se realizo una EDA (analisis exploratorio de datos), se crearon dos modelos (RamdonForest y Regresion Logistica), se comparararon y se tomo el mejor (Regresion Logistica) para su optimizacion y obtener el mejor resultado de identificacion de pacientes enfermos.

Impacto logrado: 
🔹 Sensibilidad (Recall): 93.5% → Detectamos 935 de cada 1,000 enfermos
🔹 Especificidad: 80.7% → Clasificamos correctamente 807 de cada 1,000 sanos
🔹 Precisión: 79.7% → 8 de cada 10 diagnósticos positivos son correctos
🔹 AUC-ROC: 0.954 → Capacidad discriminativa EXCELENTE
