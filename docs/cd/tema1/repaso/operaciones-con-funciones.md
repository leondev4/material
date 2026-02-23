# 📘 Resumen de Sesión: Operaciones con Funciones y Dominios

Este documento contiene las reglas y ejercicios vistos hoy sobre cómo combinar funciones y calcular sus dominios.

---

## 1. Operaciones Aritméticas
Para estas operaciones, el dominio es la **intersección** de los dominios de $f$ y $g$.

<!-- | Operación | Definición | Condición Especial |
| :--- | :--- | :--- |
| **Suma** | $(f + g)(x) = f(x) + g(x)$ | Ninguna |
| **Resta** | $(f - g)(x) = f(x) - g(x)$ | Ninguna |
| **Producto** | $(f \cdot g)(x) = f(x) \cdot g(x)$ | Ninguna |
| **División** | $(f / g)(x) = \frac{f(x)}{g(x)}$ | El denominador $g(x) \neq 0$ | -->

| Operación | Símbolo | Definición | Dominio |
| :--- | :--- | :--- | :--- |
| **Suma** | $(f + g)(x)$ | $f(x) + g(x)$ | Dom($f$) $\cap$ Dom($g$) |
| **Resta** | $(f - g)(x)$ | $f(x) - g(x)$ | Dom($f$) $\cap$ Dom($g$) |
| **Multiplicación** | $(f \cdot g)(x)$ | $f(x) \cdot g(x)$ | Dom($f$) $\cap$ Dom($g$) |
| **División** | $(f / g)(x)$ | $f(x) / g(x)$ | Dom($f$) $\cap$ Dom($g$) **pero** $g(x) \neq 0$ |

---

## 2. Composición de Funciones
La composición $(f \circ g)(x)$ consiste en evaluar una función dentro de otra.

**Fórmula:** $$(f \circ g)(x) = f(g(x))$$

### 🛠️ Cómo calcular el Dominio:
1.  **Restricción Interna:** $x$ debe ser aceptado por la función $g$.
2.  **Restricción Externa:** El resultado de $g(x)$ debe ser aceptado por la función $f$.

---

## 3. "Checklist" de Restricciones (Zonas de Peligro)

* **Raíces de índice par ($\sqrt{x}$):** Lo de adentro debe ser $\geq 0$.
* **Fracciones ($\frac{1}{x}$):** El denominador debe ser $\neq 0$.

---

## 4. Ejercicios de Clase

### A. La Raíz en el Denominador
**Función:** $h(x) = \frac{6 - x}{\sqrt{x}}$  
* **Análisis:** $x$ debe ser $\geq 0$ (por la raíz) y $x \neq 0$ (por estar abajo).  
* **Dominio:** $x > 0$  👉  $(0, \infty)$

### B. El Gran Reto (Composición)
**Funciones:** $f(x) = \frac{10}{x-4}$ y $g(x) = \sqrt{x}$  
**Composición:** $(f \circ g)(x) = \frac{10}{\sqrt{x} - 4}$  
* **Análisis:**
    1.  $x \geq 0$ (por la raíz).
    2.  $\sqrt{x} - 4 \neq 0 \implies \sqrt{x} \neq 4 \implies x \neq 16$.
* **Dominio:** $[0, 16) \cup (16, \infty)$

---

## 💡 Glosario Rápido
* **$[$ o $]$ :** Incluye el número (Intervalo cerrado).
* **$($ o $)$ :** NO incluye el número (Intervalo abierto).
* **$\cup$ :** Unión de dos pedazos de dominio.


# 🔄 Función Inversa e Implícita

<!-- ## 1. Función Inversa $f^{-1}(x)$
Es la función que revierte el proceso de la original.
* **Gráficamente:** Es simétrica respecto a la línea $y = x$.
* **Método:** 1. Cambiar $f(x)$ por $y$.
  2. Intercambiar $x \leftrightarrow y$.
  3. Despejar la nueva $y$.

## 2. Función Implícita
Es aquella donde la variable dependiente ($y$) **no está despejada**.
* **Explícita:** $y = x^2 + 2$
* **Implícita:** $x^2 + y^2 = 25$ o $\sin(y) + x = 0$ -->

### 🔍 Identificación de Funciones Implícitas

#### Trucos para identificarla:
* **Mezcla:** La $x$ y la $y$ están en el mismo lado de la igualdad.
* **Potencias en $y$:** Si ves una $y^2$, $y^3$ o $\sqrt{y}$, suele ser implícita.
* **Dificultad de despeje:** Si intentar dejar sola a la $y$ parece un rompecabezas imposible.

