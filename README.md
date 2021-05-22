# Comparativa de modelos predictivos para identificación de sentimientos
El análisis de sentimientos es una técnica que permite detectar el sentimiento subyacente de un fragmento de texto. Los sentimientos se suelen clasificar como: neutros, positivos y negativos. Existen diferentes maneras de analizar el texto para poder identificar el proposito o sentimiento del texto.

## ¿Qué archivos conforman el conjunto de datos?
train.csv: Conjunto de datos de entrenamiento
test.csv: Conjunto de datos de prueba
Columnas del conjunto de datos
textID: Identificador único por tweet
text: Texto del tweet
sentiment: Sentimiento del tweet
selected_text: Solo entrenamiento Texto que soporta el sentimiento
Cada fila contiene el texto de un tweet y una etiqueta de opinión. En el conjunto de entrenamiento, se le proporciona una palabra o frase extraída del tweet (selected_text) que encapsula el sentimiento proporcionado.

## Ambiente
El conjunto de datos elegido para este proyecto esta conformado por un conjunto de tweets, el sentimiento que expresa y aquellas palabras que soportan el sentimiento.

Los tweets fueron obtenidos de la plataforma "Data for Everyone" de Figure Eight. El conjunto de datos se titula Análisis de sentimiento: tweets de emoción en texto con etiquetas de sentimiento existentes. El conjunto de datos se encuentra licenciado como creative commons 4.0, licencia internacional.

La implementación práctica de la monografía usa Python como lenguaje de programación. Y para las arquitecturas de Deep Leraning, manipular, limpiar y procesar los datos se usan las siguientes librerias:

    - Numpy: Es el paquete fundamental para la computación científica en Python.
    - Pandas: Herramienta OpenSource para análisis y manipulación de datos.
    - matplotlib: Librería para crear visualizaciones estáticas, animadas e interactivas en Python.
    - seaborn: Librería para crear visualizaciones basada en Matplotlib.
    - plotly: Librería para crear visualizaciones que facilita la manipulación de nubes de palabras.
    - nltk: Librería de lenguage natural en Python
    - tensorflow: Es un \textit{framework} de código abierto para el aprendizaje automático y cálculos sobre datos descentralizados.
    - Keras: Es una API diseñada para seres humanos, no para máquinas. Keras sigue las mejores prácticas para reducir la carga cognitiva.

## Enlaces del proyecto

- **Datos:** https://www.kaggle.com/c/tweet-sentiment-extraction/data
- **Introducción:** https://www.kaggle.com/nietzs96/fork-of-monograf-a-introducci-n
- **Implementación Bag Of Words:** https://www.kaggle.com/nietzs96/monograf-a-bag-of-words
- **Implementación de red convolucional + Glove:** https://www.kaggle.com/nietzs96/glove-convolutional
- **Implementación de red convolucional + Fast Text:** https://www.kaggle.com/nietzs96/fasttext-convolutional
- **Implementación de biLSTM + Glove:** https://www.kaggle.com/nietzs96/glove-bilstm
- **Implementación de biLSTM + Fast Text:** https://www.kaggle.com/nietzs96/fasttext-bilstm
- **Implementación DistilBert:** https://www.kaggle.com/nietzs96/monograf-a-distilbert
- **Implementación RoBERTa:** https://www.kaggle.com/nietzs96/monograf-a-roberta

## Como ejecutar los notebooks

1. Ir al link de Kaggle de la implementación deseada.
2. Click en el botón Copy and Edit.
3. Ejecutar en modo GPU.
4. Listo.

