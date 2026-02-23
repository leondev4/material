# 📄 Cheat Sheet: Funciones, Dominios y Rangos
> **Guía maestra para análisis de funciones y comportamiento gráfico**

---

## 1. Tabla Comparativa General

| Tipo de Función | Dominio (Eje $x$) | Rango (Eje $y$) | Punto Crave |
| :--- | :--- | :--- | :--- |
| **Polinómica Impar** | $\mathbb{R}$ | $\mathbb{R}$ | Sin restricciones. |
| **Polinómica Par** | $\mathbb{R}$ | $[k, \infty)$ o $(-\infty, k]$ | El vértice define el rango. |
| **Racional** | $\mathbb{R} \setminus \{ \text{raíces del den.} \}$ | $\mathbb{R} \setminus \{ \text{A. Horizontal} \}$ | Presencia de asíntotas. |
| **Irracional** | Radicando $\ge 0$ | Normalmente $[k, \infty)$ | Inicia en el eje $y$ en el valor $k$. |
| **Valor Absoluto**| $\mathbb{R}$ | $[k, \infty)$ o $(-\infty, k]$ | Gráfica en forma de "V". |

---

## 2. Análisis Profundo del Rango ($R_f$)

El rango son todos los valores que la función "alcanza" en el eje vertical.

### A. En Funciones Racionales (Asíntotas)
El rango suele ser todos los reales excepto la **Asíntota Horizontal**.
* **Regla de Grados:**
    1. **Grados Iguales:** $f(x) = \frac{ax^n}{bx^n} \rightarrow$ Rango: $\mathbb{R} \setminus \{ \frac{a}{b} \}$.
    2. **Denominador Mayor:** $f(x) = \frac{x}{x^2} \rightarrow$ Rango: $\mathbb{R} \setminus \{ 0 \}$.



### B. En Funciones Cuadráticas y Valor Absoluto
Dependen del vértice $(h, k)$. El valor de **$k$** es el límite del rango.
* **Si abre hacia arriba ($+$):** $R_f = [k, \infty)$.
* **Si abre hacia abajo ($-$):** $R_f = (-\infty, k]$.
* *Ejemplo:* $f(x) = -|x - 2| + 5 \rightarrow$ Rango: $(-\infty, 5]$.



### C. En Funciones Irracionales (Raíces)
Para $f(x) = \sqrt{g(x)} + k$:
* El valor mínimo de una raíz cuadrada es $0$. Por lo tanto, el rango empieza en el número que esté sumando afuera ($k$).
* *Ejemplo:* $f(x) = \sqrt{x + 3} - 2 \rightarrow$ Rango: $[-2, \infty)$.



---

## 3. Guía Rápida de Dominios ($D_f$)

### 🚫 Restricción 1: Denominador $\neq 0$
* **Problema:** La división por cero no existe.
* **Solución:** Despeja $x$ en el denominador e ignora ese valor.
* *Ejemplo:* $\frac{5}{x+4} \rightarrow x+4=0 \rightarrow x=-4$. **Dom:** $\mathbb{R} \setminus \{-4\}$.

### ❄️ Restricción 2: Raíz Par $\ge 0$
* **Problema:** No hay raíces cuadradas de números negativos en los reales.
* **Solución:** Resuelve la inecuación del interior.
* *Ejemplo:* $\sqrt{7-x} \rightarrow 7-x \ge 0 \rightarrow 7 \ge x$. **Dom:** $(-\infty, 7]$.

---

## 4. Ejemplo Maestro Combinado
**Función:** $f(x) = \frac{2x - 10}{x + 5}$

1. **Dominio:** $x+5 = 0 \Rightarrow x = -5$. 
   * **$D_f = \mathbb{R} \setminus \{-5\}$**
2. **Asíntota Horizontal:** Cociente de coeficientes $\frac{2}{1} = 2$.
   * **A.H en $y = 2$**
3. **Rango:** Excluimos la asíntota horizontal.
   * **$R_f = \mathbb{R} \setminus \{ 2 \}$**