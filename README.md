Este repositorio es una ruta de aprendizaje progresiva en análisis financiero cuantitativo y modelado estadístico aplicado a los mercados financieros del curso 'Python y estadística para el análisis financiero' (https://www.coursera.org/learn/python-statistics-financial-analysis). En algunos módulos, desarrollé contenidos teóricos sobre conceptos clave. A continuación, se describe brevemente el contenido cubierto:

1) Introducción al Análisis Financiero y Manejo de Datos: Se inicia con la importación y manipulación de datos financieros utilizando la librería Pandas en Python. Se exploran conceptos básicos de dataframes, cálculo de estadísticas descriptivas, selección de datos y visualizaciones fundamentales con Matplotlib, incluyendo gráficos de series de tiempo.

2) Conceptos Estadísticos Fundamentales: Se introducen los conceptos de resultados y variables aleatorias a través de simulaciones, el análisis de frecuencia y distribución de estas variables, incluyendo la visualización mediante gráficos de barras y la noción de frecuencia relativa que se acerca a una distribución de probabilidad con más ensayos. También se abordan la esperanza y varianza de una distribución.

3) Modelado de Rendimientos Bursátiles: Se explora el modelado de rendimientos de acciones, calculando rendimientos logarítmicos y observando su distribución, que se asemeja a una distribución normal. Se introducen conceptos importantes como la probabilidad de caídas significativas, el Valor en Riesgo (VaR) y los cuantiles de la distribución de rendimientos.

4) Inferencia Estadística: Población y Muestra: Se diferencian los conceptos de población y muestra, ilustrando el cálculo de parámetros poblacionales y estadísticos muestrales, así como la idea de un estimador insesgado. Se examina la variación de los estadísticos muestrales al tomar múltiples muestras y se introduce brevemente el Teorema del Límite Central.

5) Estimación por Intervalos: Intervalos de Confianza: Se introduce el concepto de intervalo de confianza, calculando e interpretando un intervalo de confianza del 90% para el rendimiento promedio de una acción y explicando el nivel de significancia.

6) Pruebas de Hipótesis: Se aborda el test de hipótesis para evaluar afirmaciones sobre parámetros poblacionales, como el rendimiento promedio de una acción. Se explican los pasos involucrados: establecer hipótesis nula y alternativa, calcular el estadístico de prueba (estadístico z), determinar el p-valor y tomar una decisión basada en el nivel de significancia para pruebas de dos colas y de una cola. Se profundiza en la teoría de las pruebas de hipótesis, incluyendo los conceptos clave, los tres escenarios de prueba, el nivel de significancia y la región crítica, los métodos para tomar decisiones (estadístico de prueba y p-valor), la diferencia entre la distribución normal Z y la distribución t, y los posibles errores Tipo I y Tipo II [9.1].

7) Análisis de Asociación entre Variables: Se analiza la asociación entre dos variables aleatorias, utilizando como ejemplo la relación entre los precios de las acciones de AMZN y NFLX a través de gráficos de dispersión y mencionando el coeficiente de correlación de Pearson.

8) Modelado de Regresión Lineal Simple: Se introduce el modelo de regresión lineal simple para modelar la relación entre dos variables (AMZN y NFLX), estimando el intercepto y la pendiente. Se utiliza la librería statsmodels para realizar la regresión por mínimos cuadrados ordinarios (OLS) y se interpreta la tabla resumen del modelo, incluyendo el R-cuadrado y los p-valores. Se explican en detalle los supuestos del modelo de regresión lineal simple (linealidad, independencia, normalidad y varianza constante) y se presentan métodos para diagnosticar y validar estos supuestos a través de gráficos de dispersión de residuos, pruebas estadísticas como Durbin-Watson, gráficos Q-Q y análisis de homocedasticidad [12, 12.1]. Se concluye sobre la validez del modelo basado en el cumplimiento de estos supuestos.

9) Modelado de Regresión Lineal Múltiple: Se extiende el concepto a modelos de regresión lineal múltiple, utilizando múltiples predictores para modelar una variable dependiente (como el precio de un ETF del S&P 500, SPY) basándose en datos históricos de diferentes mercados bursátiles. Se cubren pasos importantes como la división de datos en conjuntos de entrenamiento y prueba, la exploración de los datos de entrenamiento, la formulación y ajuste del modelo utilizando statsmodels, el análisis de la significancia de los predictores, la detección de multicolinealidad y la evaluación del rendimiento del modelo utilizando métricas como el RMSE ajustado y el R-cuadrado ajustado tanto en el conjunto de entrenamiento como en el de prueba para evaluar el sobreajuste. Se proporciona una base teórica sobre la regresión lineal múltiple, incluyendo la interpretación del RMSE ajustado y el R-cuadrado ajustado, así como criterios para comparar el rendimiento en conjuntos de entrenamiento y prueba 

10) Evaluación de Estrategias de Trading Basadas en Modelos de Regresión: Finalmente, se aborda la evaluación práctica de una estrategia de trading construida a partir de un modelo de regresión. Se calcula la ganancia diaria y la riqueza acumulada de la estrategia, comparándola con una estrategia de "comprar y mantener". Se introducen métricas de rendimiento prácticas como el Ratio de Sharpe y el Maximum Drawdown para evaluar el rendimiento ajustado al riesgo y las pérdidas máximas potenciales de la estrategia.

En resumen, esta ruta de aprendizaje que abarca desde la importación y exploración básica de datos financieros hasta la construcción, diagnóstico y evaluación de modelos de regresión lineal simple y múltiple para la predicción y el desarrollo de estrategias de trading, incorporando conceptos estadísticos fundamentales a lo largo del camino.