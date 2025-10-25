# Funciones y Ecuaciones Cuadráticas

## Introducción a las parábolas
Las parábolas son las gráficas de las funciones cuadráticas, que tienen la forma general:
$$ f(x) = ax^2 + bx + c $$
donde $a$, $b$ y $c$ son constantes, y $a \neq 0$.

**Apertura de la parábola:**
- Si $a > 0$, la parábola se abre hacia arriba.
- Si $a < 0$, la parábola se abre hacia abajo.

**Vértice de la parábola:**
El vértice de la parábola es el punto más alto o más bajo de la curva, dependiendo de la apertura. Se puede encontrar usando las fórmulas:
$$ x_v = -\frac{b}{2a} $$
$$ y_v = f(x_v) = a(x_v)^2 + b(x_v) + c $$

> el vértice puede ser un máximo o un mínimo dependiendo de la apertura de la parábola.

**Eje de simetría:**
El eje de simetría de la parábola es la línea vertical que pasa por el vértice, dada por la ecuación:
$$ x = x_v = -\frac{b}{2a} $$

**Intersecciones con los ejes:**
- Intersección con el eje $y$: Ocurre cuando $x = 0$, entonces $f(0) = c$. Por lo tanto, la intersección con el eje $y$ es el punto $(0, c)$.
- Intersecciones con el eje $x$: Ocurren cuando $f(x) = 0$. Para encontrar estas intersecciones, se resuelve la ecuación cuadrática:
$$ ax^2 + bx + c = 0 $$
Usando la fórmula cuadrática:
$$ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$
El discriminante $D = b^2 - 4ac$ determina la naturaleza de las raíces:
- Si $D > 0$, hay dos raíces reales y distintas.
- Si $D = 0$, hay una raíz real doble.
- Si $D < 0$, no hay raíces reales.

## Resolver y graficar con forma factorizada

1. Producto en cero
para resolver ecuaciones cuadráticas en forma factorizada, se utiliza la propiedad del producto en cero:
Si $ab = 0$, entonces $a = 0$ o $b = 0$.
2. Encontrar raíces
Dada una ecuación cuadrática en forma factorizada:
$$ f(x) = a(x - r_1)(x - r_2) $$
Las raíces son $r_1$ y $r_2$. Para encontrar las raíces,
se establece cada factor igual a cero:
$$ x - r_1 = 0 \quad \Rightarrow \quad x = r_1 $$
$$ x - r_2 = 0 \quad \Rightarrow \quad x = r_2 $$

### Graficar cuadráticas en forma factorizada con producto en cero

#### Ejemplos

1. $ y = \frac{1}{2}(x-6)(x+2) $

Resolvemos para encontrar con producto en cero:
$$ x - 6 = 0 \quad \Rightarrow \quad x = 6 $$
$$ x + 2 = 0 \quad \Rightarrow \quad x = -2 $$

por lo tanto, las `intersecciones` con el eje $x$ son $(6, 0)$ y $(-2, 0)$.

Para encontrar el vértice, usamos la fórmula del eje de simetría:
$$ x_v = \frac{r_1 + r_2}{2} = \frac{6 + (-2)}{2} = 2 $$
Luego, calculamos $y_v$:
$$ y_v = f(2) = \frac{1}{2}(2-6)(2+2) = \frac{1}{2}(-4)(4) = -8 $$
Así, el vértice es $(2, -8)$.

## Resolver al sacar la raíz cuadrada

### Resolver cuadráticas al sacar raíces cuadradas

#### Resolver \[x^2=36\] y ecuaciones similares
Para resolver ecuaciones cuadráticas al sacar raíces cuadradas, se sigue el siguiente procedimiento:
1. Aislar el término cuadrático
2. Sacar la raíz cuadrada en ambos lados de la ecuación
3. Resolver para $x$

##### Ejemplos

1. $ x^2 + 3 = 75 $

Aislamos el término cuadrático:
$$ x^2 = 75 - 3 $$
$$ x^2 = 72 $$

Sacamos la raíz cuadrada en ambos lados:
$$ \sqrt{x^2} = \sqrt{72} $$
$$ x = \pm 6\sqrt{2} $$

#### Resolver \[(x-2)^2=49\] y ecuaciones similares

Aislamos el término cuadrático:
$$ (x-2)^2 = 49 $$

Sacamos la raíz cuadrada en ambos lados:
$$ \sqrt{(x-2)^2} = \sqrt{49} $$
$$ x-2 = \pm 7 $$

Resolviendo para $x$:
1. $ x - 2 = 7 \quad \Rightarrow \quad x = 9 $
2. $ x - 2 = -7 \quad \Rightarrow \quad x = -5 $

Por lo tanto, las soluciones son $ x = 9 $ y $ x = -5 $.

#### Resolver \[2x^2+3=131\] y ecuaciones similares

Aislamos el término cuadrático:
$$ 2x^2 = 131 - 3 $$
$$ 2x^2 = 128 $$

Dividimos entre 2:
$$ x^2 = 64 $$

Sacamos la raíz cuadrada en ambos lados:
$$ \sqrt{x^2} = \sqrt{64} $$
$$ x = \pm 8 $$

Por lo tanto, las soluciones son $ x = 8 $ y $ x = -8 $.

