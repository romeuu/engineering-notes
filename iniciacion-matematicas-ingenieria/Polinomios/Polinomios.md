[[Iniciacion Matematicas Ingenieria]]

- [[#Definición y aspectos generales|Definición y aspectos generales]]
	- [[#Definición y aspectos generales#Clasificación de un polinomio|Clasificación de un polinomio]]
	- [[#Definición y aspectos generales#Valor numérico de un polinomio|Valor numérico de un polinomio]]
- [[#Operaciones y propiedades básicas|Operaciones y propiedades básicas]]
	- [[#Operaciones y propiedades básicas#Operaciones básicas entre monomios|Operaciones básicas entre monomios]]
		- [[#Operaciones básicas entre monomios#Suma y resta|Suma y resta]]
		- [[#Operaciones básicas entre monomios#Producto|Producto]]
		- [[#Operaciones básicas entre monomios#Cociente|Cociente]]
	- [[#Operaciones y propiedades básicas#Operaciones básicas entre polinomios|Operaciones básicas entre polinomios]]
		- [[#Operaciones básicas entre polinomios#Suma y resta|Suma y resta]]
		- [[#Operaciones básicas entre polinomios#Producto|Producto]]
		- [[#Operaciones básicas entre polinomios#Cociente|Cociente]]
		- [[#Operaciones básicas entre polinomios#Fracciones algebraicas|Fracciones algebraicas]]
			- [[#Fracciones algebraicas#Producto y cociente de fracciones algebraicas|Producto y cociente de fracciones algebraicas]]
			- [[#Fracciones algebraicas#Suma y resta de fracciones algebraicas|Suma y resta de fracciones algebraicas]]
	- [[#Operaciones y propiedades básicas#Regla de Ruffini|Regla de Ruffini]]


## Definición y aspectos generales

Un polinomio es una expresión algebraica con una única letra, llamada variable. Los elementos básicos de un polinomio son los términos. cada término es producto de un coeficiente y un grado. Un polinomio con un solo término se llama monomio. Si tiene dos términos se denomina binomio.

$$
3a - 42a³ + 5a -2a +2
$$
$$
5b - 56b² + b - 17
$$
Los términos de estos polinomios serían:
$$
3a, -42a³ ,5a, -2a, 2
$$
$$
5b, -56b², +b, -17
$$
Los polinomios pueden designarse mediante letras para no tener que escribir toda la expresión otra vez, por ejemplo:

$$
p(x) = 5x³ - 4x² + 5x - 1
$$

### Clasificación de un polinomio

- Un polinomio con un solo término se denomina **monomio**.
- Un polinomio con dos términos se denomina **binomio**.
- Un polinomio con tres términos se denomina **trinomio**.

### Valor numérico de un polinomio

El valor numérico de un polinomio es el valor que se obtiene al sustituir la variable por un número determinado.

$$
p(1) = 5 · 1³ - 4 · 1² + 5·1 - 1 = 5
$$

## Operaciones y propiedades básicas

### Operaciones básicas entre monomios

#### Suma y resta

Sólo se pueden sumar en caso de que tengan el mismo grado, por ejemplo:

$$
3x³ + 5x³ = 8x³
$$
$$
3x³ - 5x³ = -2x³
$$
En caso de que no tengan el mismo grado, se dejan expresados de la misma manera:

$$
2x³ - 5x²
$$
#### Producto

En este caso se multiplicará el coeficiente y se sumarán los exponentes, por ejemplo:

$$
4x³ · (-5x²) = -20x⁵
$$
#### Cociente

Se hará lo inverso que la multiplicación, dividiendo los coeficientes y restando los exponentes:

$$
\frac{4x³}{2x} = 2x²
$$

### Operaciones básicas entre polinomios

#### Suma y resta

Tendremos que sumar o restar los elementos que tengan el mismo grado, por ejemplo:

$$
2x³ - 3x² + 4x - 6 + 5x⁴ - 2x³ - 5x² - 3x + 16 = 5x⁴ -8x² +x + 10
$$
#### Producto

Tendremos que multiplicar todos los términos de la primera expresión por los de la segunda expresión, por ejemplo:

$$
(7x^4 - 5x² + 3x - 8) · 2x³ = 14x⁷ - 10x⁵ + 6x⁴ - 16x³
$$
Si se multiplica por un polinomio, tendríamos que hacer exactamente lo mismo, pero para el resto de términos del polinomio:

![[Pasted image 20251022191918.png]]

#### Cociente

En este caso es muy parecido a la división entre números normales, solo que tendremos que usar los términos del polinomio.

Se tendrá que seguir los siguientes pasos:

$$
\frac{6x⁴ - 27x³ + 15x² - 48}{2x² -3x +4}
$$

1) Se divide el término de mayor grado del dividendo, por el término de mayor grado del divisor.

$$
\frac{6x⁴}{2x²} = 3x²
$$

2) A continuación, multiplicamos el divisor por el monomio obtenido:

$$
(2x² - 3x + 4) · 3x² = 6x⁴ - 9x³ + 12x²
$$
	Posteriormente, tendremos que hacer la resta del dividendo:
	
	![[Pasted image 20251022192701.png]]
	
3) Ahora con lo que ha quedado como dividendo y divisor, seguimos haciendo la división.

![[Pasted image 20251022192801.png]]

4) Seguimos este proceso de manera sucesiva hasta llegar al último elemento, que puede ser resto 0, o no, al igual que una división normal.

![[Pasted image 20251022192847.png]]

También podemos afirmar que el polinomio está formado por el producto del divisor y dividendo, por ejemplo:

$$
6x⁴ - 27x³ + 15x² - 48 = (2x² - 3x + 4) · (3x² - 9x - 12)
$$
En caso de que el resto no fuese cero, indicaríamos al final el resultado de la manera anterior, pero sumando el residuo:

$$
6x⁴ - 27x³ + 15x² + 3x - 48 = (2x² - 3x + 4) · (3x² - 9x - 12) + 3x
$$
#### Fracciones algebraicas

Podemos afirmar que dos fracciones algebraicas son equivalentes si:

$$
\frac{a(x)}{b(x)} = \frac{p(x)}{q(x)} \implies a(x) · q(x) = b(x) · p(x)
$$
También podemos afirmar que si dividimos una fracción algebraica por el mismo polinomio, la fracción resultante es equivalente a la inicial. Siendo este proceso denominado simplificación.

![[Pasted image 20251022194923.png]]

##### Producto y cociente de fracciones algebraicas

Se siguen exactamente las mismas reglas que sumando y restando fracciones numéricas.

$$
\frac{3x - 2}{2x² + 3} · \frac{7x + 1}{2x + 2} = \frac{(3x - 2 ) · (7x + 1)} {(2x² + 3) · (2x + 2)} = \frac{21x² -11x - 2}{4x³ + 4x² + 6x + 6}
$$
$$
\frac{3x - 2}{2x² + 3} : \frac{7x + 1}{2x + 2} = \frac{(3x - 2 ) · (2x +2)} {(2x² + 3) · (7x + 1)} = \frac{6x² +2x - 4}{14x³ + 2x² + 21x + 3}
$$

##### Suma y resta de fracciones algebraicas

Se siguen las mismas reglas que para sumas y restas de fracciones numéricas.

Si tienen el mismo denominador, se deja el denominador común y se suman o restan los numeradores.

Si no tienen el mismo denominador, tendremos que buscar el MCM de los denominadores, y posteriormente, dividirlo entre el denominador, y multiplicar por el numerador.

$$
\frac{3x - 4}{x² + 5x + 6} + \frac{5x - 2}{x² + 3x + 2}
$$
$$
x² + 5x + 6 = (x+2)·(x+3)
$$
$$
x² + 3x + 2 = (x +1)·(x+2)
$$
$$
MCM = (x+1)(x+2)(x+3) = x³ + 6x² + 11x + 6
$$
$$
\frac{3x - 4}{x² + 5x + 6} = \frac{3x² -x - 4}{x³ + 6x² + 11x + 6}
$$
$$
\frac{5x - 2}{x² + 3x + 2} = \frac{5x² + 13x -6}{x³ + 6x² + 11x + 6}
$$

### Regla de Ruffini

La regla de Ruffini es un procedimiento que nos permite hacer de manera sencilla la división entre dos polinomios cuando el divisor es un polinomio de grado 1 tal que su coeficiente de grado 1 es también 1 y el término independiente es un número entero.

Por ejemplo, si queremos hacer:

$$
\frac{(5x³ - 4x² + 5x - 1)}{x-2}
$$
![[Pasted image 20251023181337.png]]

Tendríamos que hacer lo siguiente:

1) Usamos el -2, y lo cambiamos de signo.
2) Bajamos el primer factor.
3) Multiplicamos el -2 por el 5, dando 10.
4) Posteriormente, sumamos -4 y 10, dando 6.
5) Multiplicaremos 6 por 2, y nos dará 12.
6) Sumaremos 12 y 5, y dará 17.
7) Posteriormente, multiplicamos por 2, y nos dará 34.
8) Sumamos 34 y -1 y nos dará 33.

Este 33 es el resto de la división, por lo tanto podremos afirmar que:

$$
\frac{(5x³ - 4x² + 5x - 1)}{x-2} = (5x² + 6x + 17) · (x-2) + 33
$$
