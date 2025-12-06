[[Iniciacion Matematicas Ingenieria]], [[Calculo]]

- [[#Logaritmos|Logaritmos]]
	- [[#Logaritmos#Propiedades|Propiedades]]
- [[#Función logarítmica|Función logarítmica]]
	- [[#Función logarítmica#Propiedades|Propiedades]]


## Logaritmos

### Propiedades

$$
\log_{a}(a) = 1
$$
$$
\log_{a}1 = 0
$$
- El logaritmo del producto es igual a la suma de logaritmos, siempre que x e y sean mayores de 0.
$$
\log_{a}(x· y) = \log_{a}(x) + \log_{a}(y)
$$
- El logaritmo de una potencia es igual al producto del exponente por el logaritmo de la base, siempre que x sea mayor que 0:

$$
\log_{a}(x^{y}) = y·\log_{a}(x)
$$
- El logaritmo de un cociente es el logaritmo del numerador menos el logaritmo del denominador, siempre que x e y sean mayores que 0:

$$
\log_{a}\left( \frac{x}{y} \right) = \log_{a}(x) - \log_{a}(y)
$$
- Es posible relacionar dos logaritmos de bases diferentes, a y b, con esta fórmula, siempre que x sea mayor que 0:

$$
\log_{b}(x) = \frac{\log_{a}(x)}{\log_{a}(b)}
$$

## Función logarítmica

La función logarítmica de base *a*, con a > 0 y a distinto de 1, es la función inversa de la función exponencial de base a. Es decir:

$$
y = \log_{a}(x) \implies x = a^{y}
$$
Si la base de nuestro logaritmo es el número irracional *e*, se habla de **logaritmo neperiano** y se escribe ln. Es decir:
$$
\ln = \log_{e}
$$
$$
\log_{e} 10 = \ln{10}
$$

Por otra parte, si la base es 10, se habla simplemente de logaritmo, sin especificar la base, y se suele escribir directamente *log*.


### Propiedades

- El **dominio** de cualquier función logarítmica de base *a* es igual a todos los números reales positivos, es decir, (0,+∞).
- La **imagen** de cualquier función logarítmica de base *a* es igual a todos los números reales, es decir, (−∞,+∞).
- La gráfica de cualquier función logarítmica siempre pasa por el punto (1, 0).

En caso de que la base de a sea mayor que 1:

La función crece al aumentar la variable del logaritmo, es decir:
$$
\log_{a}(x_{1}) < \log_{a}(x_{2})
$$
Haciendo que crezca la función, siendo mayor cuanto menor es la base. Cuanto más cerca de 0 está la variable *x*, menor es el valor de la imagen *y*. Por eso se dice que la función  log(x) tiende a −∞ cuando la x tiende a 0.


En caso de que la base de a sea menor que 1, la función decrecerá al aumentar la variable. Este decrecimiento será mayor cuanto mayor sea la base. Además, cuanto más cerca de 0 esté la variable *x*, mayor será el valor de la imagen y. Por eso se dice que log(x) tiende a +∞ cuando la x tiende a 0.

![[Pasted image 20251205230716.png]]

## Ecuaciones logarítmicas

No hay una forma estándar de resolver este tipo de ecuaciones, por lo tanto, deberemos utilizar las propiedades logarítmicas y agrupar términos hasta que nos quede una ecuación linear o cuadrática.

$$
2\log(x) - \log(x-16) = 2
$$
$$
2\log(x) = \log(x²)
$$
$$
\log(x²) - \log(x-16) = 2
$$
$$
\log(x²) - \log(x-16) \implies \log\left( \frac{x²}{x-16} \right)
$$
$$
\log\left( \frac{x²}{x-16} \right) = 2
$$
$$
\log\left( \frac{x²}{x-16} \right) = \log(100)
$$
$$
\frac{x²}{x-16} = 100
$$
$$
x² = 100x - 1600
$$
$$
x² - 100x + 1600 = 0
$$
$$
x=20
$$
$$
x=80
$$
Al terminar y encontrar las soluciones, deberemos comprobar que ambos valores se ajustan a nuestra ecuación logarítmica.

También podemos encontrarnos sistemas de ecuaciones logarítmicas:

$$
\begin{cases}
x+y = 65 \\
\log(x) + \log(y) = 3
\end{cases}
$$
Como la primera ecuación es lineal, convertiremos la ecuación logarítmica en lineal de la siguiente manera:

$$
\log(a·b) = \log(a) + \log(b) \implies \log(x·y) = \log(1000)
$$
$$
\begin{cases}
x+y=65 \\
x·y = 1000
\end{cases}
$$
$$
(x,y) = (40,25)
$$
$$
(x,y) = (25,40)
$$
## Resumen

- $\log(\text{algo})$: Ese "algo" debe ser $>0$.
- $\log(x^2)$: El dominio es todo $\mathbb{R}$ menos el 0 (porque el negativo al cuadrado se hace positivo).

 - Si tienes logaritmo a ambos lados ($\log A = \log B$), tacha los logs ($A=B$).
- Comprueba **SIEMPRE** las soluciones finales. Si alguna hace negativo un logaritmo original, **se tacha**.