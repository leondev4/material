# Sumas de Riemann

## Definición
- **Concepto**: Aproximación numérica del área bajo una curva
- **Fórmula general**:
  $$ S_n = \sum_{i=1}^{n} f(c_i) \Delta x $$
  donde:
  - $$ \Delta x = \frac{b-a}{n} $$
  - $$ c_i $$: punto muestra en el i-ésimo subintervalo

## Tipos de Sumas
### Suma por Izquierda
- **Punto muestra**: Extremo izquierdo
- **Ejemplo**:
  - Función: $$ f(x) = x^2 + 1 $$ en [0,2], n=4
  - Solución:
    $$ \Delta x = 0.5 $$
    $$ S = f(0)(0.5) + f(0.5)(0.5) + f(1)(0.5) + f(1.5)(0.5) $$
    $$ S = (1)(0.5) + (1.25)(0.5) + (2)(0.5) + (3.25)(0.5) = 3.75 $$

### Suma por Derecha
- **Punto muestra**: Extremo derecho
- **Ejercicio**:
  - Función: $$ f(x) = 3x - 1 $$ en [1,4], n=6
  - Solución:
    $$ \Delta x = 0.5 $$
    $$ S = f(1.5)(0.5) + f(2)(0.5) + \cdots + f(4)(0.5) $$
    $$ S = (3.5)(0.5) + (5)(0.5) + \cdots + (11)(0.5) = 16.5 $$

### Suma Punto Medio
- **Punto muestra**: Centro del subintervalo
- **Ejemplo**:
  - Función: $$ f(x) = e^x $$ en [0,1], n=5
  - Solución:
    $$ \Delta x = 0.2 $$
    Puntos medios: 0.1, 0.3, 0.5, 0.7, 0.9
    $$ S \approx e^{0.1}(0.2) + e^{0.3}(0.2) + \cdots + e^{0.9}(0.2) \approx 1.753 $$

## Aplicaciones
1. **Cálculo de áreas irregulares**
2. **Fundamento para integrales definidas**
3. **Problemas físicos**:
   - Trabajo mecánico
   - Centro de masa

## Ejercicios Propuestos
### Ejercicio 1
- Función: $$ f(x) = \frac{1}{x+1} $$ en [0,2], n=4 (suma izquierda)
- Solución:
  $$ \Delta x = 0.5 $$
  $$ S = f(0)(0.5) + f(0.5)(0.5) + f(1)(0.5) + f(1.5)(0.5) $$
  $$ S = (1)(0.5) + (\frac{2}{3})(0.5) + (0.5)(0.5) + (0.4)(0.5) \approx 1.183 $$

### Ejercicio 2 (Avanzado)
- Función: $$ f(x) = \sin x $$ en [0,π], n=6 (suma derecha)
- Solución:
  $$ \Delta x = \frac{π}{6} $$
  $$ S = \sum_{k=1}^6 \sin\left(\frac{kπ}{6}\right)\left(\frac{π}{6}\right) $$
  $$ S \approx (0.5 + 0.866 + 1 + 0.866 + 0.5 + 0)(π/6) \approx 1.954 $$

## Relación con Integrales
- Límite cuando n→∞:
  $$ \lim_{n \to \infty} S_n = \int_a^b f(x)dx $$