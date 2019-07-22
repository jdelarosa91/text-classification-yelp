# Clasificación de Textos - Yelp! 
En este repositorio se encuentra el código realizado durante el Trabajo de Fin de Master: "Inteligencia Artificial y Big Data: Clasificación de Textos", en el cual se realiza una clasificación de textos del dataset de Yelp!.
De este dataset, se utiliza el fichero review.json el cual contiene el conjunto de opiniones de los distintos clientes y el número de "estrellas" asignados. El objetivo es a partir del texto poder predecir el número de estrellas a asignar, lo cual corresponde a una clasificación basada en el sentimiento.

Para ello se construyen algoritmos de dos tipos:
1. Algoritmos no distribuidos: Se desarrollan mediante el framework Scikit Learn en Python. Se utiliza un notebook de Jupyter como IDE.
2. Algoritmos distribuidos: Se desarrollan mediante el framework Apache Spark (y su framework ML) en Scala. Se utiliza un notebook de Apache Zeppelin como IDE.
