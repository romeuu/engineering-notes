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
- [[#Continuidad|Continuidad]]
	- [[#Continuidad#Discontinuidad de una función|Discontinuidad de una función]]
		- [[#Discontinuidad de una función#Discontinuidad evitable|Discontinuidad evitable]]
		- [[#Discontinuidad de una función#Discontinuidad de salto|Discontinuidad de salto]]
		- [[#Discontinuidad de una función#Discontinuidad asintótica|Discontinuidad asintótica]]
	- [[#Continuidad#Asíntotas|Asíntotas]]
		- [[#Asíntotas#Asíntotas verticales|Asíntotas verticales]]
		- [[#Asíntotas#Asíntotas horizontales|Asíntotas horizontales]]
		- [[#Asíntotas#Asíntotas oblicuas|Asíntotas oblicuas]]
- [[#Repaso ejercicios|Repaso ejercicios]]



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


## Continuidad

Para que una función $f(x)$ sea continua en un punto $x = c$ deben cumplirse tres condiciones:

1. $f(c)$ existe.
2. $\lim_{ x \to c }f(x)$ existe.
3. $\lim_{ x \to c }f(x) = f(c)$


### Discontinuidad de una función

#### Discontinuidad evitable

Este tipo de discontinuidad se da cuando la función no está definida en el punto $x_0$, pero los límites laterales sí que existen y coinciden. Es decir:

$$
\lim_{ x \to x_{o}⁺ }f(x) = \lim_{ x \to x_{o}⁻ }f(x)  
$$

![[Pasted image 20251213202227.png]]

#### Discontinuidad de salto

Es el caso cuando los dos límites laterales de la función existen pero no toman el mismo valor, independientemente de si la función está definida en aquel punto o no. Es decir:

$$
\lim_{ x \to x_{o}⁺ }f(x) \neq \lim_{ x \to x_{o}⁻ }f(x)  
$$
![[Pasted image 20251213202243.png]]

#### Discontinuidad asintótica

Esta discontinuidad es una versión extrema del caso anterior, en que al emnos uno de los límites laterales es infinito. Es decir:

$$
\lim_{ x \to x_{o}⁺ }f(x) = \pm\infty  
$$
$$
\lim_{ x \to x_{o}⁻ }f(x) = \pm \infty  
$$
![[Pasted image 20251213202255.png]]

### Asíntotas

#### Asíntotas verticales

Se dan en un punto $k$ del eje $X$ cuando al menos uno de los límites laterales en este punto tiende a $\pm \infty$, es decir, cuando en la función tiene una discontinuidad asintótica en $k$. En este caso, la recta de ecuación $x=k$ es la asíntota vertical.

![[Pasted image 20251213202852.png]]

#### Asíntotas horizontales

Se dan cuando existe el límite en alguno de los infinitos. Si $\lim_{ x \to \infty }f(x) = k$, la recta de ecuación $y=k$ es la asíntota horizontal (ídem con el límite con $-\infty$). Una función puede tener hasta dos asíntotas horizontales si los dos límites a $\pm \infty$ existen y toman valores diferentes.

![[Pasted image 20251213202904.png]]

#### Asíntotas oblicuas

Si, y solo si, se cumple:

$$
\lim_{ x \to \pm\infty }f(x) = \infty 
$$
$$
\lim_{ x \to \pm\infty } \frac{f(x)}{x} = a
$$
$$
\lim_{ x \to \pm\infty }[f(x) - ax] = b 
$$
Siendo $a,b$ números reales y $y=ax+b$ es la ecuación de la asíntota.

![[Pasted image 20251213202921.png]]
![[Pasted image 20251213203426.png]]

## Repaso ejercicios

Si tienes que buscar asíntotas de una función polinómica que sea una división:

- Si el denominador no se anula nunca, no hay asíntotas verticales.
- Si el denominador tiene mayor grado que el numerador, el límite de f(x) es 0, por lo tanto, existe una asíntota horizontal en y=0.

Asíntotas:

- Exponenciales ($e^{x-2}$): Las asíntotas horizontales solo cambian si sumas números **fuera** de la $x$ (ej: $e^x + 2$). Si restas dentro del exponente ($x-2$), solo mueves la gráfica a los lados, la altura (asíntota horizontal $y=0$) no cambia.
- **Logaritmos ($\log(x-2)$):** Aquí es al revés. La asíntota vertical se mueve si tocas la $x$. Como el logaritmo explota en 0, $\log(x-2)$ explotará en $x=2$. Por eso la asíntota vertical se mueve.