# Credit-Risk

El objetivo principal de este proyecto es desarrollar un modelo de clasificación que permita determinar la elegibilidad de los clientes para la concesión de un préstamo bancario, basándose en la variable de destino ("target"). Esta variable indicará si a un cliente se le puede otorgar un préstamo (0) o no (1).

Los datos fueron seleccionados de una competencia de la web de kaggle, https://www.kaggle.com/competitions/home-credit-default-risk.

Para lograr este objetivo, se llevará a cabo un análisis exhaustivo de los datos disponibles, que incluirán información demográfica, financiera y de comportamiento de los clientes. 

El foco principal fue utilizar herramientas para seleccionar las variables mas influyentes en los distintos modelos utilizados, ejemplo SelectKBest, SelectFromModel y posteriormente, con el mejor modelo, optimizar mediante GridSearchCV.

