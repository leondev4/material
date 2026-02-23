
# Límites: Directos, Factorización, Laterales, Trigonométricos

---
## Reactivo 1
- **Pregunta:** 3 ¿Cuál es la función inversa de $ f(x) = 3x + 6 $?

  **Opciones:**
  a) $ f^{-1}(x) = \frac{x}{3} - 6 $
  b) $ f^{-1}(x) = \frac{x - 6}{3} $
  c) $ f^{-1}(x) = 3x - 6 $
  d) $ f^{-1}(x) = \frac{x + 6}{3} $

**Solución:**
Para hallar la inversa:
1. Sustituir $ f(x) $ por $ y $: $ y = 3x + 6 $
2. Intercambiar $ x $ e $ y $: $ x = 3y + 6 $
3. Despejar $ y $: $ x - 6 = 3y $ → $ y = \frac{x - 6}{3} $
4. Escribir la inversa: $ f^{-1}(x) = \frac{x - 6}{3} $

**Respuesta correcta:** b

---
## Reactivo 2
- **Pregunta:** 3 ¿Cuál es el valor del límite $ \lim_{x \to 0} \frac{\sin(5x)}{x} $?

  **Opciones:**
  a) 0
  b) 1
  c) 5
  d) No existe

**Solución:**
Sabemos que $ \lim_{x \to 0} \frac{\sin(kx)}{x} = k $ cuando $ k $ es constante.
Por lo tanto: $ \lim_{x \to 0} \frac{\sin(5x)}{x} = 5 \cdot \lim_{x \to 0} \frac{\sin(5x)}{5x} = 5 \cdot 1 = 5 $

**Respuesta correcta:** c

---
## Pregunta 3 (Función implícita)
- **Enunciado:** 3 ¿Cuál de las siguientes ecuaciones define a $ y $ como una función implícita de $ x $?
  a) $ y = x^2 + 3x - 5 $
  b) $ y^2 + 2xy + x^2 = 25 $
  c) $ f(x) = \sqrt{x} $
  d) $ y =\frac{x}{ 7} $
**Solución:** Una función implícita es aquella donde la relación entre $ x $ e $ y $ está dada por una ecuación donde $ y $ no está despejada. 
Respuesta correcta: **b**.

---
## Reactivo 4
- **Pregunta:** 3 Calcula el límite $ \lim_{x \to 2} \frac{x^2 - 4}{x - 2} $

  **Opciones:**
  a) 0
  b) 2
  c) 4
  d) No existe

**Solución:**
Factorizamos el numerador:
$ \lim_{x \to 2} \frac{x^2 - 4}{x - 2} = \lim_{x \to 2} \frac{(x-2)(x+2)}{x-2} $
Cancelamos $ (x-2) $:
$ \lim_{x \to 2} (x+2) = 2 + 2 = 4 $

**Respuesta correcta:** c

---
## Reactivo 5
- **Pregunta:** 3 Si $ f(x) = x + 4 $, ¿cuál es su función inversa $ f^{-1}(x) $?

  **Opciones:**
  a) $ f^{-1}(x) = x - 4 $
  b) $ f^{-1}(x) = x + 4 $
  c) $ f^{-1}(x) = \sqrt{x - 4} $
  d) $ f^{-1}(x) = \sqrt{x + 4} $

**Solución:**
Procedemos:
1. $ y = \sqrt{x + 4} $
2. $ x = \sqrt{y + 4} $
3. Elevamos al cuadrado: $ x^2 = y + 4 $
4. $ y = x^2 - 4 $
5. Dominio de la inversa: como el rango de $ f $ es $ [0, \infty) $, entonces $ x \geq 0 $

**Respuesta correcta:** a

---
## Reactivo 6
- **Pregunta:** 3 Calcula $ \lim_{x \to \infty} \frac{3x^2 - 2x + 1}{5x^2 + 4x - 3} $

  **Opciones:**
  a) 0
  b) $ \frac{3}{5} $
  c) 1
  d) $ \infty $

**Solución:**
Para límites en infinito con funciones racionales, dividimos numerador y denominador por la mayor potencia de $ x $:
$ \lim_{x \to \infty} \frac{3x^2 - 2x + 1}{5x^2 + 4x - 3} = \lim_{x \to \infty} \frac{3 - \frac{2}{x} + \frac{1}{x^2}}{5 + \frac{4}{x} - \frac{3}{x^2}} $
Cuando $ x \to \infty $, los términos con $ \frac{1}{x} $ y $ \frac{1}{x^2} $ tienden a 0:
$ = \frac{3 - 0 + 0}{5 + 0 - 0} = \frac{3}{5} $

**Respuesta correcta:** b

---
## Reactivo 7
- **Pregunta:** 3 Dada $ f(x) = \frac{1}{x-3} $, ¿cuál es el límite $ \lim_{x \to 3^-} f(x) $?

  **Opciones:**
  a) $ \infty $
  b) $ -\infty $
  c) 0
  d) No existe

**Solución:**
Cuando $ x \to 3^- $ (se acerca por la izquierda), $ x < 3 $, entonces $ x-3 < 0 $.
El denominador es negativo y se acerca a 0, por lo tanto:
$ \lim_{x \to 3^-} \frac{1}{x-3} = -\infty $

**Respuesta correcta:** b

---
## Reactivo 8
- **Enunciado:** 3 ¿Cuál es el valor de $ \lim_{x \to 0} \frac{\sin(3x)}{x} $?
  a) 0
  b) 1
  c) 3
  d) No existe
**Solución:** Usamos $ \lim_{u \to 0} \frac{\sin u}{u} = 1 $. Sea $ u=3x $: $ \lim_{x \to 0} \frac{\sin(3x)}{x} = \lim_{x \to 0} 3 \cdot \frac{\sin(3x)}{3x} = 3 \cdot 1 = 3 $. Respuesta correcta: **c**.
