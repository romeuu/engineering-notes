
# 🧾 Chuleta LaTeX (Obsidian + MathJax)

## ℹ️ Sintaxis general

- Fórmula en línea: `$ ... $`  
  Ejemplo: `$f(x) = x^2$`  
- Fórmula en bloque centrado: `$$ ... $$`  
  Ejemplo:  
  ```markdown
$$
	lim_{x \to a} f(x)
$$
```
$$
  \lim_{x \to a} f(x)
  $$

## 🔢 Operaciones básicas

- Suma: `a + b`  
- Producto: `a \cdot b` → \( a \cdot b \)  
- Fracción: `\frac{a}{b}` → \( \frac{a}{b} \)  
- Potencias: `x^2`, `x^{n+1}` → \( x^2, x^{n+1} \)  
- Raíz cuadrada: `\sqrt{x}` → \( \sqrt{x} \)  
- Raíz n-ésima: `\sqrt[n]{x}` → \( \sqrt[n]{x} \)  

---

## ➗ Límites y derivadas

- Límite: `\lim_{x \to a} f(x)` → \( \lim_{x \to a} f(x) \)  
- Derivada: `f'(x)` o `\frac{df}{dx}` → \( \frac{df}{dx} \)  
- Derivada parcial: `\frac{\partial f}{\partial x}` → \( \frac{\partial f}{\partial x} \)  

---

## 🔁 Sumatorios e integrales

- Sumatorio: `\sum_{i=1}^{n} i` → \( \sum_{i=1}^{n} i \)  
- Integral: `\int_{a}^{b} f(x)\,dx` → \( \int_{a}^{b} f(x)\,dx \)  

---

## 🧮 Funciones matemáticas

- `\sin`, `\cos`, `\tan`, `\log`, `\ln`, `\exp`  
  Ejemplo: `\ln(x^2 + 1)` → \( \ln(x^2 + 1) \)  

---

## 🔤 Símbolos comunes

| Descripción       | Código          | Renderizado      |
|-------------------|-----------------|------------------|
| Infinito          | `\infty`        | \( \infty \)     |
| Aproximación      | `\approx`       | \( \approx \)    |
| Pertenece         | `\in`           | \( \in \)        |
| No pertenece      | `\notin`        | \( \notin \)     |
| Igualdad          | `=`             | \( = \)          |
| Diferente         | `\neq`          | \( \neq \)       |
| Mayor/menor       | `>`, `<`        | \( >, < \)       |
| Implicación       | `\Rightarrow`   | \( \Rightarrow \)|
| Bicondicional     | `\Leftrightarrow` | \( \Leftrightarrow \) |
| Conjunto vacío    | `\emptyset`     | \( \emptyset \)  |

---

## 🧩 Extras útiles

- Paréntesis grandes: `\left( ... \right)` → \( \left( \frac{a}{b} \right) \)  
- Texto dentro de fórmulas: `\text{...}` → \( \text{límite cuando } x \to 0 \)  
- Espacio extra: `\,` (pequeño), `\quad` (grande)  