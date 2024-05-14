# DSD-Proyect

1). **Descripción del proyecto**

Richard Vásquez - Mateo Barona

Tema: Entrada y salida de ecuatorianos y extranjeros al Ecuador en el 2023

1. Introducción

El proyecto tiene como objetivo realizar un análisis cualitativo de los datos relacionados con las entradas y salidas internacionales de ecuatorianos y extranjeros en el año 2023, utilizando información proporcionada por el INEC (Instituto Nacional de Estadística y Censos) de Ecuador. Los datos provienen de diversas fuentes, como el Sistema de Migración Ecuatoriano, la Dirección General del Registro Civil, cedulas e identificaciones, la Policía Judicial y aerolíneas. Estos datos son fundamentales para comprender los patrones migratorios y su impacto en diversos aspectos socioeconómicos del país. A continuación, se proporcionará una explicación de cómo se trabajó con los datos, asi como una explicación de lo que esperaba hacer con la investigación.

2. Objetivo

El objetivo es comprender y analizar los patrones migratorios en Ecuador durante el año 2023, utilizando datos proporcionados por el INEC (Instituto Nacional de Estadística y Censos) y otras fuentes oficiales. Algunos objetivos específicos podrían incluir:

2.1. Identificar las tendencias de entrada y salida de ecuatorianos y extranjeros en el país durante el período especificado.

2.2. Analizar las características demográficas de los migrantes, como edad, género, nacionalidad, entre otros, para comprender mejor quiénes son los principales actores en los movimientos migratorios.

2.3. Evaluar la distribución geográfica de los flujos migratorios, identificando las provincias o regiones que son más atractivas para los migrantes y las que experimentan una mayor emigración.

2.4. Estudiar los motivos de la migración, como razones laborales, educativas, familiares o de otro tipo, para comprender las fuerzas impulsoras detrás de los movimientos migratorios.

2.5. Evaluar el impacto económico y social de la migración en Ecuador, incluyendo aspectos como el mercado laboral, la integración social, la diversidad cultural y otros aspectos relevantes.

2.6. Proporcionar información valiosa para la formulación de políticas públicas relacionadas con la migración, incluyendo medidas para gestionar los flujos migratorios, promover la integración de los migrantes y proteger sus derechos.

3. Metodología

Para llevar a cabo el análisis, se siguió una metodología detallada:

3.1. Reconocimiento de variables: Se identificaron las variables proporcionadas en el conjunto de datos junto con su significado, utilizando el diccionario proporcionado por el INEC.

3.2. Búsqueda de información: Se realizó una búsqueda de información que relacionara los datos numéricos con su significado dentro de las variables, para comprender mejor su contexto y aplicación.

3.3. Limpieza de datos: Se procedió a limpiar la base de datos, eliminando aquellas variables que no eran relevantes para el análisis planteado.

3.4. Esclarecimiento de dudas: Ante cualquier duda sobre los datos numéricos dentro de las variables, se consultó la fuente oficial para obtener una interpretación precisa.

3.5. Recopilación de códigos de Python: Se recopilaron y adaptaron códigos de Python que permitieran avanzar en el proceso de investigación y análisis de datos.

3.6. Resolución de preguntas de investigación: Se utilizó las habilidades adquiridas en cursos de programación e interpretación de datos para responder a las preguntas de investigación planteadas.

3.7. Presentación de resultados: Los resultados se presentaron utilizando tablas y gráficos descriptivos, que permitieron una mejor comprensión de los patrones y tendencias observadas en los datos.

4. Resultados

Explicación breve de lo que se pretendia con algunas de las combinación de variables:

Código 1: Creación de una nueva columna y cálculo de la suma de contadores por combinaciones de variables
Este código fue utilizado para generar una nueva columna que combina variables relacionadas con la provincia, tipo de movimiento, nacionalidad y motivo. Posteriormente, se agruparon los datos por esta nueva columna y se calculó la suma de los contadores, lo que nos proporciona información sobre la cantidad total de registros para cada combinación de variables.

Código 2: Ordenamiento y selección de los valores más altos y más bajos
En este código, se ordenaron los datos por la suma de contadores de forma ascendente y descendente, lo que nos permitió identificar los valores más altos y más bajos. Esto es útil para comprender las combinaciones de variables que tienen un mayor y menor impacto en la cantidad total de registros.