## Forma vértice o forma canónica
La forma vértice o forma canónica de una función cuadrática es útil para identificar el vértice de la parábola y comprender sus transformaciones.
Dependiendo donde abra la parábola, el vértice puede representar un máximo o un mínimo de la función.

### Introducción a la forma canónica
La forma vértice o forma canónica de una función cuadrática es:
$$ f(x) = a(x - h)^2 + k $$
donde $(h, k)$ es el vértice de la parábola.
**Ventajas de la forma canónica:**
- Permite identificar fácilmente el vértice de la parábola.
- Facilita la comprensión de la transformación de la parábola (traslaciones y estiramientos).
**Conversión de forma estándar a forma canónica:**
Para convertir una función cuadrática de la forma estándar $f(x) = ax^2 + bx + c$ a la forma canónica, se puede completar el cuadrado:
1. Factorizar $a$ del término cuadrático y lineal:
$$ f(x) = a\left(x^2 + \frac{b}{a}x\right) + c $$
2. Completar el cuadrado dentro del paréntesis:
$$ f(x) = a\left[\left(x + \frac{b}{2a}\right)^2 - \left(\frac{b}{2a}\right)^2\right] + c $$
3. Simplificar para obtener la forma canónica:
$$ f(x) = a\left(x + \frac{b}{2a}\right)^2 + \left(c - a\left(\frac{b}{2a}\right)^2\right) $$
Donde el vértice es:
$$ h = -\frac{b}{2a}, \quad k = c - a\left(\frac{b}{2a}\right)^2 $$

### Graficar cuadráticas en forma canónica
#### Ejemplos
1. $ y = 3(x+2)^2 - 27 $
El vértice es $(-2, -27)$.
La parábola se abre hacia arriba porque $a = 3 > 0$.

- Para encontrar las intersecciones con el eje $x$, se resuelve:
$$ 3(x+2)^2 - 27 = 0 $$
$$ 3(x+2)^2 = 27 $$
$$ (x+2)^2 = 9 $$
$$ x + 2 = \pm 3 $$
$$ x = 1 \quad \text{y} \quad x = -5 $$
Por lo tanto, las intersecciones con el eje $x$ son $(1, 0)$ y $(-5, 0)$.

- Para saber el comportamiento de la parábola, se puede calcular algunos puntos adicionales alrededor del vértice.

tabla de valores:
|  x  |   y   |
|-----|-------|
| -3  |   ?   |
| -2  | -27   |
| -1  |   ?   |

Calculamos los valores de $y$ para $x = -3$ y $x = -1$:
Para $x = -3$:
$$ y = 3(-3+2)^2 - 27 = 3(1)^2 - 27 = 3 - 27 = -24 $$
Para $x = -1$:
$$ y = 3(-1+2)^2 - 27 = 3(1)^2 - 27 = 3 - 27 = -24 $$
La tabla de valores completa es:
|  x  |   y   |
|-----|-------|
| -3  | -24   |
| -2  | -27   |
| -1  | -24   |

2. $ y = \frac{1}{3}(x-6)^2 + 1 $
El vértice es $(6, 1)$.
La parábola se abre hacia arriba porque $a = \frac{1}{3} > 0$.
- encontrar los puntos adicionales alrededor del vértice.
tabla de valores:

|  x  |   y   |
|-----|-------|
|  5  |   ?   |
|  6  |   1   |
|  7  |   ?   |

Calculamos los valores de $y$ para $x = 5$ y $x = 7$:
Para $x = 5$:
$$ y = \frac{1}{3}(5-6)^2 + 1 = \frac{1}{3}(1)^2 + 1 = \frac{1}{3} + 1 = \frac{4}{3} $$
Para $x = 7$:
$$ y = \frac{1}{3}(7-6)^2 + 1 = \frac{1}{3}(1)^2 + 1 = \frac{1}{3} + 1 = \frac{4}{3} $$
La tabla de valores completa es:
|  x  |   y   |
|-----|-------|
|  5  | 4/3   |
|  6  |   1   |
|  7  | 4/3   |

> para representar 4/3 en decimal, es aproximadamente 1.33.

3. $ y = -\frac{1}{5}(x+5)^2 - 2 $
El vértice es $(-5, -2)$.
La parábola se abre hacia abajo porque $a = -\frac{1}{5} < 0$.
- encontrar los puntos adicionales alrededor del vértice.
tabla de valores:

|  x  |   y   |
|-----|-------|
| -6  |   ?   |
| -5  |  -2   |
| -4  |   ?   |

Calculamos los valores de $y$ para $x = -6$ y $x = -4$:
Para $x = -6$:
$$ y = -\frac{1}{5}(-6+5)^2 - 2 = -\frac{1}{5}(1)^2 - 2 = -\frac{1}{5} - 2 = -\frac{11}{5} $$
Para $x = -4$:
$$ y = -\frac{1}{5}(-4+5)^2 - 2 = -\frac{1}{5}(1)^2 - 2 = -\frac{1}{5} - 2 = -\frac{11}{5} $$
La tabla de valores completa es:

|  x  |    y    |
|-----|---------|
| -6  | -11/5   |
| -5  |   -2    |
| -4  | -11/5   |