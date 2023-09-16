# Unidad Temática 3

## Trabajo de Aplicacion 1

## Materia: **Inteligencia Artificial 1** 

### Estudiante:

**Juan M. Pérez**

</br> 

---

</br>

# Ejercicio 1

Dadas los siguientes datos `x = {1, 3, 2, 4, 6, 5}` y `y = {1, 2, 3, 3, 2, 5}`, utilizar una planilla excel para realizar gráfico de puntos.

![TA1-rep-Datos](src/TA1-rep-Datos.png)

Crear un modelo de regresión lineal simple para predecir `y` a partir de `x`.

$y = \beta_0 + \beta_1 * x$

![TA1-rep-Regresion](src/TA1-rep-Regresion.png)

</br>

Utilizando la formula de la regresión lineal simple, calcular los coeficientes $\beta_0$ y $\beta_1$.

$\beta_1 = \frac{\sum_{i=1}^{n} (x_i - mean(x)) * (y_i - mean(y))}{\sum_{i=1}^{n} (x_i - mean(x))^2}$

$\beta_0 = mean(y) - \beta_1 * mean(x)$

$\beta_1 = 0.34285$ y $\beta_0 = 1.46667$

![TA1-rep-Regresion-Formula](src/TA1-rep-Regresion-Formula.png)

</br>

Hacer predicciones de `y` para los valores de `x = {0, 8}` con paso de 0,1.

![TA1-rep-Prediccion](src/TA1-rep-Prediccion.png)

![Alt text](src/TA1-tabla.png)

</br>

Estimación del Error de Predicción.

$RMSE = \sqrt{\frac{\sum_{i=1}^{n} (p_i - y_i)^2}{n}}$

El error medio cuadrático se calcula como la raíz cuadrada de la media de los errores al cuadrado. Esto nos da una idea de cuán cerca están los valores predichos de los valores reales.

A continuación se muestra graficamente la diferencia entre los valores reales y los predichos.

![TA1-rep-Error](src/TA1-rep-Error.png)

En este caso el RMSE es de 1,10122586815712.

</br>
Forma alternativa de calcular el valor de B1 utilizando el desvio estandar.
En la planilla de excel se puede utilizar la función `Pendiente` o realizando la operación en forma desarrollada de la siguiente manera:

$\beta_1 = corr(x;y) * \frac{desvest(y)}{desvest(x)}$

Si utilizamos la funcion `PEARSON` como se sugiere en el ejercicio el resultado seria: 0,469476477861571.
Utilizando la funcion Pendiente o el calculo desarrollado el resultado es: 0,342857142857143, que es igual al calculado inicialmente.

![TA1-comp-formulas](src/TA1-comp-formulas.png)

</br>
</br>

---

</br>

# Ejercicio 2