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

