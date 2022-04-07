# Best Model

## KNN / Logistic Regression

Ambos modelos están muy cerca de poder ser el mejor para este tipo de clasificación.

Si bien es cierto que el score que muestran es algo malo. Y más cuando se trata de clasificar correctamente los positivos, pero de los 3 utilizados ambos son los mejores.

> KNN = 0.9092012624423403

> LR = 0.9085943190094683

En cambio el DT es el peor de los tres. Aunque su score no está muy atrás en comparación si es cierto que ha sacado el peor score.

> DT = 0.8999757222626851

Aún así, se podrían mejorar todos los modelos. Por ejemplo, se ha utilizado dummies para las columnas categóricas, con eso se pierde rndimiento del modelo. En cuanto al KNN se podría umentar el número de K. Y en general habría que mirar el problema de la estandarización de las features numéricas para ver si se le puede sacar más rendimiento, que en principio no, va peor. Pero es algo que habría que estudiar con calma.
