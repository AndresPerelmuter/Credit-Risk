# Credit-Risk

El objetivo principal de este proyecto es desarrollar un modelo de clasificación capaz de determinar la elegibilidad de los clientes para la obtención de préstamos bancarios. Dicho modelo se centrará en analizar la variable objetivo ("target"), que indica si a un cliente se le puede conceder un préstamo (0) o no (1).

Los datos para este estudio fueron obtenidos de una competición en la plataforma de Kaggle, disponible en https://www.kaggle.com/competitions/home-credit-default-risk.

Para alcanzar este objetivo, se realizó un análisis exhaustivo de los datos proporcionados. Se puso especial énfasis en la selección de las variables más influyentes para los diversos modelos evaluados, utilizando herramientas como SelectKBest y SelectFromModel. Posteriormente, se optimizaron los hiperparámetros del modelo más prometedor mediante el uso de GridSearchCV.

Finalmente, se interpretaron los resultados del modelado. Esta interpretación integró los hallazgos de la exploración de datos y el análisis de la importancia de las características, proporcionada por Scikit-learn, para extraer insights valiosos del modelo desarrollado.

