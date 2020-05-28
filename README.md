# Solar-Energy-Prediction

![](sol.jpg)



Durante el bootcamp de Data Analytics en Ironhack, realizamos la siguiente competencia en Kaggle:  https://www.kaggle.com/c/solar-energy-prediction-datamex0320/overview

El conjunto de datos contiene columnas como velocidad y dirección del viento, humedad o temperatura. La competición consiste en predecir la radiación solar en esos datos. Se tienen 4 meses de datos.

La métrica de error es el MSE, por lo tanto, cuanto menor sea mejor resultado será.

Las unidades de cada columna son:

- Radiación: Radiación solar en vatios por metro ^ 2
- Temperatura: Temperatura en grados Fahrenheit
- Humedad: Humedad en%
- Presión: Presión atmosférica en mm de Hg
- Dirección del viento (grados): Dirección del viento en grados
- Velocidad: Velocidad del viento en millas por hora
- Amanecer / atardecer: Salida-Puesta del Sol (horario de Hawaii)
- UNIXTime: TimeStamp (segundos desde 01-01-1970)
- Datos: Fecha
- Hora: hora

Para la competencia, limpié los datos y los organicé de manera que obtuve información adicional como "Horas Solares". Por otro lado utilicé un modelo supervizado de machine learning de la librería Scikit-Learn llamado GradientBoostingRegressor (GBR), el cual fué entrenado con los datos limpios y con los que se obtuvieron predicciones de la energía solar.

**<u>Gracias al buen manejo de los datos y a la optimización del modelo, obtuve un MSE de 5822.54218 con el cual me posicioné en el segundo lugar de la tabla.</u>**