#### Tabla de Ejemplos:
| Tipo | Ejemplo | Aspecto Visual |
| :--- | :--- | :--- |
| **Explícita** | $y = 3x - 5$ | La $y$ es la protagonista absoluta. |
| **Implícita** | $x^2 + y^2 = 25$ | Están mezcladas (esto es un círculo). |
| **Implícita** | $e^y + xy = 10$ | La $y$ está "atrapada" en varios sitios. |

> **Tip:** Identifícala rápido si ves la $y$ con exponentes, dentro de raíces o mezclada con la $x$ en el mismo lado.
---

## 🔄 Función Inversa $f^{-1}(x)$
Es la función que revierte el proceso de la original.

**Método de 3 pasos:**
1. Cambiar $f(x)$ por $y$.
2. Intercambiar $x \leftrightarrow y$ (¡Cuidado si hay varias $y$!).
3. Despejar la nueva $y$.

**Ejemplo resuelto:**
* Función: $f(x) = 5x - 10$
* Inversa: $f^{-1}(x) = \frac{x + 10}{5}$

## 🏆 El Reto de la Inversa (Nivel Avanzado)

Cuando la $x$ aparece arriba y abajo en una fracción, usamos **Factor Común**.

**Ejercicio:** $f(x) = \frac{x + 1}{x - 2}$

**Pasos Clave:**
1. $x = \frac{y + 1}{y - 2}$
2. $x(y - 2) = y + 1$
3. $xy - 2x = y + 1$
4. $xy - y = 1 + 2x$
5. $y(x - 1) = 1 + 2x$
6. **Inversa:** $f^{-1}(x) = \frac{1 + 2x}{x - 1}$

> **Nota:** El dominio de la función original nos dice el rango de la inversa, y viceversa. ¡Todo está conectado!

## 🚀 Inversas de Funciones Especiales

### 1. Irracionales (Raíces)
* **Regla:** La raíz se elimina elevando a la potencia.
* **Ejemplo:** $f(x) = \sqrt{x} \implies f^{-1}(x) = x^2$

### 2. Exponenciales y Logarítmicas
* **Regla:** Se cancelan entre sí.
* **Ejemplo:** $f(x) = e^x \implies f^{-1}(x) = \ln(x)$
* **Ejemplo:** $f(x) = 10^x \implies f^{-1}(x) = \log_{10}(x)$

### 3. Trigonométricas
* **Seno:** $\sin(x) \leftrightarrow \arcsin(x)$
* **Coseno:** $\cos(x) \leftrightarrow \arccos(x)$
* **Tangente:** $\tan(x) \leftrightarrow \arctan(x)$

> **💡 Nota Visual:** Para que las trigonométricas tengan inversa, debemos "cortar" su dominio (usar solo un pedacito de la onda), porque si no, no serían funciones uno-a-uno.

### 🧪 Ejercicio Híbrido (Exponencial + Raíz)
**Función:** $f(x) = e^{\sqrt{x - 1}}$

**Proceso de Inversa:**
1. $x = e^{\sqrt{y - 1}}$
2. $\ln(x) = \sqrt{y - 1}$  <-- Aplicamos logaritmo
3. $(\ln(x))^2 = y - 1$    <-- Elevamos al cuadrado
4. $y = (\ln(x))^2 + 1$    <-- Despejamos

**Resultado:** $f^{-1}(x) = (\ln(x))^2 + 1$

> ⚠️ **¡Cuidado con el orden!**
> En la inversa de $e^{\sqrt{x}}$, el cuadrado afecta a TODO el logaritmo:
> * Correcto: $(\ln x)^2$
> * Incorrecto: $\ln(x^2)$

### 📐 Inversas con Desplazamientos
Cuando la función tiene sumas o restas fuera de la función principal:

**Ejemplo:** $f(x) = \sin(x) + 5$
1. $x = \sin(y) + 5$
2. $x - 5 = \sin(y)$
3. $\arcsin(x - 5) = y$

**Resultado:** $f^{-1}(x) = \arcsin(x - 5)$

> **Regla de Oro:** Lo que está más "afuera" en la función original es lo primero que se despeja en la inversa.

### 🔑 El "Némesis" del Logaritmo
Cuando la $x$ está atrapada en un logaritmo, usamos la base $e$.

**Ejercicio:** $f(x) = \ln\left(\frac{x}{3}\right)$
1. $x = \ln\left(\frac{y}{3}\right)$
2. $e^x = \frac{y}{3}$
3. $3e^x = y$

**Resultado:** $f^{-1}(x) = 3e^x$