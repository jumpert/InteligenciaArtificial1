# Unidad Temática 1 - Introducción al Aprendizaje Automático

## Objetivos
Esta primera unidad del curso tiene como objetivo primario el presentar la temática del aprendizaje automático, proveyendo un marco de trabajo aplicado y con enfoque industrial

## Resultados Esperados del aprendizaje
Al culminar esta unidad de aprendizaje serás capaz de:
- Identificar técnicas y herramientas para el tratamiento del aprendizaje automático actualmente disponibles y populares en la industria, y discutir sus ventajas y desventajas
- Comprender, describir y aplicar un proceso estándar de Data Science / Machine Learning
- Discutir a grandes rasgos los tipos de algoritmos de ML existentes y sus  aplicaciones.
- Comenzar a construir tu portafolios de ML
- Localizar y utilizar conjuntos de datos públicos disponibles para la práctica de técnicas de ML
- Comenzar a utilizar una herramienta típica industrial de modelado y ejecución de ML
- Utilizar planillas electrónicas para análisis estadísticos básicos

## Tópicos:
- Técnicas y herramientas de alta demanda en la industria
- El proceso de Data Science / Machine Learning - Metodología de desarrollo CRISP-DM. 
- Tipos de algoritmos y sus aplicaciones 
- Portafolios de ML
- Conjuntos de datos para entrenamiento y aprendizaje de ML, características deseables, tipos de problemas a resolver (UCI)
- Revisión de herramientas modernas a ser utilizadas en el curso (Weka, RapidMiner, etc.) 
- Revisión de Conceptos básicos de estadística descriptiva y utilización de planillas electrónicas para tratamiento de datos 


# ¿Qués es el Machine Learning?

## Definición

> El Machine Learning (o aprendizaje automático) es una rama de la Inteligencia Artificial (IA) que se centra en el estudio y construcción de sistemas capaces de aprender de los datos, identificar patrones y tomar decisiones con mínima intervención humana.

## Diferencias entre Machine Learning e Inteligencia Artificial

