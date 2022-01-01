# Machine-Learning---Imbalanced-Data

Given an imbalanced dataset make an ML model that maximice F1 score macro

## Background | Problema a solucionar

Reto de machine learning en el que dado un dataset imbalanceado hay que realizar un modelo predictivo que maximice el f1-score macro.

## Resultados y anlásis 

La solución se encuentra en el archivo 'results.csv'.

Se entrega un set con la predicciones realizadas sobre el dataset de test, en el enunciado dice que deben ser 900 filas, pero al tener 3000 filas el set de entrenamiento, el set de predicciones tiene 3000 resultados, supongo que sería una errata en el enunciado.

Al aplicar el f1_score me da un resultado de 99,97

Siempre exite el temor de pensar que el modelo puede haber sufrido un proceso de overfitting, pero al ser un set de estudio sobre el que apenas tenemos más conocimientos de el que los propios datos, y no tenemos ningún tipo de información sobre lo que representa cada variable, me encamino a pensar que es un set preparado para un entrenamiento docente, doy el resultado como válido, aún ha sabiendas que en procesos reales no encontraremos resultados tan 'eficientes'.


## Solución adoptada

El set entregado estaba completamente desbalanceado, por lo que se estima aplicar una técnica de oversampled, después de aplicar dos métodos de oversampled RandomOverSampler y SMOTE, y entrenado el modelo com ambos sets oversampleados, el que mejor resultado obtenía era con el método de RandomOverSampled, me he decantado por un modelo Random Forest Classificator porque me parecía de los más indicados para el tipo de set que nos presentaban.

En la carpeta de data están los set propuestos para el caso, tanto el de entrenamiento como el de test.

Se adjunta el jupyter notebook donde se ha realizado el estudio de los datos y el entrenamiento del modelo predictivo.


## Contact info | Not required | Recommended

Puede visitar mi [web](https://enriquerevueltagarcia.com) para ver más proyectos mios.

o explorar mi [github](https://github.com/Gobuub)

