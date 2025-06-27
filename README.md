# Problema-Analisis Numerico
## Sistema Masa–Resorte Amortiguado y Forzado

Este problema estudia un sistema masa–resorte con amortiguamiento no lineal y fuerza externa periódica.

La ecuación diferencial ordinaria que describe el movimiento del sistema es:

$$
m \frac{d^2x}{dt^2} + a \left(\frac{dx}{dt}\right)^2 + bx = F_0 \sin(\varpi t)
$$

donde:


donde:

- `x` es el desplazamiento desde la posición de equilibrio,
- `t` es el tiempo,
- `m` es la masa del resorte,
- `a` y `b` son constantes de amortiguamiento y del resorte, respectivamente.
- El término de amortiguamiento es **no lineal** y representa amortiguamiento por aire.
- El término del lado derecho representa la función de fuerza.

### Parámetros dados:

- `m = 2 kg`  
- `a = 5 N/(m/s)²`  
- `b = 6 N/m`  
- `F₀ = 2 N`  
- `ϖ = 0.5 rad/s`

Condiciones iniciales:

- Desplazamiento inicial: `x(0) = 1 m`  
- Velocidad inicial: `x'(0) = 0 m/s`

---

## A. (14 pts)

Introducir las variables necesarias para poder escribir el problema de valor inicial (P.V.I.) de orden superior como un sistema de ecuaciones diferenciales de primer orden, sujeto a sus respectivas condiciones iniciales.

Se debe definir claramente:

- la función vectorial `U(t)`,  
- el campo vectorial `F(t, U)`,  
- y el vector de condición inicial `Uₐ`  

para poder representar el sistema de ecuaciones diferenciales como un P.V.I. vectorial.

---

## B. (14 pts)

Utilice el método de Euler para aproximar el desplazamiento y la velocidad en el periodo `0 ≤ t ≤ 10` con un tamaño de paso `dt = 0.01`.

---

## C. (16 pts)

Grafique el desplazamiento y la velocidad contra el tiempo.

**¿Qué se puede concluir?**

---

## D. (6 pts)

¿Cuál es el intervalo de tiempo (dado por la discretización) en el que la masa pasa por la posición de equilibrio?

---