![ML vs IA](https://miro.medium.com/v2/resize:fit:400:400/1*H9eMNh36H1gGJXNOxjaeBw.png)

| Característica | Machine Learning | Inteligencia Artificial |
|----------------|-----------------|------------------------|
| Definición     | Aprendizaje automático que permite a las computadoras mejorar su rendimiento en una tarea específica a través de la experiencia. | Simulación de procesos de inteligencia humana mediante máquinas, incluyendo resolución de problemas, toma de decisiones y reconocimiento de patrones. |
| Aplicaciones   | Clasificación de imágenes, predicción de ventas, recomendación de contenido. | Procesamiento de lenguaje natural, visión por computadora, robótica. |
| Enfoque        | Se centra en desarrollar algoritmos y modelos para aprender de datos. | Busca replicar la inteligencia humana en máquinas mediante diversos enfoques como el razonamiento lógico y las redes neuronales. |

## Machine Learning y Data Mining

La Machine Learning (ML) es el aprendizaje automático de los datos, mientras que el Data Mining (DM) es el proceso de descubrir conocimiento a partir de los datos.

## Otras definiciones

![Conceptos](https://github.com/jumpert/InteligenciaArtificial1/assets/88668277/8f3c54e1-6fb0-480a-9b3a-e59308c57ac6)

**AI:** La capacidad de una máquina para imitar el comportamiento inteligente humano.
**ML:** Un subconjunto de AI que utiliza algoritmos estadísticos para permitir que las computadoras aprendan de los datos.
**DL:** Un subconjunto de ML que utiliza redes neuronales para aprender de los datos.
**NPL:** Un subconjunto de AI que permite a las computadoras comprender el lenguaje humano.


# Plataformas y herramientas

1. **Microsoft Azure Machine Learning Studio:** Permite construir, entrenar e implementar modelos de AI.
2. **IBM Watson Studio:** Permite crear y entrenar modelos de ML y DL, y escalarlos mediante APIs.
3. **Google TensorFlow:** Contiene librerías de Software de código abierto para programacion de flujos de datos.
4. **Amazon Machine Learning:** Es un servicio administrado para crear modelos de aprendizaje automático y generar predicciones. Contiene gran variedad de herramientas a disposición de los usuarios.
5. **OpenNN:** Es una librería de código abierto para programación de redes neuronales.

> Recuperado de https://www.simplilearn.com/best-machine-learning-tools-article.


# Proceso de Data Science

Es un posible proceso sistemático para la resolución de problemas de Data Science. Definido por 5 pasos:
1. **Definición del problema:** Definir el problema a resolver, los objetivos y los requerimientos.
2. **Preparar los datos:** Es un proceso tedioso que incluye integrar los datos, que vienen dados de diferente formas o incluso sin el uso de un formato (ej. fechas DD/MM/AAAA - MM/DD/AAAA).
3. **Elegir los Algoritmos más apropiados:** La estadística es parte esencial del modelo. En base a su comportamiento se elige el algoritmo más apropiado para el problema. Poder definir la herramienta a utilizar es importante.
4. **Mejorar los resultados:** Tener la capacidad de poder mejorar los resultados del modelo es importante, obtener la mejor herramiebta y saber que datos arrojan y como estas funcionan. Así como tambien las técnicas de mejorar el performance del resultado.
5. **Presentar los resultados:** Es importante poder presentar los resultados de manera clara y concisa, para que el cliente pueda entender el resultado y tomar decisiones en base a ello.

![Proceso de Data Science](https://github.com/jumpert/InteligenciaArtificial1/assets/88668277/1166fd2c-a2e0-4352-a932-bc49c37f76c0)

## El proceso CRISP-DM

![El proceso CRISP-DM](https://github.com/jumpert/InteligenciaArtificial1/assets/88668277/cb2283d2-dac7-4e55-8ffb-25a71363288b)

### Comprensión del negocio

Entender y comprender el problema planteado y los datos obtenidos para trabajar (saber si son basura o no).

### Comprensión de Datos

Entender los datos que se tienen, que significan, que representan, que valores tienen, etc. (Estudio de casos extremos, valores fuera de rangos, entre otros)

### Preparación de datos

Preparar los datos para poder trabajar con ellos, limpiarlos, eliminar datos basura, etc. Ej. Escalas de datos, tipos, entre otros.

### Modelado

Crear el modelo de datos, se resume en la construcción de un algoritmo que permita resolver el problema planteado.

### Evaluación

Evaluar el modelo creado, ver si cumple con los requerimientos y objetivos planteados. Mediante el testeo y evaluaciones de performance del modelo.

### Despliegue

Desplegar el modelo, aplicado a una aplicación del cliente.

El realizar este proceso permite tener el conocimiento profundo y conocer las acciones a tomar. Ejemplos de esto son: Detección de fraudes, entre otros.

# Tipos de Algoritmos y sus aplicaciones

## Algoritmos de Aprendizaje Supervisado

Los algoritmos de aprendizaje supervisado son aquellos que aprenden de un conjunto de datos de entrenamiento etiquetados. Es decir, se les proporciona un conjunto de datos de entrada y un conjunto de datos de salida esperados, también conocidos como etiquetas, y el algoritmo aprende a asociar las entradas con las salidas. El objetivo es que el algoritmo aprenda de los datos de entrenamiento para que pueda generalizar y predecir los resultados de datos nuevos y no vistos previamente.

### Clasificación

Identificar a qué categoría pertenece una muestra.

### Regresión

Predecir un valor numérico (variable dependiente) a partir de variables independientes.

## Algoritmos de Aprendizaje No Supervisado

Los algoritmos de aprendizaje no supervisado son aquellos que aprenden de un conjunto de datos de entrenamiento no etiquetados. El objetivo es que el algoritmo aprenda de los datos de entrenamiento para que pueda generalizar y predecir los resultados de datos nuevos y no vistos previamente.

### Clustering

Permite agrupar datos en función de las características de sus atributos.

### Reducción de dimensión

Transforma datos buscando nuevas dimensiones que capturen la mayor variabilidad, reduciendo la complejidad y eliminando características redundantes.


