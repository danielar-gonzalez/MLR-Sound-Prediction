# MLR-Sound-Prediction

Este proyecto implementa un modelo de regresión lineal múltiple para predecir el nivel de presión sonora en perfiles aerodinámicos utilizando un conjunto de datos de la NASA. El objetivo es analizar la relación entre diversas características aerodinámicas (frecuencia, ángulo de ataque, longitud de cuerda, velocidad de flujo libre y espesor del desplazamiento) y el nivel de presión sonora resultante.

El conjunto de datos **"data.csv"** contiene información sobre 1052 observaciones de perfiles aerodinámicos, con 6 mediciones para cada observación:
- frecuencia: Frecuencia, en Hz.
- angulo: Ángulo de ataque, en grados.
- longitud: Longitud de cuerda geométrica, en metros.
- velocidad: Velocidad de flujo libre, en metros por segundo.
- espesor: Espesor del desplazamiento en el lado de succión, en metros.
- presion: Nivel escalado de presión sonora, en dB.

Los datos fueron descargados del UCI Machine Learning Repository y originalmente publicados en el _NASA Reference Publication 1218_.

Los resultados del modelo se presentan en el Jupyter Notebook, incluyendo:

- Un resumen del modelo que muestra los coeficientes estimados y los p-values para cada variable.
- Un análisis de la significancia de las variables y la identificación de la variable más importante.
- Los valores de RSE y R^2 para los conjuntos de entrenamiento y prueba.
- Un gráfico de dispersión de los valores reales vs. predichos de presión sonora.

**Documentos incluídos en este repositorio:**
