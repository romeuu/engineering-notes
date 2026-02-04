5[[Iniciacion Matematicas Ingenieria]], [[Calculo]]

- [[#Definición|Definición]]
- [[#Tabla de integrales inmediatas|Tabla de integrales inmediatas]]
- [[#Reglas de cálculo|Reglas de cálculo]]
	- [[#Reglas de cálculo#Suma y resta|Suma y resta]]
	- [[#Reglas de cálculo#Producto|Producto]]
	- [[#Reglas de cálculo#Igualdad entre función e integral|Igualdad entre función e integral]]
	- [[#Reglas de cálculo#Regla de la cadena|Regla de la cadena]]
	- [[#Reglas de cálculo#Tabla de integrales casi inmediatas|Tabla de integrales casi inmediatas]]
- [[#Métodos de integración|Métodos de integración]]
	- [[#Métodos de integración#Método de sustitución o cambio de variable|Método de sustitución o cambio de variable]]
	- [[#Métodos de integración#Integración por partes|Integración por partes]]

## Definición

La integración es la operación opuesta a la derivación, siendo la función resultante una función **primitiva** de $f(x)$.

Si $f(x)$ es la derivada de $F(x)$, $F(x)$ es una primitiva de $f(x)$.

El conjunto de todas las primitivas de una función $f(x)$ se denomina **integral indefinida** o simplemente **integral** de la función $f(x)$.

$$
\int f(x)dx
$$
$$
\int(3x² + 5)dx = x³ + 5x + C
$$
## Tabla de integrales inmediatas

![[Pasted image 20260102192021.png]]

## Reglas de cálculo

### Suma y resta

La integral de la suma (o resta) de funciones es igual a la suma (o resta) de las integrales de las funciones.

$$
\int[f(x) \pm g(x)] = \int f(x)dx \pm \int g(x)dx
$$

### Producto

La integral del producto de un número por una función es igual al producto del número por la integral de la función.

$$
\int k · f(x) dx = k · \int f(x)dx
$$

### Igualdad entre función e integral

Si:
$$
g(x) = \int f(x)dx
$$
Entonces:

$$
g'(x) = f(x)
$$

### Regla de la cadena

$$
\int f'(g(x)) · g'(x)dx = f(g(x)) + C
$$

### Tabla de integrales casi inmediatas

![[Pasted image 20260102192617.png]]

## Métodos de integración

### Método de sustitución o cambio de variable

Consiste en convertir una función en otra más sencilla de integrar.

![[Pasted image 20260103125814.png]]

![[Pasted image 20260103125837.png]]

![[Pasted image 20260103125850.png]]

### Integración por partes

Para integrar por partes, usaremos variables como $u$ en lugar de $f(x)$ y $v$ en lugar de $g(x)$, de manera que se escribe:

$$
\int u·dv = u·v - \int v·du
$$
El orden que seguiremos para definir la función $u$ será: funciones logarítmicas, funciones potencia, funciones trigonométricas, y exponenciales.

## Integral definida. Regla de Barrow.

La integral definida nace de la necesidad de calcular el área cerrada por una función y el eje X en un cierto intervalo.

### Regla de Barrow

Si $f(x)$ es una función continua en $[a,b]$, y $F(x)$ es una primitiva cualquiera de $f(x)$:

$$
\int^b_{a} f(x)dx = F(b) - F(a)
$$
Podríamos eligir la primitiva que queramos, pero la elegiremos habitualmente con $C=0$ porque es más sencilla.

![[Pasted image 20260103181647.png]]

