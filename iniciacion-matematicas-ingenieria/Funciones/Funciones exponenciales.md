[[Iniciacion Matematicas Ingenieria]], [[Calculo]]

- [[#Propiedades|Propiedades]]


Las funciones exponenciales son de tipo:

$$
f(x) = a^x
$$
Donde *a* tiene que ser mayor que 0.

Será creciente en caso de que la base sea mayor que 1, mientras que será decreciente si se encuentra entre 0 y 1.

## Propiedades

- Siempre cortarán el punto (0,1), sin importar si es creciente o decreciente.
- El dominio de cualquier función exponencial son todos los números reales (−∞,+∞).
- La imagen de cualquier función exponencial de base distinta a 1, es desde (0,+∞).

En caso de que la función tenga una base mayor que 1:
- La función será creciente, siendo el crecimiento mayor cuanto mayor sea la base. Por otra parte, se puede saber si una función es mayor a otra comparando los exponentes.
- Cuanto menor es el variable del exponente, más se acerca a 0 el valor de la imagen *y*, aunque nunca llega a alcanzarse este valor.

En caso de que la función tenga una base menor que 1:
- La función será decreciente, siendo el decrecimiento mayor cuanto menor es la base. Además, si comparamos exponentes de  dos funciones, el que tenga el exponente más pequeño es mayor.
- Cuanto mayor es la variable *x*, más se acerca a 0 el valor de la imagen *y*, aunque no llega a alcanzarse este valor.

Si la base es 1 (a = 1): La función es constante, puesto que:
$$
1^x = 1 - \dots- = 1
$$
![[Pasted image 20251202212645.png]]

## Ecuaciones exponenciales

### Mismas bases

#### Caso 1

Si son operaciones de misma base, por ejemplo:

$$
2^{x+1} = 2²
$$
Podremos igualar ambos exponentes y obtener el resultado:

$$
x+1 =  2 \implies x = 1
$$

#### Caso 2

Por otra parte, podrían complicarse algo más, por ejemplo:

$$
7^x + 7^{x+1} + 7^{x+2} = 2793
$$
$$
7^x · (1 + 7¹ + 7²) = 2793 
$$
$$
7^x · 57 = 2793
$$
$$
7^x = \frac{2793}{57} = 49 = 7²
$$
$$
7^x = 7² \implies x =2
$$
En este caso, hemos tenido que sacar factor común con el 7 y operar.

#### Caso 3

$$
5^{x-1} = 2 + \frac{3}{5^{x-2}}
$$
En este caso, para deshacernos del denominador, tendríamos que multiplicar toda la expresión por este:

$$
5^{x-1} · 5^{x-2} = 2 · 5^{x-2} + 3
$$
Operamos con las potencias y pasamos todos los términos a la izquierda:

$$
5^{2x-3} - 2 · 5^{x-2} - 3 = 0
$$
Podremos deshacernos de las restas con la propiedad que nos indica que una resta de los exponentes de las potencias es igual a su cociente:

$$
5^{2x-3} = \frac{5^{2x}}{5³} = \frac{5^{2x}}{125}
$$
$$
5^{x-2} = \frac{5^x}{25}
$$
$$
\frac{5^{2x}}{125} - 2·\frac{5^x}{25} - 3 = 0
$$
$$
\frac{(5^x)²}{125} - \frac{2·5^x}{25} - 3 = 0
$$
$$\frac{z^2}{125} - \frac{2z}{25} - 3 = 0$$
$$
z^2 - (2z \cdot 5) - (3 \cdot 125) = 0
$$
$$z^2 - 10z - 375 = 0$$

$$
z=25
$$
$$
z = -15
$$
Descartamos el negativo y nos quedaría lo siguiente:

$$
5^x = 25 \implies x = 2
 $$
 
Del mismo modo, también podemos tener sistemas de ecuaciones exponenciales, en los que habría que resolver las ecuaciones de la misma manera que vimos anteriormente.

$$
\begin{cases}
5^x = 5^{y} · 625 \\
2^x · 2^{y} = 256
\end{cases}
$$
$$
5^x = 5^{y} · 5⁴ \implies 5^{x-y} = 5⁴
$$
$$
2^x · 2^{y} = 2⁸ \implies 2^{x+y} = 2⁸
$$
$$
\begin{cases}
x-y = 4 \\
x+y=8
\end{cases}
$$
Esto nos daría estas soluciones: $(x,y) = (6,2)$.

## Resumen

- **$e^x$**: En $x=1$, la altura es $\approx 2,7$.
- **$e^{x+a}$**: Se mueve a la **izquierda** $a$ unidades.
- **$e^x + a$**: Sube la **asíntota** a $y=a$.

- Si ves sumas ($2^x + 2^{x+1}$): **Factor común**.
- Si ves el doble de exponente ($3^{2x}$ y $3^x$): **Cambio de variable $z=3^x$** (Ecuación de 2º grado).
- **OJO:** Si te sale $3^x = 4$, **SÍ tiene solución** ($x = \log_3 4$). Solo es imposible si es igual a un negativo o cero.