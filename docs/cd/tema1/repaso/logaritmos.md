
# 📉 Logaritmos y Exponenciales: El Mapa de Poder
## 0. La Función Exponencial
Es la función donde la variable $x$ está en el "techo" (el exponente).
**Fórmula:** $f(x) = a^x$

### Características clave:
* **Base (a):** Debe ser mayor a 0 y diferente de 1 ($a > 0, a \neq 1$).
* **Dominio:** Todos los reales ($-\infty, \infty$). Puedes elevar un número a lo que sea.
* **Rango:** Solo números positivos $(0, \infty)$. Una potencia de base positiva NUNCA da un resultado negativo.
* **Punto fijo:** Toda función exponencial simple pasa por el punto **(0, 1)**, porque cualquier número elevado a la 0 es 1 ($a^0 = 1$).

### Tipos de Crecimiento:
1. **Crecimiento ($a > 1$):** La curva sube rápido (ej: $2^x$).
2. **Decaimiento ($0 < a < 1$):** La curva baja hacia el eje X (ej: $0.5^x$).

## 1. La Relación Fundamental
El logaritmo es la pregunta inversa a la potencia:
**Si:** $b^x = a$ 
**Entonces:** $\log_b(a) = x$

> *Traducción:* "¿A qué número elevo la **base (b)** para obtener el **resultado (a)**?"

---

## 2. Propiedades de Oro
Estas reglas sirven para "desarmar" ecuaciones difíciles:

| Regla | Operación | Resultado |
| :--- | :--- | :--- |
| **Producto** | $\log_b(M \cdot N)$ | $\log_b(M) + \log_b(N)$ |
| **Cociente** | $\log_b(M / N)$ | $\log_b(M) - \log_b(N)$ |
| **Potencia** | $\log_b(M^k)$ | $k \cdot \log_b(M)$ |

---

## 3. Logaritmos Especiales
* **Logaritmo Común:** Si no ves base, es base 10. $\log(x) = \log_{10}(x)$
* **Logaritmo Natural:** Usa la base $e$ (aprox. 2.718). $\ln(x) = \log_e(x)$

---

## 4. El Truco del Exponente (Para resolver $x$)
Cuando la $x$ está arriba (ej: $2^x = 20$), aplicas logaritmos a ambos lados para que la $x$ "baje" a multiplicar.

## 5. Cómo despejar una "x" en el exponente
Si tienes $a^x = b$:

1. Aplica logaritmos: $\log(a^x) = \log(b)$
2. Baja la x: $x \cdot \log(a) = \log(b)$
3. Divide: $x = \frac{\log(b)}{\log(a)}$

> **Nota visual:** El logaritmo es como una escalera que permite que la "x" baje del techo al piso para poder despejarla.

## 6. Aplicaciones en la Vida Real 🌍

### A. Escala Richter (Terremotos)
* Cada grado más en la escala significa que el terremoto es **10 veces más fuerte** en intensidad.
* Ejemplo: Un grado 7 es 100 veces más potente que un grado 5 ($10^2$).

### B. El pH (Acidez)
* Mide la concentración de iones de hidrógeno.
* Una diferencia de 1 punto en el pH es una diferencia de **10 veces** en acidez.

### C. Interés Compuesto (Dinero)
* Se usa para calcular cuánto tiempo ($t$) tardará una inversión en duplicarse usando la fórmula: $A = P(1 + r)^t$.

## 7. Dominio y Restricciones de Logaritmos
Para la función $f(x) = \log_b(g(x))$:

* **Regla:** El argumento $g(x)$ debe ser **ESTRICTAMENTE MAYOR A CERO** ($> 0$).
* **Prohibido:** No existen logaritmos de números negativos ni de cero.
* **Gráficamente:** La curva nunca cruza el eje Y hacia la izquierda; se acerca al eje Y pero nunca lo toca (asíntota vertical en $x=0$).

**Ejemplo de Dominio:**
Si tienes $y = \log(x - 3)$, el dominio es $x - 3 > 0$, o sea, **$x > 3$**.

## 8. Ejemplos Prácticos de Aplicación 🚀

### A. Química: Cálculo de pH
**Problema:** Una solución tiene una concentración de $H^+$ de $0.0001$. ¿Cuál es su pH?
* **Fórmula:** $pH = -\log[H^+]$
* **Proceso:** $pH = -\log(10^{-4})$
* **Resultado:** $pH = 4$ (Ácido)

### B. Sismología: Escala Richter
**Problema:** Un sismo mueve la aguja de un sismógrafo $1,000$ unidades. ¿Cuál es su magnitud?
* **Fórmula:** $M = \log(A)$
* **Proceso:** $M = \log(1,000)$ → (Contamos 3 ceros)
* **Resultado:** Magnitud $3.0$

### C. Sonido: Decibelios (dB)
**Problema:** El ruido de una aspiradora es $100,000$ veces más intenso que el silencio total.
* **Fórmula:** $dB = 10 \cdot \log(\text{Intensidad})$
* **Proceso:** $10 \cdot \log(100,000) = 10 \cdot 5$
* **Resultado:** $50 \text{ dB}$

### D. Finanzas: Tiempo de Inversión
**Problema:** ¿Cuánto tarda en duplicarse un dinero al $10\%$ de interés anual?
* **Fórmula:** $t = \frac{\log(2)}{\log(1.10)}$
* **Resultado:** $\approx 7.27$ años