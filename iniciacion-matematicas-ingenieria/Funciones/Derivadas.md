[[Iniciacion Matematicas Ingenieria]], [[Calculo]]

- [[#Derivada de una función|Derivada de una función]]
	- [[#Derivada de una función#Definición|Definición]]
		- [[#Definición#Tabla de funciones derivadas|Tabla de funciones derivadas]]
	- [[#Derivada de una función#Reglas de cálculo|Reglas de cálculo]]
		- [[#Reglas de cálculo#Derivada de una suma y resta|Derivada de una suma y resta]]
		- [[#Reglas de cálculo#Derivada de un producto|Derivada de un producto]]
			- [[#Derivada de un producto#Función polinómica|Función polinómica]]
			- [[#Derivada de un producto#Función no polinómica|Función no polinómica]]
		- [[#Reglas de cálculo#Derivada de cociente|Derivada de cociente]]
		- [[#Reglas de cálculo#Derivada de composición|Derivada de composición]]
		- [[#Reglas de cálculo#Derivada de una potencia|Derivada de una potencia]]


## Derivada de una función
### Definición

Al calcular la derivada de una función $f(x)$, se obtiene una nueva función en todos los puntos de su dominio.

Esta nueva función se llama **función derivada de $f(x)$**, se designa por $f'(x)$ y hace corresponder a cada punto del dominio el valor de la derivada de la función $f$ en este punto.

#### Tabla de funciones derivadas

![[Pasted image 20251218191505.png]]

### Reglas de cálculo

#### Derivada de una suma y resta

$$
(f(x) \pm g(x))' = f'(x) \pm g'(x)
$$

Por ejemplo, si queremos derivar la siguiente suma/resta de funciones:
$$
f(x) = x^3
$$
$$
g(x) = x²
$$
$$
(f(x) + g(x))' = f'(x) + g'(x) = 3x² + 2x
$$
$$
(f(x) - g(x))' = f'(x) - g'(x) = 3x²-2x
$$

#### Derivada de un producto

##### Función polinómica

$$
(f(x) · g(x))' = f'(x) · g(x) + f(x) · g'(x)
$$
$$
h(x) = 3x⁵
$$
$$
h'(x) = 0 · x⁵ + 3·5x⁴ = 15x⁴
$$

##### Función no polinómica

$$
f(x) = \cos(x)
$$
$$
g(x) = \sin(x)
$$
$$
h'(x) = f'(x) · g(x) + f(x) · g'(x) = -\sin(x) · \sin(x) + \cos(x) · \cos(x) = \cos²(x) - \sin²(x)
$$

#### Derivada de cociente

$$
h'(x) = \left( \frac{f(x)}{g(x)} \right)' = \frac{f'(x) · g(x) - f(x) · g'(x)}{g²(x)}
$$
![[Pasted image 20251218193544.png]]


#### Derivada de composición

$$
(f(g(x)))′ = f ′ (g(x)) ⋅ g ′ (x)
$$
o, equivalente,

$$
(f ○ g) ′ (x) = (f ′ ○ g)(x) ⋅ g ′ (x)
$$

![[Pasted image 20251218194323.png]]

#### Derivada de una potencia

$$
h'(x) = f(x)^{g(x)} · (g'(x) · \ln(f(x) ) + \frac{g(x)·f'(x)}{f(x)})
$$
![[Pasted image 20251218194627.png]]

