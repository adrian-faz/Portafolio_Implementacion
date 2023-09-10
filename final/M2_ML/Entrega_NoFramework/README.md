# Actividad: Implementación de una técnica de aprendizaje máquina sin el uso de un framework

En esta actividad, se implementa una técnica de aprendizaje de máquina de manera manual, sin el uso de ningún framework o biblioteca de aprendizaje máquina. 
Esta carpeta contiene los archivos solicitados para completar la actividad, está compuesta por:
* **Actividad_NoFramework.ipynb**: Notebook donde se encuentra la implementación manual del modelo y el código en general de la actividad, al igual que las explicaciones pertinentes.
* **plants_sunlight_data.csv**: Archivo donde se encuentran los datos del set de datos utilizado en la actividad en formato csv.

## Set de Datos 

El set de datos utilizado se llama "plants_sunlight_data", y este incluye 100 muestras de plantas, y el set de datos refleja la cantidad de horas promedio al día que estaba expuesta la planta al sol y una columna que indica si la planta sobrevivió después de un mes o no. Los nombres de las columnas del set de datos son los siguientes:

* Hours_of_sunlight
* Survived

Con este set de datos, se busca entrenar un modelo de manera manual que sea capaz de predecir si una planta sobrevivirá después de un mes, en base a la cantidad de horas promedio que está expuesta al sol. 

Este set de datos se puede encontrar en: https://github.com/adrian-faz/Portafolio_Implementacion/blob/main/final/M2_ML/Entrega_NoFramework/plants_sunlight_data.csv

## Problema

El problema presentado en este caso es de **clasificación**, pues se busca generar un modelo que sea capaz de clasificar cada registro en solamente 2 posibles salidas, es decir, si la planta sobrevivirá o no. Se trata de una salida categórica (Sí o No), y no una salida continua.

El modelo a utilizar fue la **Regresión Logística**, el cual es un algoritmo de aprendizaje supervisado que estima la probabilidad de que una instancia pertenezca a una categoría particular. Se utiliza la función logística o sigmoide, la cual transforma su salida para caer entre 0 y 1, y esto permite representarla como una probabilidad. La regresión logística utiliza variables predictoras para calcular ponderaciones que maximizan la verosimilitud de clasificar correctamente las observaciones. Normalmente se usa 0.5 como el umbral, si la probabilidad modelada es superior a este valor, la instancia se clasifica en la categoría 1, y si es inferior, en la categoría 0.

## Subcompetencias y archivos a revisar

Las competencias involucradas e indicadores a evaluar en esta entrega son las siguientes:

1. **SMA0401A**
   * Indicadores:
      * Implementa una técnica o algoritmo de aprendizaje máquina, sin uso de marco de trabajo o framework como regresiones, árboles, clusters, etc...
       
   * Archivo donde se evalúa:
      * Actividad_NoFramework.ipynb



## Cambios implementados

A continuación se enlistan los puntos que no recibieron marcas en la rúbrica de retroalimentación y lo que se hizo para resolverlo:

1. "**El repositorio de Github incluye un archivo Readme**":
    * Se agregó un archivo Readme al repositorio de la entrega. En este archivo se encuentra la descripción de la actividad, los datos utilizados, el problema, y la información requerida en la rúbrica de la actividad.
2. **"El readme incluye una descripción del modelo de ML implementado"**
    * En el readme, se incluyó la sección "Problema", en donde se explica el modelo que se utilizó en la actividad (Regresión Logística). En esa parte, se da una pequeña descripción de cómo funciona el modelo y en qué casos se usa.
3. **El readme incluye una descripción del dataset utilizado (nombre y URL donde se encuentra)**
    * En el readme, en la sección de "Set de Datos", se incluyó una breve descripción del set de datos que se utilizó, incluyendo datos como la cantidad de muestras, posibles salidas, y una liga que redirije al set de datos utilizado.
4. **El readme contiene una descripción breve de la estructura del repositorio (qué es cada archivo/carpeta)**
    * Al inicio del readme, se agregó la estructura de esta parte del repositorio, en donde se incluyen los archivos que lo componen y la explicación de qué es cada archivo.
5. **El readme indica cuáles son los archivos que deberán revisarse para evaluar los indicadores de las subcompetencias**
    * Se agregó la sección de "Subcompetencias y archivos a revisar", en donde se especifica el/los archivos a revisar para evaluar los indicadores de la subcompetencia(s) involucrada en la actividad. 