Código 3: Visualización de resultados utilizando gráficos de barras
Se utilizaron gráficos de barras para visualizar los resultados de los valores más altos y más bajos, lo que facilita la interpretación de los patrones y tendencias en los datos. Estos gráficos proporcionan una representación visual clara de las combinaciones de variables con la mayor y menor cantidad de registros.

Código 4: Análisis de la edad promedio por combinaciones de variables
Este código se utilizó para calcular la edad promedio de los registros agrupados por combinaciones de variables, lo que nos proporciona información sobre las características demográficas de las poblaciones involucradas en los movimientos migratorios.

Es clave recalcar que se podrían realizar múltiples combinaciones de variables con lo cual también se pudo obtener diversos resultados e interpretaciones.

Para concluir se menciona que, mediante el uso de códigos de Python y técnicas de análisis de datos, aprendidas en Coursera y demás, se pudo obtener una visión más detallada de los patrones migratorios en Ecuador en el año 2023, lo que nos permite comprender mejor su impacto en diversos aspectos socioeconómicos del país.

2). **Instrucciones sobre cómo instalar y ejecutar el código**

Para instalar las bibliotecas necesarias, puedes utilizar pip, el administrador de paquetes de Python. Asegúrate de tener Python y pip instalados en tu sistema. Luego, puedes ejecutar el siguiente comando en tu terminal o símbolo del sistema:

python
! pip install seaborn statsmodels matplotlib scikit-learn pandas


Esto instalará todas las bibliotecas necesarias: seaborn, statsmodels, matplotlib, scikit-learn y pandas.

Una vez que hayas instalado las bibliotecas, puedes ejecutar el código proporcionado en tu entorno de Python. Aquí hay instrucciones detalladas sobre cómo hacerlo:

1. Importar las bibliotecas necesarias:

python
import seaborn as sns
import statsmodels.api as sm
import matplotlib.pyplot as plt
import re
from sklearn.ensemble import IsolationForest
import numpy as np
import pandas as pd

2. Ejecutar el código:

A continuación, puedes copiar y pegar los códigos previamente generados en tu entorno de Python y ejecutarlos. Asegúrate de tener el conjunto de datos adecuado (en este caso, los datos del INEC de Ecuador) cargados en tu entorno de trabajo.

3. Visualizar los resultados:

Una vez que hayas ejecutado el código, podrás visualizar los resultados utilizando las funciones de visualización proporcionadas por las bibliotecas, como matplotlib y seaborn.

4. Interpretar los resultados:

Por último, interpreta los resultados obtenidos en base a la información proporcionada y los gráficos generados. Puedes utilizar técnicas estadísticas como modelos de regresión, análisis de varianza (ANOVA), o cualquier otro método de análisis adecuado para responder a las preguntas de investigación planteadas.

3). **Lista de dependencias o librerías necesarias**

La lista de dependencias o bibliotecas necesarias para ejecutar el código incluye:

1. **Seaborn**: Utilizada para crear visualizaciones estadísticas atractivas y informativas.
2. **Statsmodels**: Utilizada para realizar análisis estadísticos y modelado, incluyendo regresión, series temporales, y más.
3. **Matplotlib.pyplot**: Utilizada para crear gráficos y visualizaciones personalizadas en Python.
4. **Re (expresiones regulares)**: Utilizada para trabajar con patrones de texto, lo que puede ser útil para la manipulación de datos.
5. **Scikit-learn**: Utilizada para aplicar algoritmos de aprendizaje automático, incluyendo la detección de anomalías con el Isolation Forest.
6. **Numpy**: Proporciona soporte para matrices y operaciones matemáticas, es fundamental para la manipulación de datos numéricos en Python.
7. **Pandas**: Utilizada para la manipulación y análisis de datos estructurados, como los datos de un DataFrame.

Por lo tanto, para ejecutar el código correctamente, necesitarás tener instaladas estas bibliotecas en tu entorno de Python. Puedes instalarlas utilizando el administrador de paquetes pip de la siguiente manera:

python
! pip install seaborn statsmodels matplotlib scikit-learn numpy pandas

Recordar que no se necesita ingresar el código anterior en la terminal de PowerShell, si no basta con ingresarla en alguna linea del cuaderno de Jupyter

Una vez instaladas las bibliotecas, podrás ejecutar el código y realizar el análisis de datos como se describió previamente.
