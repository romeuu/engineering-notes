Asignatura: [[Fundamentos Computadores]]

- [[#Definición|Definición]]
- [[#Puerta AND|Puerta AND]]
- [[#Puerta OR|Puerta OR]]
- [[#Puerta NOT|Puerta NOT]]
- [[#Puerta XOR|Puerta XOR]]


## Definición

Una puerta lógica es un circuito digital que implementa una función lógica elemental. Son las piezas con las que construiremos circuitos más complejos.

## Puerta AND

Es una puerta que implementa el producto lógico.

Su símbolo es el siguiente:

![[Pasted image 20260211204220.png]]

Y su expresión algebraica es el producto de ambas entradas:

$$
a · b
$$
Además, tenemos su tabla de verdad, que nos permite ver el resultado de esta operación dependiendo de los valores de $a$ y $b$.

![[Pasted image 20260211205217.png]]

El número mínimo de entradas que tiene esta puerta es 2, pero puede tener más.

## Puerta OR

Esta puerta implementa la suma lógica.

Su símbolo es el siguiente:

![[Pasted image 20260212195120.png]]

Y su expresión algebraica es la suma de ambas entradas:

$$
a+b
$$

Su tabla de verdad es la siguiente:

![[Pasted image 20260212195447.png]]

También presenta aridad 2 ampliable, es decir, el mínimo son 2 entradas, pero puede tener más.

## Puerta NOT

Implementa la negación lógica, también llamado inversor.

Su símbolo es el siguiente:

![[Pasted image 20260212195559.png]]

Podemos observar un círculo, que normalmente indica negación.

Su expresión algebraica es la siguiente:

$$
a \to \bar{a}
$$

Su tabla de verdad es la siguiente:

![[Pasted image 20260212195838.png]]

Esta puerta tiene aridad 1 no ampliable, es decir, solo puede tener una entrada.

## Puerta XOR

Esta puerta implementa la suma exclusiva.

![[Pasted image 20260212195929.png]]

Su expresión algebraica es la siguiente:
$$
a \oplus b
$$

Y la tabla de verdad es exactamente igual que el OR menos en el caso de que los elementos sean iguales, que se convierte en 0:

![[Pasted image 20260212200121.png]]

Tiene aridad 2 no ampliable, es decir, se necesitan 2 entradas pero no puede haber más.
