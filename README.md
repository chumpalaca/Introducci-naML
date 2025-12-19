# Introducci-naML
Sprint09

Descripción del proyecto<br>
La compañía móvil Megaline no está satisfecha al ver que muchos de sus clientes utilizan planes heredados. Quieren desarrollar un modelo que pueda analizar el comportamiento de los clientes y recomendar uno de los nuevos planes de Megaline: Smart o Ultra.<br>

Tienes acceso a los datos de comportamiento de los suscriptores que ya se han cambiado a los planes nuevos (del proyecto del sprint de Análisis estadístico de datos). Para esta tarea de clasificación debes crear un modelo que escoja el plan correcto. Como ya hiciste el paso de procesar los datos, puedes lanzarte directo a crear el modelo.<br>

Desarrolla un modelo con la mayor exactitud posible. En este proyecto, el umbral de exactitud es 0.75. Usa el dataset para comprobar la exactitud.<br>

Instrucciones del proyecto.<br>
Abre y examina el archivo de datos. Dirección al archivo:/datasets/users_behavior.csv Descarga el dataset<br>
Segmenta los datos fuente en un conjunto de entrenamiento, uno de validación y uno de prueba.<br>
Investiga la calidad de diferentes modelos cambiando los hiperparámetros. Describe brevemente los hallazgos del estudio.<br>
Comprueba la calidad del modelo usando el conjunto de prueba.<br>
Tarea adicional: haz una prueba de cordura al modelo. Estos datos son más complejos que los que habías usado antes así que no será una tarea fácil. Más adelante lo veremos con más detalle.<br>
Descripción de datos<br>
Cada observación en el dataset contiene información del comportamiento mensual sobre un usuario. La información dada es la siguiente:<br>
сalls — número de llamadas, <br>
minutes — duración total de la llamada en minutos, <br>
messages — número de mensajes de texto, <br>
mb_used — Tráfico de Internet utilizado en MB, <br>
is_ultra — plan para el mes actual (Ultra - 1, Smart - 0).
