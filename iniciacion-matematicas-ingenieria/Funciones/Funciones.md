[[Iniciacion Matematicas Ingenieria]], [[Calculo]]

- [[#Correspondencia entre conjuntos|Correspondencia entre conjuntos]]
- [[#Aplicaciones y funciones|Aplicaciones y funciones]]
	- [[#Aplicaciones y funciones#Tipos de aplicaciones/funciones|Tipos de aplicaciones/funciones]]
		- [[#Tipos de aplicaciones/funciones#Inyectiva|Inyectiva]]
		- [[#Tipos de aplicaciones/funciones#Sobreyectiva|Sobreyectiva]]
		- [[#Tipos de aplicaciones/funciones#Biyectiva|Biyectiva]]
	- [[#Aplicaciones y funciones#Dominio y rango/imagen de una función|Dominio y rango/imagen de una función]]
		- [[#Dominio y rango/imagen de una función#Ejercicio resuelto|Ejercicio resuelto]]
	- [[#Aplicaciones y funciones#Representación de funciones|Representación de funciones]]
		- [[#Representación de funciones#Tabla de valores|Tabla de valores]]
		- [[#Representación de funciones#Expresión algebraica|Expresión algebraica]]
		- [[#Representación de funciones#Parejas ordenadas|Parejas ordenadas]]
		- [[#Representación de funciones#Gráfica|Gráfica]]


## Correspondencia entre conjuntos

La correspondencia entre dos conjuntos A y B, siendo el conjunto de partida A; y el conjunto de llegada B; se denomina *R*. 

El conjunto de los elementos del conjunto de partida (*A*) de los que sale alguna flecha, sería dominio de la correspondencia R o *DomR*.

En cambio, para el conjunto de llegada (*B*), se denomina imagen o recorrido de la correspondencia R o *ImR* (o también *RecR*).

Un elemento cualquiera del dominio de una correspondencia, se denomina *imagen del elemento*. Se denomina *antiimagen* de un elemento, a los elementos de los cuales parte una flecha hacia el elemento de la imagen.

Para calcular la imagen se sustituye el valor de x en la función. Para calcular la antiimagen, hay que igualar la función al valor que se nos proporciona.

Por ejemplo, si queremos calcular la imagen de 0, tendremos que sustituir 0 en nuestro polinomio.

Si queremos calcular la antiimagen de 8, haríamos algo así:

$$
7x + 7 = 8 \implies 7x = 1 \implies x = \frac{1}{7}
$$

## Aplicaciones y funciones

**Una aplicación** es una correspondencia que cumple que todos los elementos de su dominio tienen un único elemento en su imagen. Es decir, ningún elemento del conjunto de partida tiene más de una flecha.

Una **función** es una aplicación en la que los elementos de los conjuntos *A* y *B* son numéricos.

### Tipos de aplicaciones/funciones

#### Inyectiva

Cada elemento del conjunto de llegada (*B*) corresponde como máximo a **1** elemento del conjunto de partida (*A*).

Pueden darse elementos en el conjunto de llegada que no tenga correspondiente en el conjunto de partida.

Podemos identificar en un gráfico si es inyectiva cuando vemos que solo sube, o solo baja, ya que para un valor de y, solo tendrá un valor de x (o *antiimagen*).


> [!TIP] Truco
> Imagina que trazas líneas **horizontales** sobre la gráfica. Si ninguna de esas líneas toca la gráfica en más de un punto, es inyectiva.


#### Sobreyectiva

A cada elemento del conjunto de llegada le corresponde por lo menos un elemento del conjunto de partida. Es decir, en el conjunto de llegada, no sobraría ningún número.

Esto sería una relación N:1, cada elemento de ambos conjuntos tiene un valor (o más) correspondiente.

Podemos verificar que una función es sobreyectiva, es que siempre van desde abajo (menos infinito) hacia arriba (más infinito), o también que cubra todo el eje y.

#### Biyectiva

Una función es biyectiva cuando es inyectiva y sobreyectiva a la vez. Es decir, hay una relación perfecta 1:1 entre los dos conjuntos.

Generalmente, las funciones biyectivas son funciones sin curvas, que recorran desde más infinito a menos infinito en el eje y, es decir, una recta simple.

Se dan casos como las funciones cúbicas, que también serían biyectivas, aunque tienen curvas.

![[Pasted image 20251121190451.png]]

### Dominio y rango/imagen de una función

El dominio sería el equivalente al conjunto de partida (*A*), mientras que el rango o imagen serían los valores del conjunto de llegada (*B*) que tienen valor (o flecha asociada).

Podemos interpretar el dominio como los valores que se utilizarán para obtener un valor que nos devuelva la función (imagen).

![[Pasted image 20251121195345.png]]

Para calcular el rango de una función, nos fijaremos en el eje X, y para calcular el rango o imagen de una función, nos fijaremos en el eje Y.

#### Ejercicio resuelto

Para calcular el dominio de una función como: $$ b(x) = \sqrt{ x+1 }$$
Tendremos que buscar para que valores deja de funcionar esta función, por ejemplo, en este caso, tendremos lo siguiente:

$$
x+1 \geq 0
$$

$$
x \geq -1
$$
Por lo tanto, sabremos que esta función tendrá el siguiente dominio:

$$
[-1, +\infty)
$$

### Representación de funciones

Existen varios métodos para representar una función:

#### Tabla de valores

La tabla de valores es la tabla en la que representaremos la relación de un valor concreto de x para nuestra función f(x).

![[Pasted image 20251121202300.png]]

#### Expresión algebraica

Esta sería la expresión de nuestra función, por ejemplo:

$$
f(x) = x^{2}
$$
$$
y = x²
$$

#### Parejas ordenadas

Podemos indicar los valores de nuestra tabla de valores de la siguiente manera:

$$
f(x) = \{(-2, 4), (-1,1), (0,0), (1,1), (2, 4), (3,9)\}
$$

#### Gráfica

Para hacer la gráfica de una función necesitaremos saber la tabla de valores de una función. Posteriormente, simplemente representaremos en los ejes X e Y, los valores anteriores.

![[Pasted image 20251121203328.png]]


### Operaciones entre funciones

#### Operaciones básicas

##### Suma o resta de funciones:

La suma o resta de funciones se designa de la siguiente manera:

$$
(f\pm g)(x) = f(x)\pm g(x)
$$
Es decir, que si tenemos f(x) = 3x y g(x) = 4x² - 1:

$$
(f+g)(x) = f(x) + g(x) = 3x + 4x² - 1 = 4x² + 3x - 1
$$

**Propiedades**:

- **Conmutativa**: f + g es lo mismo que g + f.
- **Asociativa**: 
$$
f \pm (g \pm h) = (f\pm g) \pm h
$$
- Existe la llamada **función cero**, que es el elemento neutro de la suma de funciones, de modo que cualquier función sumada con este elemento no varía.
$$
z(x) = 0
$$
- Para cada función existe su **función opuesta**, que sumada a la función original da 0.
$$
f(x) \implies -f(x)
$$
$$
f(x) -f(x) = 0
$$

##### Producto de funciones

El producto de dos funciones se designa de la siguiente manera:

$$
(f·g)(x) = f(x) · g(x)
$$
Si tuviésemos que f(x) = 3x y g(x) = 4x² - 1

$$
(f·g)(x) = f(x) · g(x) = 3x · (4x² - 1) = 12x³ - 3x
$$

**Propiedades**:

- **Conmutativa**:
$$
f·g = g·f
$$
- **Asociativa**:
$$
f · (g · h) = (f·g) · h
$$
- Hay un elemento llamado **función unidad**, que es el neutro del producto de funciones, de modo que cualquier función multiplicada por este elemento no varía.

$$
u(x) = 1
$$

##### Cociente de funciones

El cociente de funciones se calcula de la siguiente manera:

$$
\left( \frac{f}{g} \right)(x) = \frac{f(x)}{g(x)}
$$
Este cociente puede calcularse siempre que la variable x esté en el dominio de las funciones que se consideran, y además, la función del denominador g(x) no sea la función 0.

Por ejemplo, si f(x) = x² - 1 y g(x) = x+1:

$$
\left( \frac{f}{g} \right)(x) = \frac{x²-1}{x+1} = x-1
$$

##### Potencia de funciones

La potencia de funciones se calcula de la siguiente manera:

$$
(f^{g})(x) = f(x)^{g(x)}
$$

Esta potencia se podrá calcular siempre que la variable, x, esté en el dominio de ambas funciones, f y g, y que ninguna de las funciones se anulen.

Si tenemos que f(x) = 4x² - 1 y g(x) = 3x:

$$
(f^{g})(x) = f(x)^{g(x)} = (4x²-1)^{3x}
$$

#### Composición de funciones y función inversa

Dadas dos funciones, se puede definir la función compuesta por ambas:

$$
(g ○ f)(x) = g(f(x))
$$

Por ejemplo, si tenemos:

$$
f(x) = x²
$$
$$
g(x) = 2x
$$
$$
(g ○ f)(x) = g(f(x)) = g(x²) = 2·x²
$$
$$
(f○g)(x) = f(g(x)) = (2x)^2 = 4x²
$$
A partir del concepto de composición, podemos definir el concepto de **inversa**. Si *f* es una función, se dice que *g* es la función inversa de f si cumple lo siguiente:

- (g○f)(x) = x para todo *x* que pertenezca al dominio de *f*.
- (f○g)(x) = x para todo *x* que perteneza al dominio de g

Por lo tanto, estas condiciones implican que el dominio de la función *f* es igual a la imagen de la función *g*, es decir:

$$
Domf = \mathrm{Im}g
$$
Esto significa que si tenemos una función *f*:

$$
f(3) = 5
$$

$$
(g○f)(3) = g(f(3)) = g(5) = 3
$$
De manera general, se dice que una función *g* es la inversa de *f* si se cumple que:

$$
f(x) = y
$$
$$
g(y) = x
$$

La función inversa se representa como:

$$
f^{-1}
$$
### Características de una función

Las funciones tienen tipos que se determinan por como utilizan la variable independiente, hablando así de familias de funciones: polinómicas, trigonométricas, exponenciales, logarítmicas...

$$
f(x) = 5x² - x - 2 \implies polinómica
$$
$$
g(x) = \sin(x) \implies trigonométrica
$$
$$
h(x) = 3^x \implies exponencial
$$

### Funciones a trozos

De forma general, las funciones se definen como una expresión algebraica aplicada a un dominio concreto. Sin embargo, una función puede estar definida por varias expresiones algebraicas diferentes, que forman una función definida a trozos o por partes.

Por ejemplo:

$$
f(x) = 
\begin{cases}
x+\pi \ \implies x\leq-\pi \\
\sin(x) \implies -\pi<x\leq \pi \\
1 \implies \pi<x\leq 2\pi
\end{cases}
$$

