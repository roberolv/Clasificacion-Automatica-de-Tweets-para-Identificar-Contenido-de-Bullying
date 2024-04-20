# Clasificacion-Automatica-de-Tweets-para-Identificar-Contenido-de-Bullying (NLP)

En este ejercicio, abordamos la detección de contenido de odio en tweets de 2 maneras distintas y complementarias, en un primer intento por ingenieria de caracteristicas y después mediante modelos de clasificación de texto. Utilizamos un conjunto de datos etiquetados manualmente y entrenamos un modelo BERT básico en el segundo notebook. Comparando con un enfoque de ingeniería de características, evaluamos la eficacia de ambos métodos y destacamos sus fortalezas y limitaciones. Este análisis proporciona una visión completa de cómo abordar el problema de la detección de contenido de odio en redes sociales asi como los pros y contras de los distintos enfoques que realizamos

En resumen, las métricas del modelo de red neuronal son generalmente mejores que las de la ingeniería de características, aunque no hay una diferencia abismal en este caso sorprendentemente. Sin embargo, la red neuronal sacrifica explicabilidad y conocimiento de las variables en favor de la capacidad de capturar automáticamente patrones complejos en los datos.

La ingeniería de características ofrece características diseñadas específicamente, lo que puede adaptarse mejor a problemas particulares y ser más interpretable. Sin embargo, puede ser más complicado definir relaciones entre características y salidas, especialmente en datos altamente interconectados.

Las redes neuronales son más rápidas y fáciles de escalar, especialmente en conjuntos de datos masivos, pero requieren una mayor capacidad de computación y pueden necesitar GPUs para entrenar eficientemente.

En cuanto a la mejora del modelo, la red neuronal muestra un mayor recall en la clase 1, lo que indica una mejor detección de contenido de odio. Si se balancean los datos, las métricas podrían mejorar aún más para la clase 0 en la red neuronal.

Comparando las matrices de confusión, la red neuronal muestra una menor tasa de errores en general, lo que la hace más adecuada para predecir con precisión sin tener en cuenta la explicabilidad del modelo. Sin embargo, si se valora la explicabilidad y adaptabilidad, la ingeniería de características sigue siendo una opción sólida..
