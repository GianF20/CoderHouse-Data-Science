**Curso: Data Science**
**Comisión: 61750**
**Proyecto: Rotacion de personal - People analytics**
**Alumno: Gian Franco Medina Robert**


**Introducción**
Este análisis se enfoca en predecir la variable 'Attrition', determinando si un empleado abandonará la empresa o no. Se utilizarán técnicas de clasificación junto con análisis exploratorio de datos para comprender los factores que influyen en la rotación. Visualizaciones y estadísticas descriptivas ayudarán a responder la pregunta problema, formulando hipótesis clave sobre la retención de empleados.

Este trabajo está dirigido a profesionales y responsables en el área de Recursos Humanos, gerentes de talento humano, consultores organizacionales y académicos interesados en la gestión del personal. Los hallazgos y metodologías presentados aquí proporcionan herramientas y conocimientos prácticos para identificar las causas de la rotación de personal y desarrollar estrategias efectivas para mejorar la retención de empleados en las organizaciones.
Preguntas problemas
¿Cuáles son las principales características asociadas con la rotación de empleados?
¿Existe una relación entre el nivel del puesto y la rotación?
¿Los empleados con mayor antigüedad tienen menor probabilidad de abandonar la empresa?
Hipótesis
Los empleados con nivel de puesto más altos tienen una mayor tasa de rotación.
Los empleados con mayor antigüedad tienen menor probabilidad de abandonar la empresa.
Factores salariales y de promoción influyen significativamente en la decisión de rotación.

Visualizaciones
***************

Modelo Gradient Boosting: Accuracy de 85.03% es bastante bueno para un modelo de clasificación, indicando que el modelo tiene un buen desempeño en cuanto a predicción correcta de rotación. 
Parece ser el modelo adecuado para predicción de rotación de empleados, ya que ofrece un buen rendimiento de clasificación. Sin embargo, sería útil considerar otras métricas de clasificación como precisión, recall o F1-score para tener una evaluación más completa.
Modelo Linear Regression: El MSE es bajo, lo que indica que las predicciones del modelo no se desvían mucho de los valores reales. Sin embargo, el R² es bajo, lo que sugiere que el modelo no está capturando bien la variabilidad de los datos y que hay mucho margen para mejorar en la predicción. 
Este modelo no parece ser el modelo adecuado para este tipo de problema, especialmente dado el bajo R². Elegí entrenar este modelo para compararlo con el modelo Gradient Boosting, este anterior es el mejor para este trabajo, más allá de que existen otros modelos que pueden ir muy bien en este proyecto.
Insights
En el marco del análisis realizado para predecir la variable 'Attrition' y comprender los factores que influyen en la rotación de empleados, se han obtenido los siguientes hallazgos clave:
Principales Características Asociadas con la Rotación de Empleados:
Satisfacción Laboral: La insatisfacción en el puesto de trabajo se identifica como un factor determinante en la decisión de los empleados de abandonar la empresa. Aquellos con bajos niveles de satisfacción presentan una mayor tendencia a la rotación.
Clima Organizacional: Un ambiente laboral negativo, caracterizado por una comunicación deficiente y falta de reconocimiento, contribuye significativamente a la rotación de personal.
Prácticas de Recursos Humanos: Políticas inadecuadas en gestión de talento, como la ausencia de planes de carrera y desarrollo profesional, están correlacionadas con tasas más altas de rotación.
Relación entre el Nivel del Puesto y la Rotación:
Niveles Jerárquicos Superiores: Contrario a la hipótesis inicial, se observa que los empleados en posiciones de mayor responsabilidad no necesariamente presentan una mayor tasa de rotación. De hecho, la estabilidad en estos niveles suele ser mayor, posiblemente debido a incentivos y compromisos contractuales más sólidos.
Posiciones Operativas: Los empleados en niveles operativos o de entrada muestran una mayor propensión a la rotación, posiblemente debido a menores barreras de salida y oportunidades más frecuentes en el mercado laboral.
Antigüedad y Probabilidad de Rotación:
Empleados con Mayor Antigüedad: Los datos indican que a mayor antigüedad en la empresa, menor es la probabilidad de rotación. Esto puede atribuirse a un mayor compromiso organizacional y beneficios acumulados que incentivan la permanencia.
Nuevos Ingresos: Los empleados con menor tiempo en la organización presentan tasas más altas de rotación, lo que sugiere la necesidad de fortalecer los procesos de inducción y seguimiento durante los primeros meses de contratación.
Influencia de Factores Salariales y de Promoción:
Remuneración Competitiva: Se confirma que paquetes salariales poco competitivos están asociados con una mayor intención de abandono por parte de los empleados.
Oportunidades de Crecimiento: La falta de perspectivas claras de promoción y desarrollo profesional dentro de la empresa se correlaciona positivamente con la rotación, indicando que los empleados buscan organizaciones que ofrezcan un camino de crecimiento definido.

Conclusiones
Estos insights proporcionan una comprensión detallada de los factores que influyen en la rotación de personal dentro de la empresa. Basándose en estos hallazgos, se pueden diseñar estrategias enfocadas en mejorar la satisfacción laboral, optimizar el clima organizacional, revisar las políticas de recursos humanos y ofrecer planes de carrera atractivos para reducir la rotación y fomentar la retención del talento.
