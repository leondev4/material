# 📐 ACORDEÓN MAESTRO: TRIGONOMETRÍA

## 1. Triángulos Rectángulos (SOH CAH TOA)
Para un ángulo $\theta$ en un triángulo con un ángulo de 90°:

* **Seno:** $\sin(\theta) = \frac{\text{Opuesto}}{\text{Hipotenusa}}$
* **Coseno:** $\cos(\theta) = \frac{\text{Adyacente}}{\text{Hipotenusa}}$
* **Tangente:** $\tan(\theta) = \frac{\text{Opuesto}}{\text{Adyacente}}$

---

## 2. El Círculo Unitario (Radio = 1)
Relaciona los ángulos con coordenadas $(x, y)$ en el plano:
* **Eje X:** Representa al **Coseno**.
* **Eje Y:** Representa al **Seno**.
* **Relación fundamental:** $\tan(\theta) = \frac{\sin(\theta)}{\cos(\theta)}$



---

## 3. Transformación de Funciones (Ondas)
Para la ecuación general: $y = A \sin(Bx - C) + D$

| Componente | Nombre | Función |
| :--- | :--- | :--- |
| **$A$** | Amplitud | Altura de la onda (de centro a pico). |
| **$B$** | Frecuencia angular | Afecta al periodo (qué tan rápido se repite). |
| **$C$** | Fase | Desplazamiento horizontal (izquierda/derecha). |
| **$D$** | Traslación Vertical | Desplazamiento hacia arriba o abajo (Eje central). |

### Fórmulas de cálculo:
* **Periodo (Seno/Coseno):** $T = \frac{2\pi}{B}$
* **Periodo (Tangente):** $T = \frac{\pi}{B}$
* **Desfase:** $\text{Fase} = \frac{C}{B}$

---

## 4. Comparativa de Gráficas

| Característica | Seno | Coseno | Tangente |
| :--- | :--- | :--- | :--- |
| **Punto en $x=0$** | 0 | 1 | 0 |
| **Rango ($y$)** | $[-1, 1]$ | $[-1, 1]$ | $(-\infty, \infty)$ |
| **Forma** | Onda suave | Onda suave | Ramas infinitas |
| **Cortes (0)** | $0, \pi, 2\pi$ | $\pi/2, 3\pi/2$ | $0, \pi, 2\pi$ |



---

## 5. Tabla de Valores Comunes
| Ángulo (°) | Ángulo (rad) | Seno | Coseno | Tangente |
| :--- | :--- | :--- | :--- | :--- |
| **0°** | 0 | 0 | 1 | 0 |
| **30°** | $\pi/6$ | 1/2 | $\sqrt{3}/2$ | $\sqrt{3}/3$ |
| **45°** | $\pi/4$ | $\sqrt{2}/2$ | $\sqrt{2}/2$ | 1 |
| **60°** | $\pi/3$ | $\sqrt{3}/2$ | 1/2 | $\sqrt{3}$ |
| **90°** | $\pi/2$ | 1 | 0 | No existe (∞) |

## 6. Identidades Trigonométricas (El Kit de Simplificación)

### A. Recíprocas y de Cociente
* $\csc(\theta) = \frac{1}{\sin(\theta)}$
* $\sec(\theta) = \frac{1}{\cos(\theta)}$
* $\tan(\theta) = \frac{\sin(\theta)}{\cos(\theta)}$
* $\cot(\theta) = \frac{\cos(\theta)}{\sin(\theta)}$

### B. Pitagóricas (Las "Madre")
* $\sin^2(\theta) + \cos^2(\theta) = 1$
* $1 + \tan^2(\theta) = \sec^2(\theta)$
* $1 + \cot^2(\theta) = \csc^2(\theta)$

### C. Ángulo Doble
* $\sin(2\theta) = 2 \sin(\theta) \cos(\theta)$
* $\cos(2\theta) = \cos^2(\theta) - \sin^2(\theta)$

### D. Suma de Ángulos
* $\sin(\alpha \pm \beta) = \sin \alpha \cos \beta \pm \cos \alpha \sin \beta$
* $\cos(\alpha \pm \beta) = \cos \alpha \cos \beta \mp \sin \alpha \sin \beta$

## 7. Estrategias Avanzadas de Simplificación 🚀

### Estrategia A: "La Regla de Oro" (Todo a Seno y Coseno)
Si la expresión es confusa, convierte todas las funciones a sus formas básicas de $\sin(x)$ y $\cos(x)$.
* **Ejemplo:** $\tan(x) \cdot \csc(x) \rightarrow \frac{\sin(x)}{\cos(x)} \cdot \frac{1}{\sin(x)} = \frac{1}{\cos(x)} = \sec(x)$

### Estrategia B: Factorización + Pitágoras
Busca factores comunes para aislar términos que puedas convertir usando la identidad $\sin^2(x) + \cos^2(x) = 1$.
* **Ejemplo:** $\sin(x) - \sin(x)\cos^2(x)$
    1. Factor común: $\sin(x)(1 - \cos^2(x))$
    2. Identidad: $1 - \cos^2(x) = \sin^2(x)$
    3. Resultado: $\sin(x) \cdot \sin^2(x) = \sin^3(x)$

### Estrategia C: El Comodín del "1"
No veas al número $1$ como algo estático. En trigonometría, $1$ puede "disfrazarse" de:
* $\sin^2(x) + \cos^2(x)$
* $\sec^2(x) - \tan^2(x)$
* $\csc^2(x) - \cot^2(x)$
* $\sin(x) \cdot \csc(x)$ (o cualquier función por su recíproca)

## 8. Triángulos Oblicuángulos (Sin ángulo recto)

### A. Ley de Senos
*Úsala cuando conoces un lado y su ángulo opuesto (una "pareja" completa).*
$$\frac{a}{\sin(A)} = \frac{b}{\sin(B)} = \frac{c}{\sin(C)}$$

### B. Ley de Cosenos
*Úsala cuando tienes dos lados y el ángulo entre ellos (LAL) o los tres lados (LLL).*
$$a^2 = b^2 + c^2 - 2bc \cdot \cos(A)$$

### 🌐 Dominios y Rangos
| Función | Dominio (Valores de x) | Rango (Valores de y) |
| :--- | :--- | :--- |
| **sin(x)** | Todos los reales ($-\infty, \infty$) | [-1, 1] |
| **cos(x)** | Todos los reales ($-\infty, \infty$) | [-1, 1] |
| **tan(x)** | Reales excepto $90^\circ + 180^\circ n$ | ($-\infty, \infty$) |
---

⭐ **¡Felicidades! Has completado el curso intensivo de Trigonometría.**