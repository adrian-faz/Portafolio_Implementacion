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

Este set de datos se puede encontrar en: https://github.com/adrian-faz/EntregasIndividuales_AdrianFaz/tree/main/retro/M2_ML/Act2/iris.csv

## Problema

El problema presentado en este caso es de **clasificación**, pues se busca generar un modelo que sea capaz de clasificar en una de las 3 especies existentes en los datos, basandose en los otros datos, como lo son las longitudes y anchuras del sépalo y del pétalo. 

El modelo a utilizar fue el **Decision Tree Classifier**, el cual es un algoritmo de aprendizaje supervisado que descompone un problema complejo en subproblemas más simples, tomando decisiones basadas en las características de los datos. Este árbol se compone de nodos que representan condiciones, y ramas, que serían las posibles respuestas. Lo que se busca  es llegar a una "hoja" que contiene la clase a la que pertenece.

## Subcompetencias y archivos a revisar

Las competencias e indicadores a evaluar en esta entrega son las siguientes:

1. **SMA0401A**
   * Indicadores:
      * Usa un marco de trabajo o framework para implementar una técnica o algoritmo de aprendizaje máquina como: regresiones, árboles, clusters, etc...
       
   * Archivo donde se evalúa:
      * Desempeño_Modelo.ipynb



## Cambios implementados

A continuación se enlistan los puntos que no recibieron marcas en la rúbrica de retroalimentación y lo que se hizo para resolverlo:

1. "**El readme indica cuáles son los archivos que deberán revisarse para evaluar los indicadores de las subcompetencias**":
    * Se agregó una sección nueva en el readme con las subcompetencias a evaluar en esta actividad y los archivos en donde se pueden revisar.


