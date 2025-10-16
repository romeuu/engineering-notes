Tema: [[Ecuaciones]]

- [[#Sistemas lineales de dos ecuaciones y dos incógnitas|Sistemas lineales de dos ecuaciones y dos incógnitas]]
	- [[#Sistemas lineales de dos ecuaciones y dos incógnitas#Soluciones|Soluciones]]
		- [[#Soluciones#Sistema con una única solución:|Sistema con una única solución:]]
		- [[#Soluciones#Sistemas con infinitas soluciones|Sistemas con infinitas soluciones]]
		- [[#Soluciones#Sistemas sin soluciones|Sistemas sin soluciones]]
	- [[#Sistemas lineales de dos ecuaciones y dos incógnitas#Métodos de resolución|Métodos de resolución]]
		- [[#Métodos de resolución#Sustitución|Sustitución]]
		- [[#Métodos de resolución#Igualación|Igualación]]
		- [[#Métodos de resolución#Reducción|Reducción]]


## Sistemas lineales de dos ecuaciones y dos incógnitas

Un sistema de dos ecuaciones lineales con dos incógnitas es un conjunto de dos ecuaciones de primer grado con dos incógnitas cada una como máximo.

$$
\begin{cases}
4x - 3y = 5 \\
2x + 4y = 3
\end{cases}
$$

### Soluciones

Se pueden dar tres casos:

#### Sistema con una única solución:

$$
\begin{cases}
x + 2y = 10 \\
2x - y = 5
\end{cases}
$$
En este caso obtendremos lo siguiente:

(x,y) = (4, 3)

#### Sistemas con infinitas soluciones

$$
\begin{cases}
2x + 4y = 20 \\
x + 2y = 10
\end{cases}
$$
Que tendría soluciones como:

$$
(x,y) = (4, 3), (x,y) = (2,4), (x,y) = (0, 5)\dots
$$

#### Sistemas sin soluciones

$$
\begin{cases}
2x + y = 8 \\
2x + y = 1
\end{cases}
$$
En este caso podemos ver como las dos expresiones se contradicen, por lo tanto no se podría llegar a una solución.


### Métodos de resolución

#### Sustitución

Este método consiste en aislar las incógnitas en una de las dos ecuaciones y sustituir la expresión en la otra ecuación.

$$
\begin{cases}
2x - 3y = 7 \\
x + 4y = -2
\end{cases}
$$
En este caso, tendríamos que elegir una ecuación de las anteriores, por ejemplo, x + 4y = -2, ya que si hay una ecuación que tenga el coeficiente de x o y igual a 1, es más sencillo de calcular.

Posteriormente, aislamos las incógnitas de la ecuación:

$$ x = -2 -4y $$
Con esto podremos sustituir el valor de x en la otra ecuación.

$$ 2 · (-2 -4y) - 3y = 7 $$
Si resolvemos esta ecuación nos daría que y = -1.

Si sustituimos este valor de y en la ecuación anterior, obtenemos que x = 2. Por lo tanto la solución sería:

$$ (x, y) = (2, -1) $$

> [!DANGER] Recuerda comprobar
> Es importante que siempre que obtengas resultados de un sistema de ecuaciones, compruebes que los resultados resuelven correctamente estas.


#### Igualación

El método de igualación consiste en aislar la misma incógnita en ambas ecuaciones del sistema.

$$
\begin{cases}
2x - 3y = 7 \\
x + 4y = -2
\end{cases}
$$
Si aislamos la incógnita x en ambas ecuaciones obtendremos lo siguiente:

$$
x = \frac{7+ 3y}{2}
$$
$$
x = -2 -4y
$$
Igualamos ambas expresiones:

$$
\frac{7+3y}{2} = -2 - 4y
$$
$$
7 + 3y = 2· (-2 -4y)
$$
$$ 7+3y = -4 -8y $$
$$ 3y + 8y = -4 -7 $$
$$ 11y = -11 $$
$$ y = -1 $$
Ahora que tenemos el valor de y podremos obtener el valor de x:

$$ x = - 2 -4 · (-1) = -2 +4 = 2 $$

#### Reducción

Este método consiste en multiplicar convenientemente las ecuaciones del sistema por unos números, de modo que al restar las ecuaciones resultantes se "reduzca" el número de incógnitas de dos a una.

Por ejemplo, si tenemos el sistema anterior:

$$
\begin{cases}
2x - 3y = 7 \\
x + 4y = -2
\end{cases}
$$
Podríamos multiplicar la primera ecuación por 1, y la segunda ecuación por 2, para que así nos quede el siguiente sistema:


$$
\begin{cases}
2x - 3y = 7 \\
2x + 8y = - 4
\end{cases}
$$
Ahora vemos que si restamos la segunda ecuación a la primera, no tendríamos la x, y nos quedaría una ecuación con y.

$$
\begin{cases}
2x - 3y = 7 \\
- (2x + 8y = - 4)
\end{cases}
$$
$$
-3y -8y = 7 +4
$$
$$ -11y = 11 $$
$$ y = -1 $$
Esto nos daría el valor de y, por lo tanto podríamos despejar el valor de x también:

$$
x + 4 · (-1) = -2
$$
$$ x = 2 $$

## Sistemas lineales de tres ecuaciones y tres incógnitas

Igual que antes, podemos definir un sistema de ecuaciones lineales con tres incógnitas como un conjunto de tres ecuaciones de primer grado con las tres mismas incógnitas en cada una de las ecuaciones.

$$
\begin{cases}
3x -2y +z = 2 \\
x + y - 2z = 1 \\
4x - 2y -3z = -4
\end{cases}
$$
### Métodos de resolución

Para resolver este tipo de sistemas tendremos que utilizar el método de Gauss.

En este necesitamos manipular las ecuaciones de manera que podamos simplificar las expresiones y posteriormente, despejar una de las incógnitas, y a partir de ahí, despejar las otras 2 que quedan pendientes.

Por ejemplo, teniendo el sistema:

$$
\begin{cases}
 x + y + z = 0 \\
2x - 5y - 2z = -2 \\
3x + 4y + z = 8
\end{cases}
$$
Podría pasar a ser este sistema:

$$
\begin{cases}
x + y + z = 0 \\
-7y -4z = -2 \\
y - 2z = 8
\end{cases}
$$
Ya que haremos que la ecuación dos sea igual a la ecuación dos menos la ecuación por 2. Y por otro lado, haremos lo mismo para la ecuación 3.

Posteriormente, podremos multiplicar la tercera ecuación por 7 y sumarla con la segunda ecuación para así eliminar la incógnita y.

$$
\begin{cases}
 x + y + z = 0 \\
-7y -4z = -2 \\
-18z = 54
\end{cases}
$$

Con esto ya conseguimos lo siguiente:

$$ z = -\frac{54}{18} = -3 $$
Ahora podremos ir a la segunda ecuación y reemplazar el valor de z:

$$
-7y - 4 · (-3) = -2
$$
$$ y = \frac{-2 -12}{-7} = 2 $$
Por último, sustituiremos los valores de z e y en la primera ecuación para obtener el valor de x:

$$
x = -y - z 
$$
$$
x = 3 - 2 = 1
$$

## Sistemas lineales de *m* ecuaciones y *n* incógnitas

