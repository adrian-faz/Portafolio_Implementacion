# Actividad: Uso de framework o biblioteca de aprendizaje máquina para la implementación de una solución.

En esta actividad, se utiliza el framework de scikit-learn para implementar una solución utilizando uno de los modelos vistos en clase. 
Esta carpeta contiene los archivos solicitados para completar la actividad, está compuesta por:
* **Desempeño_Modelo.ipynb**: Notebook donde se encuentra el código realizado y la implementación del modelo, además de las explicaciones pertinentes.
* **iris.csv**: Archivo donde se encuentran los datos del set de datos utilizado en la actividad en formato csv.

## Set de Datos 

El set de datos utilizado se llama "iris.csv", y este incluye 150 muestras de flores, las cuales están clasificadas en 3 clases distintas. Cada muestra tiene las siguientes características:

* sepal_length
* sepal_width
* petal_length
* petal_width
* species

En donde, buscamos predecir la especie a la que pertenece cada muestra en base a las otras características que tenemos como "datos de entrada".

El set de datos se puede encontrar en: https://github.com/adrian-faz/EntregasIndividuales_AdrianFaz/tree/main/retro/M2_ML/Act2/iris.csv

## Problema

El problema presentado en este caso es de **clasificación**, pues se busca generar un modelo que sea capaz de clasificar en una de las 3 especies existentes en los datos, basandose en los otros datos, como lo son las longitudes y anchuras del sépalo y del pétalo. 

El modelo a utilizar fue el **Decision Tree Classifier**, el cual es un algoritmo de aprendizaje supervisado que descompone un problema complejo en subproblemas más simples, tomando decisiones basadas en las características de los datos. Este árbol se compone de nodos que representan condiciones, y ramas, que serían las posibles respuestas. Lo que se busca  es llegar a una "hoja" que contiene la clase a la que pertenece.

## Subcompetencias y archivos a revisar

Las competencias a evaluar en esta entrega son las siguientes:

**SMA0401A**
Usa un marco de trabajo o framework para implementar una técnica o algoritmo de aprendizaje máquina como: regresiones, árboles, clusters, etc...



## Cambios implementados

A continuación se enlistan los puntos que no recibieron marcas en la rúbrica de retroalimentación y lo que se hizo para resolverlo:

1. "**El readme indica cuáles son los archivos que deberán revisarse para evaluar los indicadores de las subcompetencias**":
    * Se agregó una sección nueva en el readme con las subcompetencias a evaluar en esta actividad y los archivos en donde se pueden revisar.

