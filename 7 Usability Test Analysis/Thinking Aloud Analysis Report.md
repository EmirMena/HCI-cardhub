# Resultado del análisis del proyecto

## 1. Detalle de las pruebas de usabilidad

Véase la carpeta "6 Usability Test"

## 2. Materiales Usados


Para llevar a cabo las pruebas de usabilidad utilizamos una serie de herramientas que nos apoyaron en su diseño, implementación y posterior análisis:
* **Microsoft Teams y Discord:** Se utilizaron como medio de comunicación en algunas pruebas que no pudieron ser presenciales.
* **Software de conversión de formatos de vídeo online:** Se utilizó para transformar los vídeos grabados a un formato específico para su transcripción
* **TurboScribe:** Herramienta para transcribir videos a texto gratuito
* **Librería TextBlob:** Se utilizó el lenguaje de programación Python junto con la librería Textblob para el análisis sentimental de las transcripciones obtenidas.

## 3. Evidencia

Se adjuntan abajo los videos de la implementación de las pruebas de usabilidad así como los resultados obtenidos:

https://drive.google.com/drive/folders/1OkzaCzeIN1vzc1iGuWBjYrg1jIgPjAm7?usp=sharing

## 4. Análisis de Datos

### 4.1 Análisis de las pruebas utilizando los checklists

Según el protocolo, una encuesta fue utilizada para ayudarnos a determinar si el usuario tendría algunas dificultades a la hora de probar el prototipo.
* En la primera tarea la cual era registrar una tarjeta, tenemos los 10 elementos marcados correctamente tal y como se esperaban
* En la segunda tarea la cual era editar los valores asociados a la tarjeta, las 3 pruebas pasan todos los checklists.

### 4.2 Analisis sentimental

Para analizar los datos de la prueba de usabilidad de Thinking Aloud decidimos utilizar el análisis de sentimientos porque, dada la cantidad de información recopilada en las entrevistas de Thinking Aloud, necesitamos una forma de obtener rápidamente una idea de la experiencia del entrevistado durante la prueba y el análisis de sentimientos es una herramienta que logra procesar grandes cantidades de datos en un corto período de tiempo.

El análisis de sentimientos es una forma de analizar los datos en función del valor positivo o negativo de las palabras utilizadas durante la entrevista. Esto nos permite saber si los usuarios entrevistados tenían palabras positivas o negativas al describir sus ideas sobre el prototipo. Más palabras negativas indicarían una experiencia peor, mientras que las positivas indicarían una experiencia más agradable.

### 4.2.1 Transcripciones

Las transcripciones fueron posibles gracias a TurboScribe, una herramienta que utiliza IA para transcribir videos y obtener todo su contenido en texto de manera gratuita y rápida.

### 4.2.1 Código Python

Para realizar el análisis de sentimientos, utilizamos la biblioteca TextBlob en Python, que nos permite analizar el contenido de texto de una manera sencilla. El código utilizado para realizar el análisis de sentimientos en cada archivo de transcripción se puede encontrar en el archivo "sentiment_analysis.py" en la presente carpeta.

El código recorre todos los archivos dentro de una carpeta que contiene las transcripciones y luego calculamos el sentimiento de la prueba de transcripción.

Los resultados se presentan como pares: nombre de archivo + valor de sentimiento.

El sentimiento es un número dentro de [-1, 1]. -1 representa palabras negativas, 1 representa palabras positivas y 0 representa palabras neutras. Cuanto más cerca esté el valor de sentimiento de 1, más positivas serán las palabras en la transcripción.

## 5. Resultados

### 5.1 Resultados Preliminares

La salida del análisis sentimental es el siguiente

![image](https://github.com/user-attachments/assets/2758044d-1ca7-4753-a434-854947a22ab0)

In text:

* Sentiment value for transcripcion_alexandra.txt: 0.3588235294117647
* Sentiment value for transcripcion_jean.txt: 0.35714285714285715
* Sentiment value for transcripcion_ruth.txt: 0.359375

## Explicación del gráfico del análisis sentimental

### Introducción

![output (8)](https://github.com/user-attachments/assets/76717cb8-b9a6-4d7e-9f85-ac7ccea98484)

Este gráfico de barras presenta los resultados de un análisis de sentimientos realizado en varios documentos. El análisis de sentimientos evalúa el contenido del texto para determinar la actitud expresada, que puede ser positiva, negativa o neutra. En este caso, todos los documentos analizados contienen sentimientos positivos.

### Eje X (Horizontal)

En el eje X del gráfico se enumeran los documentos analizados. Cada documento tiene un nombre único, por ejemplo, "transcripcion_alexandra.txt", "transcripcion_ruth.txt", etc. Estos nombres identifican individualmente a cada documento del conjunto de datos.

### Eje Y (Vertical)

El eje Y muestra las puntuaciones de sentimiento, que van de -1 a 1. Estas puntuaciones indican la intensidad del sentimiento detectado en cada documento:

-1: sentimiento completamente negativo (no presente en este análisis).
0: sentimiento neutral.
1: sentimiento completamente positivo.

## Análisis de los resultados

**Documentos con el sentimiento menos positivo**
El documento con el sentimiento menos positivo es "transcripcion_jean.txt" con un aproximado de 0.357 con una diferencia muy ligera entre los otros superiores

**Documentos con el sentimiento moderadamente positivo**

El documento con el sentimiento menos positivo es "transcripcion_alexandra.txt" con un aproximado de 0.358 con una diferencia muy ligera entre el otro superior y el anterior

**Documentos con el sentimiento muy positivo**

El documento con el sentimiento menos positivo es "transcripcion_ruth.txt" con un aproximado de 0.360 igual, con una diferencia muy ligera entre sus anteriores.

## Conclusión

Este gráfico es útil para visualizar cómo varía el sentimiento positivo entre distintos documentos. Al ordenar los documentos desde el sentimiento menos positivo hasta el más positivo, es fácil identificar rápidamente cuáles tienen los tonos menos positivos y los más positivos, lo que facilita el análisis comparativo de los sentimientos expresados ​​en cada documento.

### 5.2 ¿Son estos datos significantes?

### 5.2.1 Proesos de otras fuentes

**Ontology-Guided Feature-Based Opinion Mining**

### Comparación

La forma en que realizamos el análisis de sentimientos de las transcripciones en las pruebas de usabilidad ni siquiera es similar a lo que se hace en los procesos antes mencionados, ya que no realizamos limpieza de datos, formato ni definición de palabras clave. Simplemente ingresamos las transcripciones en el código Python para obtener resultados.

### Conclusión final

Hecho esto, nos damos cuenta de que el proceso de análisis de sentimiento no se ha aplicado correctamente, empezando por el tamaño de la muestra (3 personas), que no es una muestra representativa. Además, aunque utilizamos un modelo preentrenado (TextBlob) para el análisis de sentimiento, al transcribir vía TurboScribe, las transcripciones no se corrigieron y se introdujeron directamente en el código Python para su análisis, lo que, sin considerar otras variables como el idioma, la limpieza de oraciones, la separación de palabras clave, etc., sesga en gran medida los resultados finales. Por lo tanto, concluimos que los resultados obtenidos de nuestras muestras, utilizando el análisis de sentimiento para procesarlos, no son significativos para realizar ninguna afirmación o inferencia. Sin embargo, esto no significa que nuestras pruebas de usabilidad sean incorrectas, sino que el método de análisis de los resultados no es adecuado para su uso en nuestro contexto.
