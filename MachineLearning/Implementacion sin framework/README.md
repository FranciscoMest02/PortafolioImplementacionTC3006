# **Momento de Retroalimentación: Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework. (Portafolio Implementación)**

En esta carpeta se incluye el jupyter notebook donde se implementa un algoritmo de aprendizaje máquina desde cero, sin utilizar un framework. El modelo utilizado es una **Regresión Lineal** ya que se plantea un problema de regresión. Este modelo recibe variables cuantitavivas y optimiza la funcion para ajustarse a los datos.

El dataset utilizado es el de **wine**, el cual se encuentra en la siguiente carpeta y link:
*  /data
*  https://github.com/FranciscoMest02/PortafolioImplementacionTC3006/tree/main/MachineLearning/Implementacion%20sin%20framework/data

## Estructura del repositorio
* Aprendizaje_maquina_sin_frameworks_corregido.ipynb: En este archivo se encuentra la implementación del Decision Tree Clasifier.
* /data: En esta carpeta se encuentra el set de datos, en el archivo de wine.data

## Archivos para revisión
A continuación se presentan los archivos que están listos para ser retroalimentados: 

* **Momento de Retroalimentación: Módulo 2 Uso de framework o biblioteca de aprendizaje máquina para la implementación de una solución. (Portafolio Implementación)** Please review file **retro/M2_ML/Momento%20de%20retroalimentacion%202%3A%20Framework/Aprendizaje_maquina_con_framework.ipynb** o en: https://github.com/FranciscoMest02/PortafolioImplementacionTC3006/blob/main/MachineLearning/Implementacion%20sin%20framework/Aprendizaje_maquina_sin_frameworks_corregido.ipynb

## Correciones
A continuación se listan los puntos de la rúbrica que no cumplian en la entrega de retroalimentación y se indica en donde se puede encontrar la correción

* *El modelo se entrena sobre un subset de entrenamiento de un dataset*: En el reporte, en la sección de implementación de la regresión lineal se hace una separación de los datos de entrenamiento y testing (80% - 20%).
* *El readme incluye una descripción del modelo de ML implementado*: En este mismo readme se incluye en la primera parte del texto
* *El readme incluye una descripción del dataset utilizado (nombre y URL donde se encuentra)*: Debajo de la descripción del modelo se agregó una descripción general del dataset que se usará.
* *El readme contiene una descripción breve de la estructura del repositorio (qué es cada archivo/carpeta)*: Se agregó la sección de "Estructura del repositorio" en este readme
* *El readme contiene una sección de cambios implementados, donde se mencione el cambio indicado por el docente y lo que se hizo para resolverlo (solo aplica para entrega final)*: En la sección de "Correciones" se ponen las correciones sugeridas en el momento de retroalimentación.
* *El repositorio incluye un reporte (notebook o PDF)*: En esta carpeta se adjunta el reporte completo con las correciones.
* *El reporte incluye el nombre del dataset utilizado*: En el reporte, en la sección de "Introducción" se incluye el dataset utilizado
* *El reporte incluye un enlace al lugar donde se puede encontrar el dataset utilizado*: En el reporte, en la sección de "Introducción" se incluye un link a los archivos del dataset
* *El reporte incluye una descripción breve de los datos incluidos en el dataset (cantidad de registros/muestras, número de características, número de clases de salida o rango de valores de salida)*: En el reporte, en la sección de "Introducción" se incluye una descripción de los datos del dataset.
* *El reporte incluye una descripción del tipo de problema a resolver (regresión o clasificación)*: En el reporte, en la sección de "Introducción" se explica el modelo que se desarrollará y se da una breve justificación.
* *El reporte incluye una descripción de las métricas de desempeño para el subconjunto de entrenamiento*: En el reporte, en la sección de "Pruebas" se muestran las metricas utilizadas (R Squared y MSE) y se hace un análisis de qué pueden significar los resultados de las métricas para el modelo (con los datos de entrenamiento).
* *El reporte incluye una descripción de las métricas de desempeño para el subconjunto de prueba*: En el reporte, en la sección de "Pruebas" se muestran las metricas utilizadas (R Squared y MSE) y se hace un análisis de qué pueden significar los resultados de las métricas para el modelo (con los datos de prueba).
* *El reporte incluye una comparación entre las predicciones generadas y los valores que debieron obtenerse*: En el reporte, en la sección de "Pruebas" se despliegan tablas con la comparación de los valores esperados y los valores obtenidos (para el set de datos de entrenamiento y de prueba)
* *El desempeño logrado por el modelo sobre el testing set es adecuado*: Se hizo la separación de los datos y se explican las metricas obtenidas para el modelo en training y en testing
