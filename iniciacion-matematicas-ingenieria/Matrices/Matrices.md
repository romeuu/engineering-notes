[[Iniciacion Matematicas Ingenieria]]

- [[#Matrices: tipo y elementos|Matrices: tipo y elementos]]
	- [[#Matrices: tipo y elementos#Matrices importantes|Matrices importantes]]
- [[#Operaciones básicas|Operaciones básicas]]
	- [[#Operaciones básicas#Suma y resta|Suma y resta]]
		- [[#Suma y resta#Propiedades de la suma de matrices|Propiedades de la suma de matrices]]
	- [[#Operaciones básicas#Producto por un escalar|Producto por un escalar]]
		- [[#Producto por un escalar#Propiedades del producto por un escalar|Propiedades del producto por un escalar]]
	- [[#Operaciones básicas#Producto de matrices|Producto de matrices]]
		- [[#Producto de matrices#Propiedades del producto de matrices|Propiedades del producto de matrices]]
- [[#Determinantes de una matriz|Determinantes de una matriz]]

## Matrices: tipo y elementos

Una matriz es un conjunto de números organizados en *m* filas y *n* columnas cerrados entre paréntesis.

Si una matriz tiene *m* filas y *n* columnas se dice que tiene dimensión *m x n*, o bien que es de orden (*m,n*).

$$
A = \begin{pmatrix}
1, 2, 3 \\
4,5,6
\end{pmatrix}
$$
En este caso A sería del orden (2,3), o tendría dimensión 2 x 3.

Para identificar elementos, se pondrá un subíndice en el que vaya seguido del nombre de la matriz, junto a los valores i (fila) y j (columna). Por ejemplo:

$$
a_{1,1} = 1
$$
El elemento 1, 1 sería el 1, ya que sería el primer elemento.

$$
a_{1,3} = 3
$$
Y por otra parte, el elemento de la fila 1 y columna 3, sería el 3.

Podremos afirmar que una matriz es **igual**, cuando todos los elementos sean iguales y ocupen las mismas posiciones.

### Matrices importantes

Existen varios tipos de matrices que tenemos que conocer:

- **Matriz cuadrada**: Es una matriz que tiene el mismo número de filas y columnas.
- **Matriz diagonal**: Es una matriz en la que la diagonal tiene valores distintos a 0, y el resto de elementos de la matriz son 0. 

$$
\begin{pmatrix}
1,0,0 \\
0,2,0 \\
0,0,4
\end{pmatrix}
$$
- **Matriz nula**: Es la matriz que tiene todos los números a 0.

$$
0_{mn} = \begin{pmatrix}
0,0,0 \\
0,0,0
\end{pmatrix}
$$
- **Matriz identidad**: Es la matriz diagonal en la que todos los elementos de la diagonal son 1. 

$$
I_{3} = \begin{pmatrix}
1,0,0 \\
0,1,0 \\
0,0,1
\end{pmatrix}
$$
$$
I_{2} = \begin{pmatrix}
1,0 \\
0,1
\end{pmatrix}
$$
- **Matriz triangular**: Es una matriz cuadrada en la que todos los elementos situados por debajo o por encima de la diagonal son 0. Si los elementos están por debajo de la diagonal, será una matriz **triangular superior**. En cambio, si los elementos que son 0 están por encima de la diagonal, sería **triangular inferior**.

$$
A = \begin{pmatrix}
-1,3,5 \\
0,-2,2 \\
0,0,8
\end{pmatrix}
$$
$$
B = \begin{pmatrix}
-1,0,0 \\
2,-2,0 \\
2,-7,8
\end{pmatrix}
$$
- **Matriz traspuesta**: La matriz traspuesta de una matriz A se denomina A elevado a T, y es la matriz que resulta de cambiar filas por columnas en la matriz A.

$$
A = \begin{pmatrix}
-1,3,5 \\
2,-2,2 \\
2,-7,8
\end{pmatrix}
$$
$$
A^T = \begin{pmatrix}
-1, 2,2 \\
3, -2,7 \\
5,2,8
\end{pmatrix}
$$
- **Matriz simétrica**: Es la que coincide con su matriz traspuesta.

$$
A = \begin{pmatrix}
-1,4,7 \\
4,-2,-1 \\
7,-1,8
\end{pmatrix}
$$

## Operaciones básicas

### Suma y resta

Dos matrices se pueden sumar o restar únicamente si sus dimensiones son las mismas. Para efectuar estas operaciones, tendremos que hacer lo siguiente:

$$
A + B = (a_{ij} ) + (b_{ij}) = (a_{ij} + b_{ij})
$$
$$
A - B = (a_{ij}) - (b_{ij}) = (a_{ij} - b_{ij})
$$
#### Propiedades de la suma de matrices

- **Conmutativa**: A + B = B + A
- **Asociativa**: A + B + C = A + (B + C) = (A + B) + C
- **Elemento neutro**: Hay una matriz, denominada elemento neutro, que sumada a cualquier otra matriz A de la misma dimensión, tiene como resultado siempre A. Esta matriz es la matriz nula.
- **Elemento opuesto**: Toda matriz tiene un elemento opuesto, que sumado con el original resulta el elemento neutro. El elemento opuesto de A es -A.

### Producto por un escalar

El producto de una matriz por un escalar (número real) siempre puede calcularse y consiste en multiplicar todos los elementos de la matriz por ese número.

$$
r · A = r · (a_{ij}) = (r · a_{ij})
$$
#### Propiedades del producto por un escalar

- **Conmutativa**: r · A = A · r
- **Asociativa**: 
$$
(r_{1} · r_{2}) · A = r_{1} · (r_{2} · A)
$$
- **Elemento neutro**: Hay un escalar, denominado elemento neutro, que multiplicado por cualquier matriz A tiene como resultado siempre A. Este es el número 1.
- **Distributiva**: en este caso hay dos tipos, escalar o matriz.

	Escalar:
$$
r· ( A + B) = r · A + r · B
$$
	O de matriz:
$$
(r_{1} + r_{2}) · A = r_{1} · A + r_{2} · A
$$

> [!NOTE] División de matriz
> Para dividir una matriz por un número, tiene que multiplicarse esa matriz por el inverso del número.


### Producto de matrices

Para multiplicar dos matrices, A y B, y obtener la matriz producto A · B, tiene que comprobarse que el número de columnas de la matriz A, coincida con el número de filas de la matriz B.

El producto resultante tendrá el mismo número de filas que la matriz A y el mismo número de columnas que B.

$$
(m · n)  · (n · r) = m ·r
$$
Para encontrar cada elemento de la matriz producto, tendremos que multiplicar odenadamente los elementos de la fila 1 de la matriz A (en verde) por los elementos de la columna 1 de la matriz B.

![[Pasted image 20251107200838.png]]

#### Propiedades del producto de matrices

- **Asociativa**: A · B · C = A · (B · C) = (A · B) · C
- **El elemento neeutro del producto de matrices cuadradas** es la matriz identidad I de n. Es decir, si A es una matriz cuadrada de dimensión n x n, se cumple:
$$
A · I_{n} = I_{n} · A = A
$$
- A veces (aunque no siempre), hay matrices cuadradas que tienen **elemento inverso**. Esta matriz, cuando existe, se denomina inversa. También se puede decir que la matriz es invertible. La matriz inversa de una matriz cuadrada de dimensión n x n A se indica como A elevado a -1.
$$
A · A^{-1} = I_{n}
$$
$$
A^{-1} · A = I_{n}
$$
- En general, el **producto de matrices NO es conmutativo**. Es decir, si A y B son dos matrices, cuando se pueden hacer los productos A · B y B · A, generalmente no son iguales, aunque puede darse el caso de que si.
$$
A · B \neq B · A
$$

## Determinantes de una matriz

Para cada matriz cuadrada puede definirse un número que nos sirve para determinar si la raíz es invertible, y si es así, para calcular la inversa de la matriz.

Se escribe como det(A) o |A|.

### Cálculo

#### Matriz 1x1

Es igual al número que compone la matriz.

$$
A = (3)
$$
$$
\det(A) = |3| = 3
$$
#### Matriz 2x2

Es igual al producto de los elementos de la diagonal menos el producto de los otros dos elementos.

$$
A= \begin{pmatrix}
1,-1 \\
2, 4
 \end{pmatrix} \implies \det(A) = 1 · 4 - (-1) · 2 = 6
$$
#### Matriz 3x3

![[Pasted image 20251107230833.png]]


#### Matrices 4x4

En este caso se tiene que descomponer el determinante. Elegimos una fila o columna y desarrollamos por esta. Por ejemplo, si elegimos la primera columna:

![[Pasted image 20251107232410.png]]
