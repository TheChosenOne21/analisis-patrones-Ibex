# Análisis de patrones con Machine Learning.
Proyecto de construcción de modelos de Machine Learning que permitan reconocer patrones de análisis técnico dentro de una serie de precios (activos Ibex)
Se plantean tres prototipos de modelo que tienen en cuenta los diferentes procesos de un workflow de minería de datos.
Estos modelos se plantean como una tarea de clasicación en la que el modelo es capaz de identificar y clasificar los patrones básicos de trading como doble suelo, doble techo...

Para el primer caso, se busca generar un modelo de clasificación binaria que clasifique un patrón de "doble suelo" y que dicho modelo sea efectivamente mejor que la aleatoriedad.
Para el segundo caso, se busca abordar el problema como una clasificación multiclase en la que se reconozcan a la vez varias figuras técnicas: doble suelo, doble techo y
sin patrón.
Para el tercer caso, se abordará el problema desde un enfoque de aprendizaje activo. Es decir, se reentrenará el modelo utilizando los casos en los que no esté clara su frontera de decisión, pero  en los que se dará la etiqueta real de forma manual.
