
- [[#Pasar de binario a decimal|Pasar de binario a decimal]]
- [[#Pasar de decimal a binario|Pasar de decimal a binario]]
	- [[#Pasar de decimal a binario#División a la mitad|División a la mitad]]
	- [[#Pasar de decimal a binario#Tabla|Tabla]]
- [[#Complemento C2|Complemento C2]]
- [[#Hexadecimal|Hexadecimal]]
	- [[#Hexadecimal#Pasar de hexadecimal a binario|Pasar de hexadecimal a binario]]


## Pasar de binario a decimal

Tendremos que leer el número de derecha a izquierda, y cada número que tenga el número en binario, será un 2, que se multiplicará por 2 secuencialmente, es decir, la primera cifra tendrá un valor de 1, la segunda de 2, etc.

$$
11001 \implies 1 + 8 + 16 = 25
$$
$$
10001101 \implies 1 + 4 + 8 + 128 = 141
$$
$$
11100001 \implies 1 + 32 + 64 + 128 = 225
$$
$$
111111111 \implies 1 + 2 + 4 + 8 + 16 + 32 + 64 + 128 + 256 = 511
$$

## Pasar de decimal a binario

Existirían dos métodos principales para hacer esta conversión:

### División a la mitad

Tendremos que hacer la división escalonada de el número hasta llegar a 1. El resto de cada división nos dará un dígito de nuestro número en binario, poniendo siempre el número 1 al principio.

Por ejemplo, para el 34, veremos que el número binario es 100010.

![[Pasted image 20260204205331.png]]

### Tabla

Podemos poner una tabla también que nos ayuda a descomponer el número en sus factores, por ejemplo:

![[Pasted image 20260204205717.png]]

Este método está bien para números más pequeños.

## Complemento C2

A veces necesitamos representar números decimales en negativo, pero no existe el binario negativo, por lo tanto tenemos que encontrar una manera de que el ordenador entienda, por ejemplo, el número 5.

Para esto existe el complemento C2 que nos permite representar números negativos en binario invirtiéndolos.

Estos serían los pasos a seguir si queremos representar el $-5$:

- Escribimos el número que queremos escribir en binario sin el signo negativo, es decir, el $5$: $0101$.
- Invertimos este número en binario cambiando 0 por 1 y 1 por 0: $1010$.
- Sumamos 1 al resultado final: $1010 + 1$ = $1011$.

Esto haría que -5 en complemento 2 sea $1011$.

## Hexadecimal

Para hexadecimal tenemos esta tabla de conversión:

|**Decimal**|**Binario (4 bits)**|**Hexadecimal**|
|---|---|---|
|0-9|...|**0-9**|
|10|1010|**A**|
|11|1011|**B**|
|12|1100|**C**|
|13|1101|**D**|
|14|1110|**E**|
|15|1111|**F**|
Básicamente, a partir del número 10, necesitamos representar con letras hasta la F, que sería el 15.

Para pasar números binarios a HEX tenemos que hacer bloques de 4 bits para así obtener grupos representables.

$10111100101$ a HEX tendríamos 3 grupos:

$$
0101 \implies 5
$$
$$
1110 \implies 14 \implies E
$$
$$
101 \implies 5
$$

Por lo tanto, podemos afirmar que el número $10111100101$ en HEX es igual a $5E5$.

Otro ejemplo, sería el $11001111$, que nos daría dos subgrupos:

$$
1111 \implies 15 \implies F
$$
$$
1100 \implies 12 \implies C
$$
$$
11001111 \implies CF
$$

### Pasar de hexadecimal a binario

Si queremos convertir de hexadecimal a binario, simplemente tendremos que pasar el valor de cada cifra del número HEX a binario:

$$
3A
$$
$$
3 \implies 0011
$$
$$
A \implies 1010
$$
$$
3A = 00111010
$$
