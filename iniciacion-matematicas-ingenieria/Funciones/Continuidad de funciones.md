[[Iniciacion Matematicas Ingenieria]], [[Calculo]]

- [[#Operaciones con límites|Operaciones con límites]]
	- [[#Operaciones con límites#Suma y resta|Suma y resta]]
	- [[#Operaciones con límites#Producto|Producto]]
	- [[#Operaciones con límites#División|División]]
	- [[#Operaciones con límites#Exponencial|Exponencial]]
- [[#Límites laterales|Límites laterales]]
- [[#Límites al infinito|Límites al infinito]]
	- [[#Límites al infinito#Diccionario de símbolos|Diccionario de símbolos]]
	- [[#Límites al infinito#Traducción Lógica|Traducción Lógica]]
	- [[#Límites al infinito#Diferencia entre $+\infty$ y $-\infty$|Diferencia entre $+\infty$ y $-\infty$]]
- [[#Reglas de cálculo|Reglas de cálculo]]
- [[#Indeterminaciones|Indeterminaciones]]
	- [[#Indeterminaciones#0 partido de 0|0 partido de 0]]
	- [[#Indeterminaciones#Infinito partido de infinito|Infinito partido de infinito]]
	- [[#Indeterminaciones#0 multiplicado por infinito|0 multiplicado por infinito]]
	- [[#Indeterminaciones#Infinito menos infinito|Infinito menos infinito]]
	- [[#Indeterminaciones#1 elevado a infinito|1 elevado a infinito]]


El límite de una función en un valor $x$ es igual a un número al que tiende la función cuando la variable tiende a este valor (sin llegar nunca a serlo).

## Operaciones con límites

### Suma y resta

El límite de la suma (o resta) de dos funciones en un punto es igual a la suma (o resta) de límites de estas funciones, es decir:

$$
\lim_{ x \to a }(f(x) \pm g(x)) = \lim_{ x \to a }f(x) \pm \lim_{ x \to a }g(x)
$$
### Producto

El límite del producto de dos funciones es igual al producto de sus respectivos límites:

$$
\lim_{ x \to a }(f(x) · g(x)) = \lim_{ x \to a }f(x) · \lim_{ x \to a }g(x)
$$
### División

El límite de un cociente de dos funciones en un punto es igual al cociente de los límites de estas funciones:

$$
\lim_{ x \to a } \frac{f(x)}{g(x)} = \frac{\lim_{ x \to a } f(x)}{\lim_{ x \to a } g(x)}
$$

### Exponencial

El límite del exponencial de una función por otra en un punto es igual al exponencial de límite de estas funciones en el punto en cuestión siempre que ambas funciones no tomen el valor 0 a la vez:

$$
\lim_{ x \to a }f(x)^{g(x)} = \lim_{ x \to a }f(x)^{\lim_{ x \to a }g(x) }  
$$

## Límites laterales

El límite lateral por la izquierda (o la derecha) de una función $f(x)$ en un punto $a$ es el límite de la función cuando se considera que la variable solo puede tomar valores menores (o mayores) que el punto, esto es, el valor que toma la función cuando nos aproximamos a su punto objetivo desde puntos por su izquierda (o por la derecha). Este límite se denota por:

$$
\lim_{ x \to a⁻ } f(x) = b
$$
$$
\lim_{ x \to a^+ } f(x) = b
$$
Si los dos límites laterales existen y coinciden con el mismo valor, el límite de la función también existirá y tomará el mismo valor. Aún así, si los dos límites laterales toman valores diferentes, el límite de la función en aquel punto no existe (aunque la función sí esté definida en aquel punto).


## Límites al infinito

Esta definición formaliza la idea de una **Asíntota Horizontal**. Describe cómo la función se estabiliza en una altura $b$ cuando nos alejamos mucho del origen.

### Diccionario de símbolos

Para entender la frase: _"Para todo $\epsilon > 0$ existe un $k$..."_

- **$\epsilon$ (Épsilon):** Es el **margen de error** o tolerancia. Visualmente, crea una franja horizontal (un "tubo") alrededor del límite $b$ con un ancho de $2\epsilon$.
    
- **$k$:** Es la **frontera** en el eje $x$. Es el punto a partir del cual la función empieza a "comportarse bien".
    
- **$|f(x) - b| < \epsilon$:** Significa que la distancia entre la función y el límite es menor que el error. Visualmente: **la gráfica está dentro del tubo**.
    

### Traducción Lógica

La definición es un reto de condiciones:

No importa qué tan estrecho hagas el margen de error ($\epsilon$), siempre podré encontrar un punto ($k$) tal que, si pasamos de ese punto, la gráfica se queda **atrapada** dentro de ese margen para siempre.

### Diferencia entre $+\infty$ y $-\infty$

|**Límite**|**Condición**|**Interpretación Visual**|
|---|---|---|
|**$x \to +\infty$**|Si $x > k$|Miramos hacia la **derecha**. A partir de $k$, la función entra en el tubo y no sale.|
|**$x \to -\infty$**|Si $x < k$|Miramos hacia la **izquierda**. Antes de $k$, la función ya venía dentro del tubo.|

## Reglas de cálculo

$$
k·\infty = \infty, k \neq 0
$$
$$
\infty + \infty = \infty, k+\infty = \infty
$$
$$
\frac{k}{\infty} = 0
$$
$$
\frac{k}{0} = \infty, k \neq 0
$$
## Indeterminaciones

### 0 partido de 0

Se factorizan y simplifican los polinomios.

![[Pasted image 20251213000922.png]]

### Infinito partido de infinito

Se busca el término dominante de cada polinomio (el de grado superior) y se dividen las expresiones por este, simplificando así la expresión.

![[Pasted image 20251213001033.png]]

### 0 multiplicado por infinito

Este caso siempre se da en límites del tipo:

$$
\lim_{ x \to a } f(x) · g(x) 
$$
Ya que uno de los límites de las funciones vale 0 y el otro $\infty$. Para resolverlo escribiremos el producto de la siguiente manera:

$$
f(x) · g(x) = \frac{f(x)}{\frac{1}{g(x)}}
$$
Esto convertirá el límite en uno de tipo infinito partido de infinito, que habría que resolver como en el anterior apartado.


### Infinito menos infinito

Este caso es habitual en diferencias de funciones que contienen raíces. En estos casos hay que multiplicar y dividir la función por su conjugada (la misma expresión cambiando la resta por una suma) y usar la igualdad notable $(a-b)·(a+b)=a²-b²$

![[Pasted image 20251213002728.png]]


### 1 elevado a infinito

Es una indeterminación que aparece cuando tenemos una función exponencial en la que la base tiende a 1 y el exponente a infinito.

Esto se soluciona haciendo el siguiente cambio:

$$
\lim_{ x \to a }f(x)^{g(x)} = e^{\lim_{ x \to a } [f(x) - 1] · g(x) } 
$$
![[Pasted image 20251213003023.png]]

