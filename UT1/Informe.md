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

</br>
<a href="https://www.youtube.com/watch?v=cHB24HIHuSs">
  <img src="https://github.com/jumpert/InteligenciaArtificial1/assets/88668277/a829a37a-45c5-4998-8329-a945e78b46ce" alt="Texto alternativo">
</a>




# ¿Qués es el Machine Learning?

## Definición

> El Machine Learning (o aprendizaje automático) es una rama de la Inteligencia Artificial (IA) que se centra en el estudio y construcción de sistemas capaces de aprender de los datos, identificar patrones y tomar decisiones con mínima intervención humana.

### Definición 1: 
“El aprendizaje automático es una rama de  la inteligencia artificial (IA)  y la informática que se centra en el uso de datos y algoritmos para imitar la forma en que los humanos aprenden, mejorando gradualmente su precisión.” 
> Recuperado de IBM https://www.ibm.com/topics/machine-learning, 15 de agosto 2023.
### Definición 2: 
“El aprendizaje automático es un subcampo de la inteligencia artificial, que se define ampliamente como la capacidad de una máquina para imitar el comportamiento humano inteligente. Los sistemas de inteligencia artificial se utilizan para realizar tareas complejas de una manera similar a la forma en que los humanos resuelven problemas.”
> Recuperado de Sloan de MIT https://mitsloan.mit.edu/ideas-made-to-matter/machine-learning-explained, 16 de agosto de 2023.
### Definición 3: 
“El aprendizaje automático permite que una máquina aprenda automáticamente de los datos, mejore el rendimiento de las experiencias y prediga cosas sin estar programada explícitamente.” 
> Recuperado de Java T point https://www.javatpoint.com/machine-learning, 16 de agosto de 2023.

## Diferencias entre Machine Learning e Inteligencia Artificial

