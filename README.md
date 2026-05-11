# Modelo de Machine Learning con arquitectura de Red Neuronal Artificial con capas ocultas integrado

En este Notebook estaremos abordando una problemática de una entidad financiera, la cual aprueba o niega créditos a solicitantes de crédito. 
En el dataset utilizado tenemos apróximadamente unos 16.700 solicitantes los cuales cuentan con múltiples características socioeconómicas al igual que hábitos financieros.
Haciendo una limpieza del dataset al elegir las características y hábitos con mayor correlación, entrenamos módelos predictivos binarios como Naive Bayes, Árboles de decisión, o K Nearest Neighbors.
Posteriormente, elegimos uno de los modelos que mejor se adapte para presentar a la entidad financiera, junto con la justificación del por qué fue elegido.
Esto para así poder segmentar / clusterizar a los solicitantes, e incluso gráficar en 3 dimensiones (los ejes son las variables con mayor correlación en el dataset).

Finalmente se implementa una Red Neuronal Artificial con capas ocultas con el objetivo de ver cómo se comporta mejor, si como un modelo predictivo de clasificación binaria. O, como un modelo de regresión.
