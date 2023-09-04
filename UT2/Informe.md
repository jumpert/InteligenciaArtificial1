# Unidad Temática 2 - Preparación de datos y fundamentos de ML

## Objetivos

En esta unidad de aprendizaje pretendemos:

* Realzar la importancia del conocimiento de la naturaleza del problema abordado y los datos relativos al mismo, para entonces analizar las diversas herramientas disponibles para el tratamiento inicial de los datos.
* Revisar los fundamentos generales de los algoritmos de Aprendizaje Automático, e
* Introducir las técnicas habitualmente utilizadas para la prueba y validación de modelos de ML

## Materiales y recursos

* ["Mastering Machine Learning Algorithms"](../../Bibliografia/Mastering%20Machine%20Learning%20Algorithms.pdf), de Giuseppe Bonaccorso, publicado por Packt Publishing Ltd. en 2017. Capítulos del 3 al 7.
* ["Data Mining for the masses"](../../DataMiningForTheMasses.pdf), de Matthew North, publicado por CreateSpace Independent Publishing Platform en 2012. Capítulo 3 "Data Preparation for Data Mining".
* ["Applied Predictive Modelling"](../../Bibliografia/applied%20predictive%20modelling.pdf), de Max Kuhn y Kjell Johnson, publicado por Springer en 2013. Capítulo 3 "Data Pre-Processing".
* Tutoriales de RapidMiner: "Data Handling", "Handling Missing Values" y "Normalization and Outlier Detection".

## Actividades de aprendizaje

### 1. Preparación de datos

La preparación de datos es una de las tareas más importantes en el proceso de minería de datos. En esta actividad se pretende que el alumno se familiarice con las tareas más habituales en la preparación de datos, y con las herramientas disponibles para ello.

#### 1.1. Análisis de datos

En primer lugar, se pretende familiarice con los datos que vamos a utilizar en el resto de actividades de esta unidad. Para ello, se le proporciona un conjunto de datos de ejemplo, que deberemos analizar y describir. Para ello, deberemos responder a las siguientes preguntas:

* ¿Cuántos atributos tiene el conjunto de datos?
* ¿Cuántos ejemplos tiene el conjunto de datos?
* ¿Cuántos ejemplos hay de cada clase?
* ¿Cuántos valores distintos hay para cada atributo?
* ¿Cuántos valores perdidos hay para cada atributo?
* ¿Qué atributos son numéricos y cuáles categóricos?

#### 1.2. Limpieza de datos

En esta actividad, debemos de realizar tareas para verificar los datos, de que todos los valores son correctos y que no hay valores perdidos. Para ello, debemos de realizar las siguientes tareas:

* Evaluar si hay valores perdidos en el conjunto de datos.
* Evaluar si esos valores perdidos que se pueden imputar o es necesario eliminarlos.
* Evaluar los tipos de datos de los atributos y si son correctos.
* Analizar si hay valores atípicos en el conjunto de datos.
* Evaluar si hay valores atípicos que se puedan eliminar o imputar.

#### 1.3. Transformación de datos

En esta actividad, debemos de realizar tareas para transformar los datos, de forma que se puedan utilizar en los algoritmos de aprendizaje automático. Para ello, debemos de realizar las siguientes tareas:

* Agrupar valores que contengan estrechas relaciones entre sí. Ej. del dataset utilizado (Titanic) se puede agrupar los atributos `SibSp` y `Parch` en un único atributo `FamilySize`.
* Eliminar atributos que no aporten información al problema. Ej. del dataset utilizado (Titanic) se puede eliminar el atributo `PassengerId`.
* Aplicar técnicas de normalización de datos. Ej. del dataset utilizado (Titanic) se puede normalizar el atributo `Age` para que tenga una distribución normal.
* Otra tarea puede ser el estandarizar los datos, es decir, que tengan media 0 y desviación típica 1.

### 2. Preparación de Modelos de Aprendizaje Automático

Una vez que hallamos preparado los datos, debemos de preparar los modelos de aprendizaje automático. Una opción particularmente atractiva es la utilización de gráficos que nos permitan visualizar el comportamiento de los datos.
Aquí debemos considerar también cual es el objetivo de nuestro modelo, si es un modelo de clasificación o de regresión. En el caso de que sea un modelo de clasificación, debemos de considerar si es un problema de clasificación binaria o multiclase. En el caso de que sea un modelo de regresión, debemos de considerar si es un problema de regresión lineal o no lineal. En función de esto, debemos de elegir el modelo de aprendizaje automático que mejor se adapte a nuestro problema.

### 3. Validación de Modelos de Aprendizaje Automático

Una vez que hallamos preparado los modelos de aprendizaje automático, debemos de validarlos. Para ello, podríamos dividir el dataset en dos partes, una parte para entrenar el modelo y otra parte para validar el modelo. Sin embargo, esto no es lo más recomendable, ya que el modelo podría sobreajustarse a los datos de entrenamiento y no generalizar bien. Por ello, lo más recomendable es utilizar técnicas de validación cruzada, como por ejemplo la validación cruzada de k iteraciones.

Las técnicas de validación cruzada nos permiten evaluar el modelo de aprendizaje automático de forma más robusta, ya que se entrena y valida el modelo varias veces, y se calcula la media de los resultados obtenidos. Esto nos permite obtener una estimación más fiable del rendimiento del modelo.

## Muestra de ejercicios resueltos

Se proporcionan las evidencias de los casos de estudios utilizados en esta Unidad, los cuales comprenden los dataset de `wine` y `titanic`. 

El dataset de `wine` se encuentra en la carpeta [Ejercicios](./Ejercicios/wine) y el dataset de `titanic` se encuentra en la carpeta [Ejercicios](./Ejercicios/UT2-PD4). El dataset de wine es extraído de la página oficial de [UCI Machine Learning Repository](https://archive.ics.uci.edu/datasets), mientras que el dataset de titanic es extraído de la página oficial de [Kaggle](https://www.kaggle.com/c/titanic/data).

En ambas páginas se nos ofrece una descripción de los datos, así como también una descripción de los atributos que componen el dataset. Esto es de gran ayuda para poder realizar el análisis de los datos, así como también para poder realizar la limpieza y transformación de los datos. 

Para cada ejercicio realizado existe un informe en formato `pdf` y un archivo de extensión `.md` que contiene el código utilizado para realizar el ejercicio.

* :page_facing_up: [PD1 Ejercicio 1 - RapidMiner](./Ejercicios/UT2-PD1/UT2_PD1_Ej1.pdf) y [PD1 Ejercicio 2 - Wine](./Ejercicios/UT2-PD1/UT2_PD1_Ej2.pdf)
* :page_facing_up: [PD2 Ejercicio 1 - Procesamiento Previo](./Ejercicios/UT2-PD2/UT2-PD2-Ej1.pdf)
* :page_facing_up: [PD3 Ejericio - Dataset Wine en Python](./Ejercicios/UT2-PD3/UT2_PD3.html)
* :page_facing_up: [PD4 Ejercicio 1 - Dataset Titanic en Python](./Ejercicios/UT2-PD4/UT2_PD4-Ej1.pdf) y [PD4 Ejercicio 2 - Dataset Titanic Probabilidad](./Ejercicios/UT2-PD4/UT2_PD4-Ej2.pdf)


