[[Iniciacion Matematicas Ingenieria]], [[Calculo]]

- [[#Derivada de una función|Derivada de una función]]
	- [[#Derivada de una función#Definición|Definición]]
		- [[#Definición#Tabla de funciones derivadas|Tabla de funciones derivadas]]
	- [[#Derivada de una función#Reglas de cálculo|Reglas de cálculo]]
		- [[#Reglas de cálculo#Derivada de una suma y resta|Derivada de una suma y resta]]
		- [[#Reglas de cálculo#Derivada de un producto|Derivada de un producto]]
			- [[#Derivada de un producto#Función polinómica|Función polinómica]]
			- [[#Derivada de un producto#Función no polinómica|Función no polinómica]]
		- [[#Reglas de cálculo#Derivada de cociente|Derivada de cociente]]
		- [[#Reglas de cálculo#Derivada de composición|Derivada de composición]]
		- [[#Reglas de cálculo#Derivada de una potencia|Derivada de una potencia]]


## Derivada de una función
### Definición

Al calcular la derivada de una función $f(x)$, se obtiene una nueva función en todos los puntos de su dominio.

Esta nueva función se llama **función derivada de $f(x)$**, se designa por $f'(x)$ y hace corresponder a cada punto del dominio el valor de la derivada de la función $f$ en este punto.

#### Tabla de funciones derivadas

![[Pasted image 20251218191505.png]]

### Reglas de cálculo

#### Derivada de una suma y resta

$$
(f(x) \pm g(x))' = f'(x) \pm g'(x)
$$

Por ejemplo, si queremos derivar la siguiente suma/resta de funciones:
$$
f(x) = x^3
$$
$$
g(x) = x²
$$
$$
(f(x) + g(x))' = f'(x) + g'(x) = 3x² + 2x
$$
$$
(f(x) - g(x))' = f'(x) - g'(x) = 3x²-2x
$$

#### Derivada de un producto

##### Función polinómica

$$
(f(x) · g(x))' = f'(x) · g(x) + f(x) · g'(x)
$$
$$
h(x) = 3x⁵
$$
$$
h'(x) = 0 · x⁵ + 3·5x⁴ = 15x⁴
$$

##### Función no polinómica

$$
f(x) = \cos(x)
$$
$$
g(x) = \sin(x)
$$
$$
h'(x) = f'(x) · g(x) + f(x) · g'(x) = -\sin(x) · \sin(x) + \cos(x) · \cos(x) = \cos²(x) - \sin²(x)
$$

#### Derivada de cociente

$$
h'(x) = \left( \frac{f(x)}{g(x)} \right)' = \frac{f'(x) · g(x) - f(x) · g'(x)}{g²(x)}
$$
![[Pasted image 20251218193544.png]]


#### Derivada de composición

$$
(f(g(x)))′ = f ′ (g(x)) ⋅ g ′ (x)
$$
o, equivalente,

$$
(f ○ g) ′ (x) = (f ′ ○ g)(x) ⋅ g ′ (x)
$$

![[Pasted image 20251218194323.png]]

#### Derivada de una potencia

$$
h'(x) = f(x)^{g(x)} · (g'(x) · \ln(f(x) ) + \frac{g(x)·f'(x)}{f(x)})
$$
![[Pasted image 20251218194627.png]]

## Aplicaciones de la derivada

Entre las muchas aplicaciones importantes que tiene la derivada en el estudio de funciones, destacamos el hecho de identificar los intervalos de crecimiento y decrecimiento de una función, y los de concavidad y conexidad, imprescindibles a la hora de localizar los extremos (máximos y mínimos), además de los puntos de inflexión.

### Crecimiento y decrecimiento de una función

Si una función es creciente en un punto, la derivada de esta función en este punto es positiva. Además, cuanto más rápidamente crece la función, más grande es el valor de la derivada en el punto.

Si una función es decreciente en un punto, la derivada de esta función en este punto es negativa. Además, cuanto más rápidamente decrece la función, menor es el valor de la derivada en el punto.

![[Pasted image 20251218205420.png]]

### Máximos y mínimos de una función

Es posible determinar si un punto es un extremo derivando la función y resolviendo la ecuación que resulta de igualar la derivada a 0.

Tanto en el caso del máximo como en el del mínimo, la recta tangente en ellos es horizontal y, por lo tanto, con pendiente nula (es decir, igual a 0), y esto indica que la derivada de la función es 0 en estos puntos.

![[Pasted image 20251218205730.png]]

Ahora bien, ¿cómo se puede saber cuando un extremo es un máximo o un mínimo sin tener que estudiar la gráfica de la función?

Sí. Sólo hay que derivar la función otra vez. Para calcular la segunda derivada de la función, $f ′′$, se utilizan las reglas de derivación habituales. Una vez calculada la segunda derivada de la función, hay que estudiar el signo que toma al ser evaluada en el punto $x_{0}$ en cuestión. Entonces, la regla para determinar si la función presenta un máximo o mínimo en el punto $x_{0}$ de su dominio es la siguiente:

- En $f'(x_{0}) = 0$ y $f''(x_{0}) < 0$ el punto $(x_{0}, f(x_{0}))$ es un **máximo** de la función $f$.
- En $f'(x_{0}) = 0$ y $f''(x_{0}) > 0$ el punto $(x_{0}, f(x_{0}))$ es un **mínimo** de la función $f$.
- En $f''(x_{0}) = 0$ no se puede decir nada sobre si se trata de un máximo o un mínimo.

![[Pasted image 20251218210818.png]]

También se puede estudiar si un punto es máximo o mínimo revisando el crecimiento o decrecimiento de la función en un entorno de $x_{0}$, es decir, en puntos cercanos.

![[Pasted image 20251218210850.png]]


### Concavidad y convexidad de una función

Podemos afirmar que una función es **cóncava** en aquellos puntos en que su derivada segunda es negativa.

Así mismo, podemos afirmar que una función es **convexa** en aquellos puntos en que su derivada segunda es positiva.

![[Pasted image 20251218212832.png]]

Para calcular los puntos de inflexión de nuestra función, igualaremos la segunda derivada a 0, y resolveremos la ecuación.

En definitiva, para encontrar los intervalos de concavidad y convexidad de una función, hay que encontrar en primer lugar los valores $x$ de su dominio donde la segunda derivada de la función se anula (es decir, resolver $f ′′(x) = 0$) y los valores ̃$x$ en donde esta segunda derivada no existe, y estudiar posteriormente el signo de la segunda derivada en ellos. En particular, si la segunda derivada cambia de signo en un entorno de $x$, el punto $(x, f(x))$ es un punto de inflexión de la función $f(x)$.


## Problemas de optimización

## Preguntas comunes práctica

Cuando veas una letra (a, b, k...) sumando o restando sin $x$, es un número disfrazado.

- **Si SUMA o RESTA sola:** Su derivada es **0** (desaparece).
    - Ejemplo: $f(x) = \ln(x) + a \rightarrow f'(x) = \frac{1}{x}$ (La $a$ muere).

- **Si MULTIPLICA:** Se queda quieta esperando.
    - Ejemplo: $f(x) = k \cdot x^2 \rightarrow f'(x) = k \cdot 2x$.

2. Leer Gráficas de Derivadas $f'(x)$ (Preguntas 4 y 5)

¡Cuidado! Si el eje Y dice $f'(x)$, **NO estás viendo la forma de la función**, estás viendo su "velocidad".

- **Altura de la gráfica ($Y$) = Pendiente de la original ($m$).**
    
    - Si la gráfica está **por encima** del eje X ($+$) $\rightarrow$ La función original **SUBE** $\nearrow$.
        
    - Si la gráfica está **por debajo** del eje X ($-$) $\rightarrow$ La función original **BAJA** $\searrow$.
        
    - Si la gráfica **corta** al eje X ($0$) $\rightarrow$ La función original tiene un **MÁXIMO o MÍNIMO** (cima o valle).
        

> **Truco:** No mires si la línea de la derivada sube o baja, mira si es **positiva o negativa**.

3. Rectas Tangentes Paralelas (Pregunta 8)

La palabra "Paralela" en cálculo significa **"Igualar Derivada"**.

- Si te dicen: _"Busca $x$ para que la tangente sea paralela a $y = mx + n$ "_.
    
- **Fórmula:**
    
    $$f'(x) = m$$
    
    (Igualas tu derivada al número que acompaña a la $x$ en la recta).
    

4. El "Pico" del Valor Absoluto

Las funciones con valor absoluto $| \dots |$ tienen un punto débil: el vértice (la esquina de la V).

- **Regla:** Donde lo de dentro del valor absoluto vale **0**, hay un pico.
    
- **Consecuencia:** En los picos **NO existe la derivada** (es imposible apoyar una tangente estable).
    
    - Ejemplo: $|2x - 6|$ no es derivable en $x=3$.
        

5. Intersección de Pendientes

Si te preguntan "¿Dónde tienen estas dos funciones la misma pendiente?".

- Procedimiento: Deriva las dos por separado e IGUALAS los resultados.
    
    $$f'(x) = g'(x)$$