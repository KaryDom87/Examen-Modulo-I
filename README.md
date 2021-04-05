# Examen-Modulo-I
Examen Modulo I WA
Marzo 2021

1.	Considere el conjunto de datos Breast Cancer Wisconsin  disponible en el archivo zip correspondiente. 
2.	Eliga uno de los algoritmos vistos durante el módulo (perceptrón simple, árboles de decisión, regresión logistica, knn) para construir un clasificador.
3.	Justifique la elección del algoritmo y reporte los resultados

El algoritmo utilizado para realizar la clasificación fue knn. Al realizar un análisis exploratorio de la base de datos se descarto utilizar el algoritmo de arboles de decisión, debido a que no se presentaba ninguna variable categórica para realizar la clasificación. De igual forma, al tratarse de variables numéricas que representaban medidas como la longitud o área, se opto por utilizar knn ya que es el óptimo para este tipo de datos.

Resultados

El algoritmo utilizado nos arrojó una precisión del 98% tanto en el conjunto de entrenamiento como en el de prueba con un k=3, lo que nos indica que es un buen modelo para realizar la clasificación de nuestros datos.
.
