[[Iniciacion Matematicas Ingenieria]]

- [[#Matrices: tipo y elementos|Matrices: tipo y elementos]]
	- [[#Matrices: tipo y elementos#Matrices importantes|Matrices importantes]]

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
