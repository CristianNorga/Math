# Funciones
Una **función** es una relación especial entre dos conjuntos, donde a cada elemento del primer conjunto (llamado **dominio**) le corresponde exactamente un elemento del segundo conjunto (llamado **codominio**).

Las funciones le asignan a cada valor de entrada (del dominio) un único valor de salida (del codominio). Esto se puede representar matemáticamente como $ f: A \rightarrow B $, donde $ A $ es el dominio y $ B $ es el codominio.

representación gráfica de una función:

$$ Input \ (x) \rightarrow f(x) \rightarrow Output \ (y) $$

$$ f(x) \begin{cases}
x^2, si x es par \\
x + 5, si x es impar \\
\end{cases} $$

- f(2) = 4
- f(3) = 8

| x | f(x) or y |
|---|------|
| 2 | 4    |
| 3 | 8    |
| 4 | 16   |

## Partir de su ecuación
La función f(x) se define como f(x)=49-x^2. encuentre el valor de f(5).

**Solución:**
Sustituyendo x por 5 en la ecuación de la función:
f(5) = 49 - (5)^2
f(5) = 49 - 25
f(5) = 24

## Funciones discretas
Una función discreta es aquella que se define solo para valores específicos y separados dentro de su dominio. Estos valores suelen ser números enteros o puntos específicos en un conjunto finito. Por ejemplo, una función que asigna a cada estudiante su calificación en un examen es una función discreta, ya que las calificaciones son valores específicos (por ejemplo, 0, 1, 2, ..., 100) y no pueden tomar valores intermedios.

> Nota: Las funciones solo pueden tener un valor de salida para cada valor de entrada.

## Expresiones con notación de funciones
Las expresiones con notación de funciones son una forma de representar matemáticamente las relaciones entre variables utilizando símbolos específicos. La notación más común es f(x), donde "f" representa la función y "x" es la variable independiente o entrada. La expresión f(x) indica que la función toma el valor de "x" y lo transforma en un valor de salida, que se denota como f(x).
Por ejemplo, si tenemos una función f(x) = 2x + 3, esto significa que para cualquier valor de "x" que ingresemos en la función, el resultado será el doble de "x" más 3. Si evaluamos la función en x = 4, obtenemos:
f(4) = 2(4) + 3 = 8 + 3 = 11
Por lo tanto, f(4) = 11. Esta notación es útil para expresar y manipular funciones de manera clara y concisa en matemáticas.

## Hacer coincidir una entrada con la salida de una función (ecuación)

La función f se define de la siguiente manera:

$$ f(t) = 2t + 5 = 13 $$
Encuentra el valor de t que hace que f(t) = 13.

**Solución:**
Para encontrar el valor de t, debemos resolver la ecuación:
$$ -2t + 5 = 13 $$
Restamos 5 de ambos lados:
$$ -2t = 13 - 5 $$
$$ -2t = 8 $$
Dividimos ambos lados entre -2:
$$ t = \frac{8}{-2} $$
$$ t = -4 $$
Por lo tanto, el valor de t que hace que f(t) = 13 es t = -4.

## Diferencia entre función y ecuación
Una función es una relación matemática que asigna a cada elemento de un conjunto (dominio) un único elemento de otro conjunto (codominio). Se representa comúnmente como f(x), donde "f" es la función y "x" es la variable independiente. Por ejemplo, f(x) = 2x + 3 es una función que toma un valor de "x" y lo transforma en otro valor.

Una ecuación, por otro lado, es una afirmación matemática que establece que dos expresiones son iguales. Se utiliza para encontrar valores desconocidos y se representa con el signo "=". Por ejemplo, 2x + 3 = 11 es una ecuación que podemos resolver para encontrar el valor de "x".

## Obtener una función a partir de una ecuación
Para un valor de entrada 'b' dado, la función 'f' entrega un valor de salida 'a' para satisfacer la siguiente ecuación:
$$ 4a + 7b = -52 $$

Escriba la formula para la f(b) en terminos de 'b'.

**Solución:**
Para encontrar la función f(b) en términos de 'b', primero debemos despejar 'a' en la ecuación dada:
$$ 4a + 7b = -52 $$
Restamos 7b de ambos lados:
$$ 4a = -52 - 7b $$
Luego, dividimos ambos lados entre 4 para despejar 'a':
$$ a = \frac{-52 - 7b}{4} $$
Por lo tanto, la función f(b) en términos de 'b' es:
$$ f(b) = \frac{-52 - 7b}{4} $$
Simplificando, podemos escribir:
$$ f(b) = -13 - \frac{7b}{4} $$

## Tasa de cambio promedio

### Introducción a la tasa de cambio promedio
La tasa de cambio promedio es una medida que indica cómo cambia una cantidad en relación con otra durante un intervalo específico. En matemáticas, se utiliza comúnmente para describir cómo varía una función entre dos puntos en su dominio.

### Ejemplo
1. Considere la función d(t) = 3t + 1, que representa la distancia (d) en kilómetros recorrida por un automóvil en función del tiempo (t) en horas. Calcule la tasa de cambio promedio de la distancia entre t = 2 horas y t = 5 horas.
**Solución:**
Para calcular la tasa de cambio promedio, utilizamos la fórmula:
$$ \text{Tasa de cambio promedio} = \frac{d(t_2) - d(t_1)}{t_2 - t_1} $$
Donde:
- $ t_1 = 2 $ horas
- $ t_2 = 5 $ horas

Ahora, calculamos $ d(t_1) $ y $ d(t_2) $:
- $ d(2) = 3(2) + 1 = 6 + 1 = 7 $ kilómetros
- $ d(5) = 3(5) + 1 = 15 + 1 = 16 $ kilómetros

Sustituyendo estos valores en la fórmula de la tasa de cambio promedio:
$$ \text{Tasa de cambio promedio} = \frac{16 - 7}{5 - 2} = \frac{9}{3} = 3 $$

Por lo tanto, la tasa de cambio promedio de la distancia entre t = 2 horas y t = 5 horas es de 3 kilómetros por hora.

2. Considere la función d(t) = t^2 + 1, que representa la distancia (d) en kilómetros recorrida por un automóvil en función del tiempo (t) en horas. Calcule la tasa de cambio promedio de la distancia entre t = 1 hora y t = 4 horas.
**Solución:**
Para calcular la tasa de cambio promedio, utilizamos la fórmula:
$$ \text{Tasa de cambio promedio} = \frac{d(t_2) - d(t_1)}{t_2 - t_1} $$
Donde:
- $ t_1 = 1 $ hora
- $ t_2 = 4 $ horas

Ahora, calculamos $ d(t_1) $ y $ d(t_2) $:
- $ d(1) = (1)^2 + 1 = 1 + 1 = 2 $ kilómetros
- $ d(4) = (4)^2 + 1 = 16 + 1 = 17 $ kilómetros

Sustituyendo estos valores en la fórmula de la tasa de cambio promedio:
$$ \text{Tasa de cambio promedio} = \frac{17 - 2}{4 - 1} = \frac{15}{3} = 5 $$

Por lo tanto, la tasa de cambio promedio de la distancia entre t = 1 hora y t = 4 horas es de 5 kilómetros por hora.

> podemos pensar en las **rectas secantes** `(recta que intersecta la curva en dos puntos)` que conectan dos puntos en la gráfica de la función, y la pendiente de estas rectas secantes representa la tasa de cambio promedio entre esos dos puntos.