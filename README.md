
# Proyecto #1: Estimación del precio de venta de vehículos
Disponemos de un conjunto de datos con información variada sobre ventas de vehículos de segunda mano en el Reino Unido. El problema de regresión a resolver consiste en predecir el precio de venta de un vehículo de segunda mano en función de sus características.



## El conjunto de datos

Para este proyecto usaremos un conjunto de datos recopilados de listas de venta de coches usados. Se dispone de información sobre 100.000 vehículos de segunda mano.

El conjunto de datos está formado por varios ficheros CSV, uno para cada fabricante de coches. Cada fila del archivo corresponde a una venta de un vehículo de segunda mano.

Las características (o features) de este conjunto de datos son las siguientes:

model - modelo del vehículo
year - año de matriculación
price - precio de venta en libras esterlinas (variable objetivo) 
transmission - tipo de transmisión
mileage - millas de uso
fuelType - tipo de carburante
tax - impuesto de circulación
mpg - consumo del vehículo en millas recorridas por galón
engineSize - cilindrada del motor en litros



## Requisitos del proyecto

Será imprescindible realizar los siguientes procesos durante la resolución del problema:

Preprocesamiento adecuado de los conjuntos de datos.
Entrenamiento y validación de diferentes modelos de regresión estudiados durante el curso (tanto clásicos como basados en redes neuronales).
Optimización con Grid Search de los hiperparámetros de cada uno de los modelos anteriores.
Validación cruzada con 5 folds de cada uno de los modelos entrenados, utilizando las siguientes métricas de calidad RMSE.
De cara a evaluar justamente, la semilla para todos aquellos métodos estocásticos será: random_state=4815.


## Sistema de evaluación
Se deberá realizar una presentación con una duración aproximada de 10 minutos el próximo viernes 12 de febrero en la que se incluyan las operaciones realizadas para el preprocesamiento, entrenamiento y validación de los modelos. Se valorará positivamente interpretar no solo las medidas de calidad obtenidas por el modelo sino también el modelo en sí mismo.



# A mejorar

Eliminar duplicados
Probar con más algoritmos de Machine Learning
Usar todo el conjunto entrenamiento para probar despues la validacion
Probar a usar solo las dummys para el PCA
