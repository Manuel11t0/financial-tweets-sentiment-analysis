# Financial Tweets Sentiment Analysis

Este proyecto realiza un análisis de procesamiento de texto y sentimientos usando un dataset de tweets financieros.

El objetivo principal es limpiar, procesar y analizar textos de Twitter relacionados con el mercado financiero, para identificar palabras frecuentes, patrones del corpus y la polaridad de los tweets.

## Descripción del proyecto

En este proyecto se trabaja con el dataset **Financial Tweets**.  
Se construye un corpus de textos a partir de tweets financieros y se aplican técnicas básicas de Procesamiento de Lenguaje Natural.

El análisis incluye limpieza de texto, tokenización, eliminación de stopwords, stemming, análisis de frecuencias, generación de WordCloud, análisis de sentimientos y visualización con t-SNE.

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- NLTK
- VADER Sentiment Analysis
- Scikit-learn
- Matplotlib
- WordCloud
- Google Colab

## Objetivos

- Cargar y explorar el dataset de tweets financieros.
- Construir un corpus de textos limpio.
- Eliminar ruido como enlaces, menciones, hashtags y símbolos bursátiles.
- Aplicar tokenización y remoción de stopwords.
- Usar stemming para reducir palabras a su raíz.
- Identificar las palabras más frecuentes.
- Generar una nube de palabras.
- Clasificar tweets como positivos, negativos o neutrales.
- Visualizar patrones de texto usando TF-IDF y t-SNE.
- Exportar los resultados procesados.

## Flujo del proyecto

1. Instalación e importación de librerías.
2. Carga manual de archivos CSV en Google Colab.
3. Lectura robusta de los datos.
4. Exploración inicial del dataset.
5. Detección automática de la columna de texto.
6. Construcción del corpus.
7. Limpieza básica del texto.
8. Cálculo de longitud de tweets.
9. Extensión del vector de stopwords.
10. Tokenización, eliminación de stopwords y stemming.
11. Análisis de palabras más comunes.
12. Creación de WordCloud.
13. Análisis de sentimientos con VADER.
14. Análisis complementario por fuente.
15. Visualización con t-SNE.
16. Exportación de resultados finales.

## Análisis de sentimientos

Para el análisis de sentimientos se utiliza **VADER**, una herramienta de NLTK útil para textos cortos como tweets.

Cada tweet recibe un puntaje `compound`, y con base en ese valor se clasifica como:

- Positivo
- Neutral
- Negativo

## Archivos generados

El proyecto exporta los siguientes archivos:

```text
corpus_financial_tweets_procesado.csv
frecuencias_palabras_financial_top100.csv
