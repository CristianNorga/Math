# Gráficas de ecuaciones lineales
Una ecuación lineal en dos variables, como \(y = 2x + 3\), puede representarse gráficamente en un plano cartesiano.

## Ecuación de la recta horizontal
Una ecuación de la forma \(y = b\) representa una línea horizontal que cruza el eje \(y\) en el punto \((0, b)\).

## Pasos para graficar una ecuación lineal
1. **Identificar la pendiente y la intersección en el eje \(y\)**
    - En la ecuación \(y = mx + b\), \(m\) es la pendiente y \(b\) es la intersección en el eje \(y\).
    - Por ejemplo, en \(y = 2x + 3\), la pendiente \(m = 2\) y la intersección en el eje \(y\) es \(3\).
2. **Trazar la intersección en el eje \(y\)**
    - Coloca un punto en \((0, 3)\) en el plano cartesiano.
3. **Usar la pendiente para encontrar otro punto**
    - La pendiente \(m = 2\) significa que por cada unidad que avanzas en \(x\), subes \(2\) unidades en \(y\).
    - Desde el punto \((0, 3)\), mueve \(1\) unidad a la derecha (a \(x = 1\)) y \(2\) unidades hacia arriba (a \(y = 5\)), colocando otro punto en \((1, 5)\).
4. **Dibujar la línea**
    - Traza una línea recta que pase por los puntos \((0, 3)\) y \((1, 5)\).

## Pendiente
La pendiente \(m\) indica la inclinación de la línea.

La mejor manera para describir la pendiente es:
> Calcular el cambio en \(y\) en base al cambio en \(x\).
$$ m = \frac{Alza y}{Avance x} = \frac{desplazamiento vertical}{desplazamiento horizontal} = \frac{\Delta y}{\Delta x} = \frac{(cambio) y}{cambio x}$$
**Ejemplo:**
Dado los puntos \((1, 2)\) y \((3, 6)\):
- Cambio en \(y\): \(6 - 2 = 4\)
- Cambio en \(x\): \(3 - 1 = 2\)

**Ejemplo puntos negativos:**
Dado los puntos \((-1, -2)\) y \((1, 2)\):
- Cambio en \(y\): \(2 - (-2) = 4\)
- Cambio en \(x\): \(1 - (-1) = 2\)

Entonces, la pendiente es:
$ m = \frac{4}{2} = 2 $
> Calcular el cambio en ambos ejes en base a los puntos.
$$ m = \frac{y_2 - y_1}{x_2 - x_1} $$
**Ejemplo:**
| Eje | P 1 | P 2 | P 3 | P 4 |
|-----|----|----|----|----|
| x  | 1  | 2  | 3  | 4  |
| y  | 2  | 3  | 4  | 5  |
Usando los puntos \((1, 2)\) y \((2, 3)\):
$$ m = \frac{3 - 2}{2 - 1} = \frac{1}{1} = 1 $$


- Si \(m > 0\), la línea es ascendente `positivo` (sube de izquierda a derecha).
- Si \(m < 0\), la línea es descendente `negativo` (baja de izquierda a derecha).
- Si \(m = 0\), la línea es horizontal.

## Intersecciones con el eje x y con el eje y
- La intersección con el eje \(x\) es el punto donde la línea cruza el eje \(x\) (cuando \(y = 0\)), llamada también como ordenada al origen.
- La intersección con el eje \(y\) es el punto donde la línea cruza el eje \(y\) (cuando \(x = 0\)), llamada también como abscisa al origen.

### Partir desde una ecuación
Encontrar la ordenada y la abscisa al origen de la ecuación 

**Ejemplo 1:**
\(-5x + 4y = 20\):

1. **Encontrar la intersección con el eje \(y\)** (cuando \(x = 0\)):
   $$ 
   -5(0) + 4y = 20 \implies 4y = 20 \implies y = 5
$$
   Entonces, la intersección con el eje 
   $$ y = 5 $$

2. **Encontrar la intersección con el eje \(x\)** (cuando \(y = 0\)):
   $$
   -5x + 4(0) = 20 \implies -5x = 20 \implies x = -4
   $$
   Entonces, la intersección con el eje 
   $$ x = -4 $$

**Ejemplo 2:** \(y = 4x + 7\)
1. **Intersección con el eje \(y\)** (cuando \(x = 0\)):
   $$
   y = 4(0) + 7 \implies y = 7
   $$
   Entonces, la intersección con el eje 
   $$ y = 7 $$
2. **Intersección con el eje \(x\)** (cuando \(y = 0\)):
   $$
    0 = 4x + 7 \implies 4x = -7 \implies x = -\frac{7}{4}
   $$
   Entonces, la intersección con el eje 
   $$ x = -\frac{7}{4} $$

### Partir desde una tabla

tabla de valores:
| x | y |
|---|---|
| -2 | 8 |
| 1 | 2 |
| 2 | 0 |
| 4 | -4 |

La siguiente tabla muestra los valores de \(x\) y \(y\) de la gráfica de una funcion lineal, Determina las intersecciones con los ejes \(y\) de esta grafica.

1. **Intersección con el eje \(y\)** (cuando \(x = 0\)):
   - Observando la tabla, no hay un valor directo para \(x = 0\). Sin embargo, podemos ver que cuando \(x = 1\), \(y = 2\) y cuando \(x = -2\), \(y = 8\). Podemos interpolar para encontrar el valor de \(y\) cuando \(x = 0\).
   - La pendiente entre los puntos \((-2, 8)\) y \((1, 2)\) es:
     $$
     m = \frac{2 - 8}{1 - (-2)} = \frac{-6}{3} = -2
     $$
   - Usando la pendiente para encontrar \(y\) cuando \(x = 0\):
     $$
     y - 8 = -2(0 - (-2)) \implies y - 8 = -4 \implies y = 4
     $$
   Entonces, la intersección con el eje 
   $$ y = 4 $$

tabla actualizada:
| x | y |
|---|---|
| -2 | 8 |
| -1 | 6 |
| 0 | 4 |
| 1 | 2 |
| 2 | 0 |
| 4 | -4 |

> por cada unidad que avanzas en \(x\), bajas \(2\) unidades en \(y\).