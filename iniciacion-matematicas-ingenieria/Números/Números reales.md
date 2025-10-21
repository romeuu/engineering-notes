[[Iniciacion Matematicas Ingenieria]]

- [[#Potencias|Potencias]]
	- [[#Potencias#Raíces|Raíces]]
		- [[#Raíces#Raíz cuadrada|Raíz cuadrada]]
		- [[#Raíces#Raíz cúbica|Raíz cúbica]]
		- [[#Raíces#Otras raíces|Otras raíces]]
		- [[#Raíces#Propiedades potencias y raíces|Propiedades potencias y raíces]]
			- [[#Propiedades potencias y raíces#Potencia de exponente 1|Potencia de exponente 1]]
			- [[#Propiedades potencias y raíces#Producto de potencias de la misma base|Producto de potencias de la misma base]]
			- [[#Propiedades potencias y raíces#Cociente de potencias de la misma base|Cociente de potencias de la misma base]]
			- [[#Propiedades potencias y raíces#Potencia de exponente 0|Potencia de exponente 0]]
			- [[#Propiedades potencias y raíces#Potencia de una potencia|Potencia de una potencia]]
			- [[#Propiedades potencias y raíces#Producto de potencias con el mismo exponente|Producto de potencias con el mismo exponente]]
			- [[#Propiedades potencias y raíces#Cociente de potencias con el mismo exponente|Cociente de potencias con el mismo exponente]]
		- [[#Raíces#Racionalización de raíces|Racionalización de raíces]]
- [[#✍️ Ejercicios resueltos|✍️ Ejercicios resueltos]]
- [[#✅ Resumen final|✅ Resumen final]]


## Potencias

Una potencia es el conjunto de multiplicaciones con los mismos factores. Por ejemplo:

$$
7 * 7 * 7 * 7 * 7 = 7⁵
$$
Hay dos partes en una potencia, la base y el exponente:
- **Base**: Es el número que se multiplica varias veces.
- **Exponente**: Es el número de veces que se repite la base.

Cuando la base es negativa, hay que ponerla entre paréntesis ya que afecta a la base y al signo, ya que si no la operación sería distinta:

$$
(-3)⁴ = (-3) * (-3) * (-3) * (-3)
$$
$$
-3⁴ = -3 * 3 * 3 * 3
$$
Si el **signo de la base** es positivo, el resultado, siempre será **positivo**. Si es **negativo** y es **par**, será positivo, si es **impar**, negativo.

La potencia de una fracción es igual a otra fracción con el mismo numerador y denominador, pero elevados al exponente de la potencia. Por ejemplo:

$$
\left( \frac{7}{5} \right) = \frac{7³}{5³} = \frac{343}{125}
$$
Además, se pueden definir potencias con exponentes negativos, que es igual al inverso de la misma potencia con exponente positivo. Por ejemplo:

$$
\left( \frac{7}{9} \right)^{-6} = \frac{1}{(\frac{7}{9})^{6}}
$$
o también:

$$
6^{-1} = \frac{1}{6}
$$


### Raíces

Del mismo que la diferencia es la operación opuesta a la suma, y la división es la operación opuesta a la multiplicación, la radicación es la operación opuesta a la potenciación. Los tipos más importantes de radicación son:

#### Raíz cuadrada

Se trata de la operación opuesta a *elevar al cuadrado*. Se usa el signo √, o signo radical, con el número en el interior. Por ejemplo, como 5 al cuadrado es 25, entonces, la raíz cuadrada de 25 es igual a 5.

$$
\sqrt{ 25 } = 5
$$
$$
\sqrt{ 49 } = 7
$$

#### Raíz cúbica

Es la operación opuesta a *elevar al cubo*. Se usa el signo √ con un 3 como índice. Por ejemplo, como 5 al cubo es igual a 125 podemos decir que la raíz cúbica de 125 es 5.

$$
\sqrt[3]{125} = 5
$$

#### Otras raíces

De manera similar a la raíz cúbica, se pueden hacer raíces de diferentes índices. Por ejemplo:

La raíz de índice 4, la raíz cuarta, de 625 es 5.
La raíz de índice 5, la raíz quinta, de 32 es 2.

$$
\sqrt[4]{625} = 5
$$
$$
\sqrt[5]{32} = 2
$$

En el caso de **números negativos, se tiene que tener en cuenta que no es posible calcular la raíz del índice par.** Por ejemplo, la expresión raíz cuadrada de -4 es incorrecta porque no hay ningún número entero cuyo cuadrado sea 4; en general, no hay ningún número cuyo cuadrado sea un número negativo.

$$
\sqrt{ -4 } 
$$
En el caso de los números fraccionarios, su raíz se calcula:

$$
^\sqrt{ \frac{16}{25} } = \frac{4}{5}
$$
Ya que: $$ \left( \frac{4}{5} \right)^{2}  = \frac{16}{25} $$
En todo caso, **la raíz de una fracción siempre se puede expresar como una fracción de raíces**. Por ejemplo:

$$
\sqrt[3]{ \frac{27}{125} } = \frac{\sqrt[3]{ 27 }}{\sqrt[3]{ 125 }} = \frac{3}{5}
$$

Toda raíz se puede expresar también como una **potencia con exponente un número fraccionario igual al inverso del índice.** Por ejemplo:

$$
\sqrt{ 16 } = 16 ^ \frac{1}{2}
$$

$$
\sqrt[3]{27} = 27 ^ \frac{1}{3}
$$

De este modo, se puede expresar conjuntamente la raíz de una potencia. Por ejemplo: 

$$
\sqrt[3]{ 27 ^2 } = 27 ^ \frac{2}{3}
$$
Es decir, la raíz de una potencia es igual a una potencia con el exponente que es la fracción con numerador de la potencia y denominador del índice de la raíz. Otro ejemplo:

$$
\sqrt[4]{ \frac{16}{81} ^ {-3} } = \left( \frac{16}{81} \right)^{-\frac{3}{4}}
$$

#### Propiedades potencias y raíces

Para simplificar los cálculos con potencias y raíces es útil usar estas propiedades:

##### Potencia de exponente 1

El resultado de una potencia de exponente 1 es igual a la base. Por ejemplo:

$$
a^1 = a
$$

$$
5^{1} = 5 \: o \: (-3)^{-1} = -3
$$
##### Producto de potencias de la misma base

Para **multiplicar potencias con la misma base**, basta con **sumar los exponentes** dejando la base sin modificaciones:

$$
a^p * a^q = a ^ {p+q}
$$
$$
3^{4} * 3 ^ {2} = 3^{6}
$$
$$
\left( \frac{8}{81} \right)^{\frac{5}{2}} * \left( \frac{8}{81} \right)^{\frac{11}{4}} = \left(\frac{8}{81} \right) ^ {\frac{21}{4}} 
$$

##### Cociente de potencias de la misma base

Así mismo, para **dividir potencias de la misma base**, deberemos **restar los exponentes** y mantener la base sin modificaciones:

$$
a^p : a^q = a ^ {p-q}
$$
$$
7^{6} : 7^{4} = 7^{2}
$$
$$
\left( \frac{8}{81} \right)^{\frac{5}{2}} : \left( \frac{8}{81} \right)^{\frac{11}{4}} = \left(\frac{8}{81} \right) ^ {-\frac{1}{4}} 
$$

##### Potencia de exponente 0

Cualquier potencia (con base diferente a 0) de exponente 0 resulta siempre igual a 1.

$$
a^{0} = 1
$$
$$
9^{0} = 1
$$

##### Potencia de una potencia

El resultado de **elevar una potencia cualquiera a otro exponente** es igual a una potencia que tiene por **base la base de la potencia**, y el **exponente** de la cual **es el producto de exponentes**.


$$
(a^{p})^{q} = a^{p*q}
$$
$$
(5^{4}) ^ {3} = 5^{12}
$$
$$
\left( \left( \frac{64}{729} \right)^{\frac{7}{3}} \right) ^ {\frac{3}{2}} = \left( \frac{64}{729} \right) ^ {\frac{7}{2} * \frac{3}{2}} = \left( \frac{64}{729} \right) ^ \frac{21}{6}
$$

##### Producto de potencias con el mismo exponente

El resultado de **multiplicar varias potencias con el mismo exponente** es igual a una potencia la **base de la cual es el producto de bases** y el **exponente de la cual es el exponente común.**

$$
a^{p} * b^{p} = ({a * b})^{p}
$$
$$
8^{3} * 5^{3} = (8 * 5)^{3} = 40^{3}
$$
$$
\left( \frac{8}{81} \right)^{\frac{5}{2}} * \left( \frac{25}{4} \right) ^ {\frac{5}{2}} = \left( \frac{200}{324} \right) ^ {\frac{5}{2}}
$$

##### Cociente de potencias con el mismo exponente

El resultado de **dividir dos potencias con el mismo exponente** es igual a una potencia la **base de la cual es el cociente de bases** y el **exponente de la cual es el exponente común**.

$$
a^{p} : b^{p} = (a:b)^{p}
$$
$$
12^{5} : 3^{5} = (12:3)^{5} = 4^{5}
$$
$$
\left( \frac{8}{81} \right)^{\frac{5}{2}} : \left( \frac{25}{4} \right)^{\frac{5}{2}} = \left( \frac{32}{2025} \right)^{\frac{5}{2}}
$$

Se tiene que tener en cuenta que estas propiedades son correctas siempre que a, b, p y q sean **números racionales correctos** para la operación que se tiene que hacer. Por ejemplo, en el caso de la potencia de exponente 0, la base no puede ser 0; en el caso de los exponentes, sabemos que no pueden tener el denominador par si la base es negativa.

> [!DANGER] Atención
> No es lo mismo decir que el producto de potencias es igual a la potencia de la suma, que la suma de potencias es igual a la potencia del producto (esto último es falso). Es decir, no es cierto que:
> $$
> a^{p} + a^{q} = a^{p*q}
> $$

#### Racionalización de raíces

No es usual dejar una fracción con raíces en el denominador. Por eso, es habitual eliminarlas siempre que sea posible. Este proceso se llama racionalización de la fracción. Para conseguirlo, **tendremos que multiplicar el numerador y denominador por alguna expresión que permita eliminar las raíces.**

Por ejemplo, si tenemos esta expresión:

$$
\frac{1}{\sqrt{ 3 }} = \frac{1 * \sqrt{ 3 }}{ \sqrt{ 3 } * \sqrt{ 3 }} = \frac{\sqrt{ 3 }}{ (\sqrt{ 3 } ) ^ 2} = \frac{\sqrt{ 3 }}{3}
$$

En muchos casos, podremos encontrar una suma o resta de raíces en el denominador. En estos casos tenemos que multiplicar el denominador y el numerador por la operación opuesta del denominador.

$$
\frac{4}{(\sqrt{ 3 } - \sqrt{ 5 })} = \frac{4 * (\sqrt{ 3 } + \sqrt{ 5 })}{(\sqrt{ 3 } - \sqrt{ 5 }) *  (\sqrt{ 3 } + \sqrt{ 5 })} = \frac{(4 * (\sqrt{ 3} + \sqrt{ 5 }))}{3-5} = -2 * (\sqrt{ 3 } + \sqrt{ 5 })
$$




## ✍️ Ejercicios resueltos

---

## ✅ Resumen final

# Resumen: Potencias y Raíces

## Potencias

Una **potencia** es una multiplicación repetida de la misma base.

- **Base**: número que se multiplica.  
- **Exponente**: número de veces que se repite la base.  

El signo depende de la base y de si el exponente es **par** (resultado positivo) o **impar** (resultado negativo).  

También existen potencias con **fracciones** y con **exponentes negativos** (inversos).  

---

## Raíces

La **radicación** es la operación inversa de la potenciación.

- **Raíz cuadrada**: opuesta a elevar al cuadrado.  
- **Raíz cúbica**: opuesta a elevar al cubo.  
- **Raíces de mayor índice** siguen el mismo principio.  
- No existen raíces de índice par de números negativos.  
- Las raíces de fracciones se calculan aplicando la raíz a numerador y denominador.  
- Toda raíz se puede expresar como potencia con exponente fraccionario:  

$$
\sqrt[n]{a} = a^{\tfrac{1}{n}}
$$

---

## Propiedades de potencias y raíces

$$
a^1 = a
$$
$$
a^0 = 1 \quad (a \neq 0)
$$
$$
a^p \cdot a^q = a^{p+q}
$$
$$
\dfrac{a^p}{a^q} = a^{p-q}
$$
$$
(a^p)^q = a^{p \cdot q}
$$
$$
a^p \cdot b^p = (a \cdot b)^p
$$
$$
\dfrac{a^p}{b^p} = \left(\dfrac{a}{b}\right)^p
$$

⚠️ **Error común**: la suma de potencias **no equivale** a la potencia de la suma.  

---

## Racionalización

Consiste en eliminar raíces del denominador multiplicando por la expresión adecuada.

### Ejemplo 1: raíz simple  

$$
\dfrac{1}{\sqrt{3}} = \dfrac{\sqrt{3}}{\sqrt{3}} = \dfrac{\sqrt{3}}{3}
$$

---

### Ejemplo 2: suma de raíces (conjugado)

$$
\dfrac{1}{\sqrt{3} + \sqrt{2}}
$$

Multiplicamos por el conjugado $$(\sqrt{3} - \sqrt{2}):  


\dfrac{1}{\sqrt{3} + \sqrt{2}} \cdot \dfrac{\sqrt{3} - \sqrt{2}}{\sqrt{3} - \sqrt{2}}
= \dfrac{\sqrt{3} - \sqrt{2}}{(\sqrt{3})^2 - (\sqrt{2})^2}
= \dfrac{\sqrt{3} - \sqrt{2}}{3 - 2}
= \sqrt{3} - \sqrt{2}
$$

---

### Ejemplo 3: denominador con raíz cúbica  

$$
\dfrac{1}{\sqrt[3]{2}}
$$

Para eliminar la raíz cúbica necesitamos **elevar al cubo**, es decir, multiplicar por 
$$(\sqrt[3]{2^2}):  


\dfrac{1}{\sqrt[3]{2}} \cdot \dfrac{\sqrt[3]{2^2}}{\sqrt[3]{2^2}}
= \dfrac{\sqrt[3]{4}}{\sqrt[3]{8}}
= \dfrac{\sqrt[3]{4}}{2}

$$
