# 🧠 GUÍA MAESTRA: LÍMITES DE POTENCIAS VARIABLES

Esta guía resume el proceso para resolver límites con formas indeterminadas como $0^0$, $1^\infty$ e $\infty^0$ usando la base $e$ y la Regla de L'Hôpital.

---

## 1. EL TRUCO MAESTRO (LA LLAVE)
Para cualquier límite de la forma $f(x)^{g(x)}$, usa esta transformación:

> **Identidad fundamental:** $A^B = e^{B \cdot \ln(A)}$

Esto permite "bajar" el exponente para poder operar. 



---

## 2. TABLA DE RESULTADOS RÁPIDOS
Patrones comunes que te ahorrarán tiempo:

| Tipo de Límite | Estructura | Resultado | Ejemplo |
| :--- | :--- | :--- | :--- |
| **Base Cero** | $x^x$ | **1** | $\lim_{x \to 0^+} x^x = 1$ |
| **Definición de $e$** | $(1+x)^{1/x}$ | **$e$** | $\lim_{x \to 0} (1+x)^{1/x} = e$ |
| **Con Coeficiente** | $(1+ax)^{1/x}$ | **$e^a$** | $\lim_{x \to 0} (1+5x)^{1/x} = e^5$ |
| **Trigonométrico** | $(\cos x)^{1/x^2}$ | **$e^{-1/2}$** | El "Jefe Final" |



---

## 3. TRUCOS DE SUPERVIVENCIA (CÁLCULO MENTAL)

* **🚀 El coeficiente manda:** En la forma $(1 + \mathbf{k}x)^{1/x}$, el resultado siempre será $e^{\mathbf{k}}$. Si es $(1 - 2x)^{1/x}$, el resultado es $e^{-2}$.
* **🚀 Aproximación de Seno:** Cuando $x \to 0$, puedes tratar a $\operatorname{sen}(x)$ como si fuera simplemente $x$. Por eso $(1 + \operatorname{sen} x)^{1/x}$ da $e^1$.
* **🚀 El truco de la fracción:** Si tienes $x \cdot \ln(x)$, siempre pásalo a la forma $\frac{\ln(x)}{1/x}$ para que sea $\infty / \infty$ y puedas usar L'Hôpital.


---

## 5. EL PROCESO EN 4 PASOS
1.  **Transformar:** Usa $e^{\text{exponente} \cdot \ln(\text{base})}$.
2.  **Fraccionar:** Asegúrate de tener una forma $0/0$ o $\infty/\infty$.
3.  **Derivar:** Aplica L'Hôpital (deriva arriba y abajo por separado).
4.  **Evaluar:** Sustituye la $x$ y el resultado final ponlo como exponente de $e$.

---

## 6. EJERCICIOS DE PRÁCTICA (¡PONTE A PRUEBA!)

Intenta resolver estos usando la guía anterior:

1.  **Nivel Fácil:** $\lim_{x \to 0^+} x^{3x}$  
    *(Pista: El resultado debería ser 1)*.
    
2.  **Nivel Medio:** $\lim_{x \to 0} (1 - 4x)^{1/x}$  
    *(Pista: Usa el truco del coeficiente manda)*.

3.  **Nivel Difícil:** $\lim_{x \to 0^+} (\tan x)^x$  
    *(Pista: Se parece mucho al de $(\operatorname{sen} x)^x$)*.



---