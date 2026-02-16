Asignatura: [[Álgebra]]

- [[#Representación de números complejos|Representación de números complejos]]
- [[#Representación gráfica|Representación gráfica]]
- [[#Operaciones con números complejos|Operaciones con números complejos]]
	- [[#Operaciones con números complejos#Suma y resta de complejos|Suma y resta de complejos]]
	- [[#Operaciones con números complejos#Producto de complejos|Producto de complejos]]
	- [[#Operaciones con números complejos#Conjugado de un número complejo|Conjugado de un número complejo]]
	- [[#Operaciones con números complejos#División de números complejos en forma binómica|División de números complejos en forma binómica]]
		- [[#División de números complejos en forma binómica#Dividido por número real|Dividido por número real]]
		- [[#División de números complejos en forma binómica#Dividido por número complejo|Dividido por número complejo]]
- [[#Forma polar|Forma polar]]
	- [[#Forma polar#Componentes de la forma polar|Componentes de la forma polar]]
		- [[#Componentes de la forma polar#Módulo ($r$ o $|z|$)|Módulo ($r$ o $|z|$)]]
		- [[#Componentes de la forma polar#Argumento ($\alpha$ o $\theta$)|Argumento ($\alpha$ o $\theta$)]]
	- [[#Forma polar#Pasar de binómica a polar|Pasar de binómica a polar]]
		- [[#Pasar de binómica a polar#Calcular módulo|Calcular módulo]]
		- [[#Pasar de binómica a polar#Calcular argumento|Calcular argumento]]
		- [[#Pasar de binómica a polar#Ejemplo|Ejemplo]]
	- [[#Forma polar#Pasar de polar a binómica|Pasar de polar a binómica]]
		- [[#Pasar de polar a binómica#Ejemplo|Ejemplo]]
	- [[#Forma polar#Operaciones aritméticas con números complejos en forma polar|Operaciones aritméticas con números complejos en forma polar]]
		- [[#Operaciones aritméticas con números complejos en forma polar#Suma o resta de números complejos en forma polar|Suma o resta de números complejos en forma polar]]
		- [[#Operaciones aritméticas con números complejos en forma polar#Producto y división de números complejos en forma polar|Producto y división de números complejos en forma polar]]
- [[#Forma exponencial|Forma exponencial]]
	- [[#Forma exponencial#Operaciones aritméticas|Operaciones aritméticas]]
		- [[#Operaciones aritméticas#Multiplicación|Multiplicación]]
		- [[#Operaciones aritméticas#División|División]]
		- [[#Operaciones aritméticas#Potencia|Potencia]]


## Representación de números complejos

Los números complejos tienen forma binómica, es decir, se componen de la forma $a + bi$, en la que $a$ y $b$ son números reales.

$$
2+3i
$$
$$
3 - 4i
$$
$$
-\frac{2}{3} + 8i
$$
$$
\sqrt{ 2 } + 10i
$$
## Representación gráfica

Para representar los números complejos utilizaremos la **parte real como la abscisa** (coordenada $x$) y la **parte imaginaria con la ordenada** (coordenada $y$).

Por lo tanto, por ejemplo, el número $2 + 3i$ tendría el punto del plano $(2,3)$. Mientras que el número $\sqrt{ 2 } + 10i$ tendría el punto del plano $(\sqrt{ 2 }, 10)$.

Además, si un número complejo no tiene parte real (tiene parte real igual a cero), recibirá el nombre de **número complejo imaginario puro**. Por ejemplo, $i$, $2i$, $\sqrt{ 3 }i$ son números complejos imaginarios puros.

Si, por la contra, el número complejo no tiene parte imaginaria, lo denominaremos **número real**. Por ejemplo, $2$, $-1$, o $e$ son números reales.

## Operaciones con números complejos

### Suma y resta de complejos

Si están en su forma binómica, podremos sumar las partes reales y las partes imaginarias por separado.

$$
(1+2i) + (4+3i) = (1+4) + (2i+3i) = 5 + 5i
$$
Para la resta sería exactamente igual, solo que restando los operandos:

$$
(2-i) - (1+3i) = 1 - 4i
$$
Estas operaciones se pueden representar gráficamente utilizando la ley del paralelogramo, que también se utilizar para sumar y restar vectores.

![[Pasted image 20260207125903.png]]
![[Pasted image 20260207125922.png]]

### Producto de complejos

Si es un producto por un escalar, simplemente se multiplica el binomio:

$$
3 · (1 + 3i) = 3 + 9i
$$

Si es un producto de binomios de números complejos se hace la multiplicación como si fuesen polinomios, por ejemplo:

$$
(1+2i) · (4+3i) = 4 + 3i + 8i + 6i² = 4 + 11i + 6i² = 4 + 11i + 6 · (-1) = 11i - 2
$$

> [!DANGER] Equivalencia de i²
> Recuerda que i² es igual a -1, por lo tanto, siempre que lo veas lo puedes reemplazar por este valor.


### Conjugado de un número complejo

El conjugado de un número complejo $z = a + bi$, es otro número complejo con la misma parte real pero con la parte imaginaria cambiada de signo. El conjugado de un número complejo $z$  se representa como $\tilde{z}$.

Por ejemplo, el conjugado de $1+2i$ sería $1 - 2i$.

![[Pasted image 20260209195846.png]]

Además, existe la propiedad que nos indica que el producto de un número complejo por su conjugado nos dará siempre un número real mayor o igual a 0.

### División de números complejos en forma binómica

#### Dividido por número real

Si dividimos un número complejo en forma binómica por un número real, simplemente dividiremos los miembros de esta expresión por el número real.

$$
\frac{1+2i}{5} = \frac{1}{5} + \frac{2i}{5}
$$
#### Dividido por número complejo

En este caso necesitaremos multiplicar por la misma división pero con el conjugado del denominador de la división original.

$$
\frac{1+2i}{3-4i} = \frac{1+2i}{3-4i} · \frac{3+4i}{3+4i} = \frac{(1+2i)·(3+4i)}{(3-4i)·(3+4i)} = \frac{3-8+6i+4i}{3² + 4²} = \frac{-5 + 10i}{25} = -\frac{5}{25} + \frac{10}{25}·i = -\frac{1}{5} + \frac{2}{5}·i
$$


## Forma polar

Antes habíamos visto como los números complejos se representaban de manera binómica. Además, existe otra manera de representarlos, llamada **forma polar**. Esta forma nos permite llegar al mismo punto en el plano, pero con pasos distintos.

Cuando pensamos en la forma polar, tenemos que pensar en, por ejemplo, un radar militar, ya que si queremos identificar un punto tenemos que saber la apertura del ángulo, y cuanto tenemos que avanzar.

Antes, con forma binómica expresábamos algo como "camina 3 metros al este y 4 metros al norte" $z= 3 + 4i$. Ahora, podemos expresar esto mismo como "Gira 53 grados y camina 5 metros en línea recta" $z=5_{53º}$ o $5 \angle 53^\circ$.

Ambos son compatibles e idénticos, solo que cambiamos el lenguaje.

### Componentes de la forma polar

#### Módulo ($r$ o $|z|$)

El módulo es lo que necesitamos avanzar, o, la **longitud** que necesitamos avanzar desde el punto (0,0).

Este componente siempre va a representar la "magnitud" o "tamaño" del número complejo, y siempre es **positivo**.

#### Argumento ($\alpha$ o $\theta$)

Es el ángulo que forma el módulo con el eje horizontal positivo (el eje de las X).

Este se mide en sentido contrario a las agujas del reloj, y se puede expresar en grados ($360º$) o en radianes ($2\pi$).

### Pasar de binómica a polar

Si tenemos una expresión como $z = a+bi$ y queremos llegar a $r_{\alpha}$, tendremos que calcular el **módulo** y el **argumento**.

#### Calcular módulo

El módulo se calcula de la siguiente manera:

$$
r = \sqrt{ a² + b² }
$$
#### Calcular argumento

Sabemos cuanto mide el cateto opuesto y el contiguo, lo que nos permite utilizar la fórmula de la tangente:

$$
\tan(\alpha) = \frac{b}{a} \implies \alpha = \arctan\left( \frac{b}{a} \right)
$$

> [!DANGER] TRAMPA DE ARCOTANGENTE Y CALCULADORA
> Antes de calcular el arcotangente, visualiza el punto en forma binómica, y mira en que cuadrante está, ya que **si se encuentra en el segundo o tercer cuadrante hay que sumarle 180º** a lo que nos indique la calculadora, ya que esta asume que nuestro ángulo se encuentra en el primer o cuarto cuadrante.

#### Ejemplo

Queremos pasar $z = -3 + 3i$ a forma polar, por lo que tendremos que calcular el módulo y el argumento:

Módulo:

$$
r = \sqrt{ a² + b^2 } = \sqrt{ (-3)² + 3² } = \sqrt{ 18 }
$$
Argumento:

$$
\alpha = \arctan\left( \frac{b}{a} \right) = \arctan\left( -\frac{3}{3} \right) = -45º + 180º = 135º
$$
Se suman 180º ya que podemos comprobar que este número complejo se encontraría representado en el segundo cuadrante, ya que vamos a -3 en las X, y subimos 3 en Y.

Esto nos deja una forma final de:

$$
\sqrt{ 18 }_{135º}
$$
### Pasar de polar a binómica

Si tenemos un número complejo $a+bi$ y el ángulo que forma con el eje positivo de las $x$, es decir, $z = r_{\theta}$, podríamos determinar que:

$$
sen(\theta) = \frac{b}{r}
$$
$$
\cos(\theta) = \frac{a}{r}
$$
Lo que nos permitiría afirmar que:

$$
a = r · \cos(\theta)
$$
$$
b = r · sen(\theta)
$$
Es decir, el número $r_{\theta}$ en forma binómica es:

$$
z = r_{\theta} = r · \cos(\theta) + r·sen(\theta) ·i
$$
Por lo tanto, la equivalencia entre la forma polar y la forma binómica de un número complejo es:

$$
r_{\theta} = r·\cos(\theta) + r·sen(\theta) · i = r(\cos(\theta) + sen(\theta)· i)
$$
Esta manera de expresar un número complejo recibe el nombre de **forma trigonométrica**.

#### Ejemplo

Si tenemos el número complejo en forma polar $\sqrt{ 3 }_{{\frac{\pi}{6}}}$. ¿Cuál es su representación en forma binómica?

$$
\sqrt{ 3 }_{\frac{\pi}{6}} = \sqrt{ 3} · \cos\left( \frac{\pi}{6} \right) + \sqrt{ 3 } · sen\left( \frac{\pi}{6} \right) · i
$$
$$
\sqrt{ 3 } · \frac{\sqrt{ 3 }}{2}
 + \sqrt{ 3 } · \frac{1}{2} · i
$$
$$
\frac{3}{2} + \frac{\sqrt{ 3 }}{2} ·i
$$

### Operaciones aritméticas con números complejos en forma polar

#### Suma o resta de números complejos en forma polar

Para sumar o restar números complejos en forma polar debemos expresarlos primero en forma binómica y posteriormente sumarlos o restarlos.

Por ejemplo, tenemos $z_{1} = 2_{\pi}$ y $z_{2} = 5_{-\frac{\pi}{2}}$.
Tendríamos que pasar ambos a forma bińomica:

$$
z_{1} = 2 · \cos(\pi) + 2 · sen(\pi) · i = -2
$$
$$
z_{2} = 5 · \cos\left( -\frac{\pi}{2} \right) + 5·sen\left( -\frac{\pi}{2} \right) · i = -5i
$$
$$
z_{1} + z_{2} = -2 + (-5i) = -2 -5i
$$
$$
z_{1} - z_{2} = -2 - (-5i) = -2 + 5i
$$
#### Producto y división de números complejos en forma polar

Para multiplicar dos números en forma polar se multiplican los módulos y se suma los argumentos.

Si tenemos la siguiente multiplicación:

$$
z_{1} · z_{2} = 2_{\pi} · 5_{-\frac{\pi}{2}} = (2·5)_{\pi+\left( -\frac{\pi}{2} \right)} = 10_{\frac{\pi}{2}}
$$
En un caso genérico se podría llegar a la siguiente fórmula:

$$
r_{\theta_{1}} · s_{\theta_{2}} = (r·s)_{\theta_{1}+\theta_{2}}
$$
De manera similar, para la división deberemos dividir los módulos y se restan los argumentos.

$$
\frac{z_{1}}{z_{2}} = \frac{2_{\pi}}{5_{-\frac{\pi}{2}}} = \frac{2}{5}_{\pi-\left( -\frac{\pi}{2} \right)} = \frac{2}{5}_{\frac{3·\pi}{2}}
$$

## Forma exponencial

La función exponencial real es la suma de infinitos términos:

$$
e^x = 1 + x + \frac{x²}{2!} + \frac{x³}{3!} + \frac{x⁴}{4!}+\dots
$$
![[Pasted image 20260212210440.png]]

Siguiendo la demostración, podemos determinar lo siguiente:

$$
e^{\theta i} = \cos(\theta) + sen(\theta)i
$$
Este resultado lo denominamos la **Fórmula de Euler**.

Además, como sabemos que un número complejo lo podemos expresar como $z = r(\cos(\theta) + sen(\theta) · i)$, llegaremos a la conclusión de que la forma exponencial de un número complejo es:

$$
z = r · e^{\theta i}
$$
En el que $r = |z|$ es el módulo de $z$ y $\theta$ es el argumento de $z$.

La representación polar de un número complejo es, pues, equivalente a la representación exponencial del mismo número complejo. En efecto:

$$
r·e^{\theta i} = r·(\cos(\theta) + i · sen(\theta)) = r_{\theta}
$$

![[Pasted image 20260212210918.png]]

### Operaciones aritméticas

Vamos a utilizar estos dos números complejos para los ejemplos:

$$
z = 3 · e^{\frac{\pi}{3}·i}
$$
$$
w = 2 · e^{\frac{\pi}{6}·i}
$$

#### Multiplicación

Tendríamos que multiplicar los módulos y sumar los argumentos.

En el ejemplo anterior quedaría:

$$
(3·2)·e^{(\frac{\pi}{3} + \frac{\pi}{6})·i} = 6·e^{\frac{\pi}{2}i}
$$
#### División

Tendríamos que dividir los módulos y restar los argumentos.

En el ejemplo anterior quedaría:

$$
\left( \frac{3}{2} \right)·e^{\left( \frac{\pi}{3} - \frac{\pi}{6} \right)·i} = \frac{3}{2}·e^{\frac{\pi}{6}i}
$$
#### Potencia

Si queremos elevar un número complejo a una determinada potencia tendremos que aplicar la siguiente fórmula:

$$
(r·e^{\theta i})^n = r^n · e^{n\theta i}
$$
Si queremos aplicar el ejemplo anterior y hacer $z³$, haríamos lo siguiente:

$$
r³ · e^{3·\theta·i} = 3³ + e^{3 · \frac{\pi}{3}i} = 27·e^{\pi·i}
$$

## Raíces enésimas

Si queremos calcular las raíces enésimas de un número complejo tendremos que pasar este a forma polar para posteriormente aplicar la fórmula de las raíces enésimas:

$$
\frac{\theta + 2·\pi·k}{n}
$$
Siendo $n$ dependiente del tipo de raíz que se calcule, ya que si es una cúbica, será 3, si es una cuarta será 4, etc.

El módulo de estas soluciones ($r$), será la raíz cúbica, cuarta, etc de nuestro número original, por ejemplo, si queremos calcular las raíces cúbicas de 8, tendríamos que el módulo es 2, ya que $2³ = 8$.

Una vez tengamos las soluciones en forma polar las pasaremos a su forma binómica utilizando la fórmula:

$$
z = R(\cos \alpha + i · \sin \alpha)
$$

Estas expresiones binómicas serán nuestras soluciones.

### Ejemplo

Si queremos resolver $z³ = -8$:

![[Pasted image 20260216190524.png]]

### Representación gráfica

Si representamos este tipo de problemas en el plano, veremos como dependiendo del índice de la raíz, surge una figura u otra. En caso de una raíz cúbica, resultará un triángulo, ya que nos aportaría 3 soluciones. Si fuese una raíz cuarta, sería un cuadrado, ya que tiene 4 soluciones, y así sucesivamente. Esto nos lleva a afirmar que cada solución encontrada, será igual a un nuevo vértice en nuestra representación gráfica.

![[Pasted image 20260216193639.png]]

![[Pasted image 20260216193649.png]]