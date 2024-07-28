Laboratorio | Datos desequilibrados
Utilizaremos el files_for_lab/customer_churn.csvconjunto de datos para construir un predictor de abandono.

Instrucciones
Cargue el conjunto de datos y explore las variables.
Intentaremos predecir la variable Churnutilizando una regresión logística sobre las variables tenure, SeniorCitizen, MonthlyCharges.
Extraer la variable de destino.
Extraer las variables independientes y escalarlas.
Construir el modelo de regresión logística.
Evaluar el modelo.
Incluso un modelo simple nos dará una precisión de más del 70%. ¿Por qué?
La técnica de sobremuestreo de minorías sintéticas (SMOTE) es una técnica de sobremuestreo basada en vecinos más próximos que agrega nuevos puntos entre puntos existentes. Aplicar imblearn.over_sampling.SMOTEal conjunto de datos. Construir y evaluar el modelo de regresión logística. ¿Hay alguna mejora?
Los enlaces de Tomek son pares de instancias muy cercanas, pero de clases opuestas. Eliminar las instancias de la clase mayoritaria de cada par aumenta el espacio entre las dos clases, lo que facilita el proceso de clasificación. Aplicar imblearn.under_sampling.TomekLinksal conjunto de datos. Construir y evaluar el modelo de regresión logística. ¿Hay alguna mejora?