![ML vs IA](https://miro.medium.com/v2/resize:fit:400:400/1*H9eMNh36H1gGJXNOxjaeBw.png)

| Característica | Machine Learning | Inteligencia Artificial |
|----------------|-----------------|------------------------|
| Definición     | Aprendizaje automático que permite a las computadoras mejorar su rendimiento en una tarea específica a través de la experiencia. | Simulación de procesos de inteligencia humana mediante máquinas, incluyendo resolución de problemas, toma de decisiones y reconocimiento de patrones. |
| Aplicaciones   | Clasificación de imágenes, predicción de ventas, recomendación de contenido. | Procesamiento de lenguaje natural, visión por computadora, robótica. |
| Enfoque        | Se centra en desarrollar algoritmos y modelos para aprender de datos. | Busca replicar la inteligencia humana en máquinas mediante diversos enfoques como el razonamiento lógico y las redes neuronales. |

* Como se compara el Aprendizaje Automático de la “Inteligencia Artificial”, básicamente la Inteligencia artificial es dotar a la maquina con la capacidad de pensar de forma similar a como lo realizan los seres humanos, pero a su vez la fuerte relación que tiene con la ML es que esta última es parte de la IA.

A su vez ambas emplean la automatización de tareas y procesos que normalmente requerirían la intervención humana.

La diferencia más elocuente es que la IA es como se mencionaba anteriormente dotar a la maquina con la capacidad de pensamiento, mientras que la ML esta centrado en el desarrollo de algoritmos y técnicas que permiten a las maquinas aprender patrones de datos sin ser estos programados implícitamente.

* Tanto el Machine Learning como el Estudio Estadístico, son formas de obtener información a través de datos, esta es la principal relación que hay entre ambos.

Como se mencionaba anteriormente ambos utilizan datos, los cuales son requeridos como entradas para poder ser procesados y generar resultados, para esto los datos deben ser coherentes y con la mínima cantidad de errores posible (el tener datos acertados favorece al resultado final).

Como diferencias entre ambos tenemos que, el aprendizaje automático se enfoca en la capacidad de las máquinas para aprender patrones y tomar decisiones sin intervención humana directa. El Análisis Estadístico, por otro lado, se centra en inferir propiedades y relaciones dentro de los datos mediante métodos estadísticos.

Otra diferencia es que el Machine Learning utiliza algoritmos y modelos matemáticos para entrenar máquinas y generar predicciones basadas en patrones pasados. El Análisis Estadístico se basa en técnicas estadísticas para comprender las propiedades y relaciones de los datos.
## Machine Learning y Data Mining

La Machine Learning (ML) es el aprendizaje automático de los datos, mientras que el Data Mining (DM) es el proceso de descubrir conocimiento a partir de los datos.

* Si bien comúnmente se tiene el concepto de que ML es igual a data mining, ese concepto esta un poco errado, porque si bien su punto objetivo es similar la forma en que cada uno lo realiza es distinto. El Data Mining se enfoca en encontrar patrones interesantes y significativos que puedan ayudar a tomar decisiones informadas, mientras que el Machine Learning utiliza esos patrones para hacer predicciones futuras y tomar acciones automatizadas.

Otra cosa en la que se establece una diferencia es que si bien ambos enfoques dependen de técnicas estadísticas para analizar datos. Mientras que el Data Mining se basa en métodos estadísticos para identificar patrones y relaciones, el Machine Learning utiliza algoritmos estadísticos para entrenar modelos que puedan realizar tareas específicas, como clasificación o regresión.

* El machine learning tiene diferentes aplicaciones según su rama de implementación, actualmente comprende un sinfín de aplicaciones a tareas cotidianas e incluso en tareas con una mayor complejidad. Dentro de estas ramas tenemos la Salud, la Energía, el Procesamiento de Lenguaje Natural (PLN), entre otras tantas.

En cada una de estas se utilizan diferentes enfoques metodológicos de procesamiento que son acordes a las diferentes situaciones, problemas y datos. Al ser esta una herramienta que nos ayuda a facilitar muchas tareas y debe realizarlo con la mayor optimización existen diferentes algoritmos que lo hacen posible.

## Otras definiciones

![Conceptos](https://github.com/jumpert/InteligenciaArtificial1/assets/88668277/8f3c54e1-6fb0-480a-9b3a-e59308c57ac6)

**AI:** La capacidad de una máquina para imitar el comportamiento inteligente humano.

**ML:** Un subconjunto de AI que utiliza algoritmos estadísticos para permitir que las computadoras aprendan de los datos.

**DL:** Un subconjunto de ML que utiliza redes neuronales para aprender de los datos.

**NPL:** Un subconjunto de AI que permite a las computadoras comprender el lenguaje humano.

</br>

# Plataformas y herramientas

1. **Microsoft Azure Machine Learning Studio:** Permite construir, entrenar e implementar modelos de AI.
2. **IBM Watson Studio:** Permite crear y entrenar modelos de ML y DL, y escalarlos mediante APIs.
3. **Google TensorFlow:** Contiene librerías de Software de código abierto para programacion de flujos de datos.
4. **Amazon Machine Learning:** Es un servicio administrado para crear modelos de aprendizaje automático y generar predicciones. Contiene gran variedad de herramientas a disposición de los usuarios.
5. **OpenNN:** Es una librería de código abierto para programación de redes neuronales.

> Recuperado de https://www.simplilearn.com/best-machine-learning-tools-article.

![Cuadro de herramientas y plataformas](https://github.com/jumpert/InteligenciaArtificial1/assets/88668277/9383368e-e419-4d45-a223-7a0434e859b8)

</br>

# Proceso de Data Science

Es un posible proceso sistemático para la resolución de problemas de Data Science. Definido por 5 pasos:
1. **Definición del problema:** Definir el problema a resolver, los objetivos y los requerimientos.
2. **Preparar los datos:** Es un proceso tedioso que incluye integrar los datos, que vienen dados de diferente formas o incluso sin el uso de un formato (ej. fechas DD/MM/AAAA - MM/DD/AAAA).
3. **Elegir los Algoritmos más apropiados:** La estadística es parte esencial del modelo. En base a su comportamiento se elige el algoritmo más apropiado para el problema. Poder definir la herramienta a utilizar es importante.
4. **Mejorar los resultados:** Tener la capacidad de poder mejorar los resultados del modelo es importante, obtener la mejor herramiebta y saber que datos arrojan y como estas funcionan. Así como tambien las técnicas de mejorar el performance del resultado.
5. **Presentar los resultados:** Es importante poder presentar los resultados de manera clara y concisa, para que el cliente pueda entender el resultado y tomar decisiones en base a ello.

![Proceso de Data Science](https://github.com/jumpert/InteligenciaArtificial1/assets/88668277/1166fd2c-a2e0-4352-a932-bc49c37f76c0)

## El proceso CRISP-DM

<img src="https://github.com/jumpert/InteligenciaArtificial1/assets/88668277/cb2283d2-dac7-4e55-8ffb-25a71363288b" alt="Proceso de Data Science" width="600" height="600" />

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

</br>

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



