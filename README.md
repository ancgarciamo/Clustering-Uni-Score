# Clustering-Uni-Score
El siguiente dataset de college scoreboard


## Pre-procesamiento de datos
El dataset contiene una dimensionalidad extremadamente alta de 1715 columnas , siendo estas muchas variables , para ello empezaremos por descartar columnas que posean algún dato nulo, dejando únicamente 16 columnas.

usando un codigo para descartar las variables que no son numericas, y al final nos quedan 12 columnas con datos unicamente numericos y sin valores nulos .


## Matriz de correlacion
Lo siguiente sera escoger las posibles variables a analizar para aplicar el metodo de k-means, para esto hacemos una matriz de coorelacion y escogemos las variables mas dispersas
