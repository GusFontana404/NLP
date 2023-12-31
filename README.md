# Trabajo Práctico I - NLP

Este repositorio contiene una notebook con el desarrollo del Trabajo Práctico I de la materia Procesamiento del Lenguaje Natural, se adjunta además el informe del mismo. 

Enunciado del TP I:

## Ejercicio 1:
Construir un dataset haciendo web scraping de páginas web de su elección.
- Definir 4 categorías de noticias/artículos.
- Para cada categoría, extraer los siguientes datos de 10 noticias diferentes:
  - url (sitio web donde se publicó el artículo) 
  - título (título del artículo)  
  - texto (contenido del artículo)
Recomendaciones: elegir blogs para evitar los límites de lectura para los medios que exigen suscripción. Investigue sobre el archivo robots.txt y téngalo en cuenta. Considere también espaciar las consultas para evitar saturar el sitio.
Utilizando los datos obtenidos construya el dataset en formato csv.

## Ejercicio 2:
Utilizando los datos de título y categoría del dataset del ejercicio anterior, entrenar un modelo de clasificación de noticias en categorías específicas.

## Ejercicio 3:
Para cada categoría, realizar las siguientes tareas:
- Procesar el texto mediante recursos de normalización y limpieza.
- Con el resultado anterior, realizar conteo de palabras y mostrar la importancia de las mismas mediante una nube de palabras.
Escribir un análisis general del resultado obtenido.

## Ejercicio 4:
Use los modelos de embedding propuestos sobre el final de la Unidad 2 para evaluar la similitud entre los títulos de las noticias de una de las categorías.
Reflexione sobre las limitaciones del modelo en base a los resultados obtenidos, en contraposición a los resultados que hubiera esperado obtener.

## Ejercicio 5:
Escriba un programa interactivo que, según la categoría seleccionada por el usuario, devuelva un resumen de las noticias incluidas en ella.
Justifique la elección del modelo usado para tal fin.

## Opcional: 
Investigar y programar un bot de Telegram que entregue un resumen de noticias del blog de su elección. Recomendamos el uso de pyTelegramBotAPI.




## Nota: 
Todas la librerías y dependencias necesarias para la ejecución del código se encuentran indexadas en el desarrollo de la notebook. 
