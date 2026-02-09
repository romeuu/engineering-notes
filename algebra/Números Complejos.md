Asignatura: [[Álgebra]]

- [[#Representación de números complejos|Representación de números complejos]]
- [[#Representación gráfica|Representación gráfica]]
- [[#Operaciones con números complejos|Operaciones con números complejos]]
	- [[#Operaciones con números complejos#Suma y resta de complejos|Suma y resta de complejos]]
	- [[#Operaciones con números complejos#Producto de complejos|Producto de complejos]]



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

