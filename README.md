# regresonlinealisimple
Predecir cuántas veces será compartido un artículo de Machine Learning.

En este ejemplo cargaremos un archivo .csv de entrada obtenido por webscraping que contiene diversas URLs a artículos sobre Machine Learning de algunos sitios muy importantes como Techcrunch o KDnuggets y como características de entrada -las columnas- tendremos:

Title: Titulo del Artículo
url: ruta al artículo
Word count: la cantidad de palabras del artículo,
# of Links: los enlaces externos que contiene,
# of comments: cantidad de comentarios,
# Images video: suma de imágenes (o videos),
Elapsed days: la cantidad de días transcurridos (al momento de crear el archivo)
# Shares: nuestra columna de salida que será la “cantidad de veces que se compartió el artículo”.

A partir de las características de un artículo de machine learning intentaremos predecir, cuantas veces será compartido en Redes Sociales.

Haremos una primer predicción de regresión lineal simple -con una sola variable predictora- para poder graficar en 2 dimensiones (ejes X e Y) y luego un ejemplo de regresión Lineal Múltiple, en la que utilizaremos 3 dimensiones (X,Y,Z) y predicciones.
