[[Iniciacion Matematicas Ingenieria]], [[Calculo]]

- [[#Funciones lineales|Funciones lineales]]
- [[#Funciones afines|Funciones afines]]
	- [[#Funciones afines#Propiedades|Propiedades]]
- [[#Funciones cuadráticas|Funciones cuadráticas]]
	- [[#Funciones cuadráticas#Vértices|Vértices]]
	- [[#Funciones cuadráticas#Puntos de corte|Puntos de corte]]
	- [[#Funciones cuadráticas#Tabla de valores|Tabla de valores]]
	- [[#Funciones cuadráticas#Modificaciones|Modificaciones]]


## Funciones lineales

Las funciones lineales son funciones que su expresión es el producto de un número por la variable. Es decir, *f* es una función lineal si:

$$
f(x) = a·x
$$
El número que multiplica a la variable, se denomina **razón de proporcionalidad**.

$$
g(x) = 2x
$$
$$
h(x) = 4x
$$
$$
s(x) = -3x
$$
Estas tendrían razón de proporcionalidad 2, 4, y -3, respectivamente.

Si la **razón de proporcionalidad**, también llamada **pendiente**, es positiva, crecerá con más rapidez, y si es negativa, decrecerá con más rapidez.

Las funciones lineales, cortan siempre el punto (0,0).

![[Pasted image 20251122115939.png]]


## Funciones afines

Este tipo de funciones son las que su expresión es un polinomio de primer grado:

$$
f(x) = ax+b
$$
Son exactamente igual que las funciones lineales, pero sin cortar el punto (0,0), ya que el término independiente que se suma, hace que se mueva la gráfica.

En este caso, llamamos **pendiente** a *a*, y **término independiente** a *b*.

$$
g(x) = 3x - 2
$$
En este caso, la pendiente sería 3, y el término independiente -2.

Para representar estas gráficas haremos lo mismo que en el caso anterior, una tabla de valores, y representar los números que obtengamos.

Si queremos calcular los puntos de corte, podremos hacerlo de la siguiente manera:

![[Pasted image 20251122120413.png]]

Asimismo, si queremos calcular la función afín a partir de dos puntos, tendremos que hacer lo siguiente:

![[Screenshot from 2025-11-22 12-06-05.png]]

### Propiedades

Podemos distinguir tres tipos de funciones afines según el valor de la pendiente:

- Si la pendiente es positiva, se denomina **función creciente**.
$$
f(x) = ax + b \implies a > 0
$$
- Si la pendiente es negativa, se denomina **función decreciente**.
$$
f(x) = ax + b \implies a < 0
$$
- Las funciones afines que son paralelas al eje X son **funciones constantes**, ya que tienen pendiente nula. Es decir:
$$
f(x) = ax + b \implies a = 0
$$

## Funciones cuadráticas

Las funciones cuadráticas son expresiones polinómicas de segundo grado.

$$
f(x) = ax² + bx + c
$$
La representación gráfica de estas funciones son **parábolas**. Si sabemos que el término que multiplica a la incógnita de segundo grado es **positivo**, será una **parábola cóncava**, mientras que si es **negativo**, será una **parábola convexa**.

![[Pasted image 20251122124119.png]]

### Vértices

Para calcular los vértices de esta parábola, tendremos que hacer lo siguiente:

$$
f(x) = x² - 6x + 5
$$
$$
x_{v} = -\frac{b}{2a} = \frac{6}{2} = 3
$$
$$
y_{v} = f(x_{v}) = f(3) = 3² - 6·3 + 5 = 9 - 18 + 5 = -4
$$
Con esto obtendremos que el vértice sería:

$$
(3, -4)
$$
### Puntos de corte

Para calcular los puntos de corte correspondiente a *x*, haremos lo siguiente:

$$
f(x) = 0 \implies x² - 6x + 5 = 0 \implies \begin{cases}
x=5 \\
x=1
\end{cases}
$$
Esto nos daría los dos puntos de corte para el eje *X* de esta función:

$$
(5, 0) (1,0)
$$
Si la ecuación de segundo grado tiene solo un resultado, nos indica que solo corta a X en un punto, mientras que si no tiene resultado, no cortará el eje X.

Para calcularlos para el eje *Y*, sabemos que x = 0, por lo tanto:

$$
x = 0 \implies y = 5 \implies (0,5)
$$

### Tabla de valores

Sabiendo el vértice, y los puntos de corte, podremos tener una idea de como se representaría nuestra parábola, pero para que sea completamente fiable, tendremos que crear una tabla de valores, y completar el resto de puntos.

### Modificaciones

Si modificamos el término independiente de una función cuadrática, se desplazará verticalmente la parábola asociada, por lo tanto, si el término aumenta, la parábola sube, mientras que si se reduce, esta bajará.

Si el signo del coeficiente de grado 2 es positivo, las ramas irán hacia arriba, mientras que si es negativo, irán hacia abajo.

Si se cambia el valor del coeficiente del término de grado 2, en valor absoluto, también produce un cambio regular en la parábola: si disminuye, las ramas se separan, mientras que si aumenta, las ramas se acercan.


## Funciones polinómicas

 Estas funciones son funciones que tienen más de grado dos, por ejemplo, grado 3, 4, 5... Tienen ciertas características, al igual que las funciones lineales y de otros tipos, lo que nos permite tener una idea de como se representarían gráficamente:

- La **rama derecha** se dirigirá hacia **arriba** cuando el **coeficiente de grado máximo es positivo**, y hacia **abajo** cuando es **negativo**.
- La **rama izquierda** se dirige hacia abajo cuando el polinomio es de grado par y el coeficiente máximo es negativo, o bien cuando el polinomio es de grado impar y el coeficiente máximo es positivo. En caso contrario, el extremo de la izquierda se dirigirá hacia arriba.
- La **parte central** es la parte en la que la gráfica presenta varios pliegues. Cuanto mayor es el grado del polinomio más pliegues puede presentar, ya que el número de pliegues será igual o menor al grado máximo menos 1. Por ejemplo, un polinomio de grado 3, tendrá 2 pliegues como máximo, mientras que uno de 4, tendrá 3.

Por otra parte, podemos hablar de puntos importantes dentro de estas funciones, como serían:

- Los **extremos**. Este término hace referencia a los máximos y mínimos de la función. Se denomina **máximo relativo** (o local) de una función el punto en que la función pasa de ser creciente a decreciente. Al contrario, se denomina **mínimo relativo** (o local) al punto en el que pasa de ser decreciente a creciente.
- La **intersección con el eje Y**. Hay solo un punto de intersección entre la gráfica de cualquier polinomio y el eje Y. Este punto es el que tiene coordenada x = 0, y por lo tanto, se trata del punto del plano (0, f(0)).
- La **intersección con el eje X**. Puede haber un número de intersecciones con el eje X igual al grado del polinomio como máximo. Asimismo, no siempre se llega a este número. Estos puntos serán las raíces del polinomio, ya que tendremos que igualar el polinomio a 0 y resolverlo.

![[Pasted image 20251122163244.png]]