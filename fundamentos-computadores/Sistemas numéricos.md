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