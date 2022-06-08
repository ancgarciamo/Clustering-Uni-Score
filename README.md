# Clustering-Uni-Score
El siguiente dataset de college scoreboard


## Pre-procesamiento de datos
El dataset contiene una dimensionalidad extremadamente alta de 1715 columnas , siendo estas muchas variables , para ello empezaremos por descartar columnas que posean algún dato nulo, dejando únicamente 16 columnas.

usando un código para descartar las variables que no son numéricas, y al final nos quedan 12 columnas con datos unicamente numéricos y sin valores nulos.


## Matriz de correlacion
Lo siguiente sera escoger las posibles variables a analizar para aplicar el metodo de k-means, para esto hacemos una matriz de coorelacion y escogemos las variables mas dispersas







Como vemos las variables que quedaron  , en su mayoría casi no se relacionan linealmente, ahora escogeremos 3 variables para el método de k-means , entonces escogeremos 3 variables que puedan darnos significado para el analisis de clusters, por ejemplo variables como UNITD Y OPEID no pueden ser buenas ya que simplemente son un identificador para cada institución , Sin embargo el resto de variables que quedan por lo general son categoricas , segun las recomendaciones del enunciado donde se publico el ejercicio originalmente , para trabajar con estas variables , usaremos el k-means con una distancia de coseno.

Sabiendo esto escogemos las variables , CONTROL , HIGHDEG y región
Para encontrar el k adecuado se usaran los metodos del estadistico de gap , la curva del codo y el analisis de siluetas adaptados para una distancia con coseno.

## Curva del codo

Para la curva del codo la primera inclinacion importante la tomaremos en k=3



## Estadistico de Gap

ahora para encontrar el k adecuado para el metod
