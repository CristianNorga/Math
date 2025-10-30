# Límites y Continuidad

## Límites
El concepto de límite es fundamental en cálculo y análisis matemático. Un límite describe el comportamiento de una función a medida que su variable independiente se acerca a un valor específico.

### Introducción a los límites
Para entender qué son los límites, consideremos un ejemplo. Empezamos con la función 
$f(x)=x+2$.

Se grafica la función f. El eje x va de 0 a 9. La gráfica consta de una recta que empieza en (0, 2), se mueve hacia arriba, pasa a través de (2, 4) y (4, 6) y termina en 

El límite de 
$f$ en 
$x=3$ es el valor al cual se aproxima 
$f$ a medida que nos acercamos más y más a 
$x=3$. Gráficamente, es el valor de 
$y$ al que tendemos en la gráfica de 
$f$ al acercarnos más y más al punto de la gráfica donde 
$x=3$.
Por ejemplo, si partimos del punto 
$(1,3)$ y nos movemos en la gráfica hasta estar muy cerca de 
$x=3$, entonces nuestro valor 
$y$ (es decir, el valor de la función) está muy cerca de 
$5$.
La gráfica de la función f está animada. Un punto se mueve hacia arriba sobre la recta desde (1, 3) hasta (2.99, 4.99).
Creado con Geogebra.
Similarmente, si empezamos en 
$(5,7)$ y nos movemos a la izquierda hasta estar muy cerca de 
$x=3$, el valor 
$y$ nuevamente estará muy cerca de 
$5$.
La gráfica de la función f está animada. Un punto se mueve hacia abajo sobre la recta desde (5, 7) hasta (3.01, 5.01).
Creado con Geogebra.
Por estas razones, decimos que el límite de 
$f$ en 
$x=3$ es 
$5$.
La gráfica de la función f tiene flechas que apuntan a lo largo de la recta, hacia arriba y a la derecha y hacia abajo y a la izquierda, respectivamente, en dirección del punto (3, 5).

Tal vez te preguntes cuál es la diferencia entre el límite de 
$f$ en 
$x=3$ y el valor de 
$f$ en 
$x=3$, es decir, 
$f(3)$.
Y sí, el límite de 
$f(x)=x+2$ en 
$x=3$ es igual a 
$f(3)$, pero este no siempre es el caso. Para entender esto, consideremos la función 
$g$. Esta función es igual a 
$f$, excepto que no está definida para 
$x=3$.
Se grafica la función g. El eje x va de 0 a 9. La gráfica consta de una recta que empieza en (0, 2), se mueve hacia arriba, pasa a través de (2, 4) y de un círculo abierto en (3, 5) y termina en (7, 9).

Puedes pensar 
$g$ como una función definida por partes:

$g(x)=\begin{cases}
x+2&\text{si }x\neq 3
\\\\
\text{indefinida}&\text{si }x=3
\end{cases}$
También puedes definir 
$g$ como la función racional

$\dfrac{x^2-x-6}{x-3}$. Esta función no está definida en 
$x=3$, pues eso causa una división entre cero. Por otro lado, al simplificar obtenemos 
$f$:

$\begin{aligned}
g(x)&=\dfrac{x^2-x-6}{x-3}
\\\\
&=\dfrac{(x+2)\cancel{(x-3)}}{\cancel{x-3}}
\\\\
&=x+2, \text{ para }x\neq 3
\end{aligned}$
Tal como con 
$f$, el límite de 
$g$ en 
$x=3$ es 
$5$. Esto se debe a que aún podemos acercarnos mucho a 
$x=3$ y los valores de la función se acercarán muchísimo a 
$5$.
La gráfica de la función \(g\) tiene flechas que apuntan a lo largo de la recta, hacia arriba y a la derecha y hacia abajo y a la izquierda, respectivamente, en dirección del círculo abierto en (3, 5).

Así que el límite de 
$g$ en 
$x=3$ es igual a 
$5$, ¡pero el valor de 
$g$ en 
$x=3$ no está definido! ¡No son lo mismo!
Esa es la belleza de los límites: no dependen del valor real de la función en el límite. Describen cómo se comporta la función al acercarse al límite.

### Límites laterales
A veces, el comportamiento de una función puede ser diferente dependiendo de si nos acercamos a un cierto punto desde la izquierda o desde la derecha. En estos casos, hablamos de límites laterales.
Consideremos la función
$$h(x) = \begin{cases}
2x + 1 & \text{si } x < 3 \\
5 & \text{si } x = 3 \\
2x - 1 & \text{si } x > 3
\end{cases}$$

Se grafica la función h. El eje x va de 0 a 6. La gráfica consta de una recta que empieza en (0, 1), se mueve hacia arriba, pasa a través de (2, 5) y tiene un círculo abierto en (3, 7). En (3, 5) hay un punto sólido. Luego la gráfica continúa desde (3, 5) y se mueve hacia arriba pasando por (4, 7) y termina en (6, 11).

Para encontrar el límite de 
$h$ en $x=3$, debemos considerar los límites laterales.
- El límite lateral izquierdo, denotado como
$$\lim_{x \to 3^-} h(x),$$
se refiere al valor al que se acerca $h(x)$ a medida que $x$ se aproxima a $3$ desde la izquierda. En este caso, cuando $x < 3$, la función está definida como $2x + 1$. Por lo tanto, podemos calcular el límite lateral izquierdo como:
$$\lim_{x \to 3^-} h(x) = \lim_{x \to 3^-} (2x + 1) = 2(3) + 1 = 7.$$
- El límite lateral derecho, denotado como
$$\lim_{x \to 3^+} h(x),$$
se refiere al valor al que se acerca $h(x)$ a medida que $x$ se aproxima a $3$ desde la derecha. En este caso, cuando $x > 3$, la función está definida como $2x - 1$. Por lo tanto, podemos calcular el límite lateral derecho como:
$$\lim_{x \to 3^+} h(x) = \lim_{x \to 3^+} (2x - 1) = 2(3) - 1 = 5.$$
Dado que los límites laterales no son iguales
$$\lim_{x \to 3^-} h(x) = 7 \quad \text{y} \quad \lim_{x \to 3^+} h(x) = 5,$$
decimos que el límite de $h$ en $x=3$ no existe.

### Límites no acotables (acotados)
En algunos casos, una función puede acercarse a un valor infinito a medida que la variable independiente se aproxima a un cierto punto. En estos casos, decimos que el límite no es acotable o que tiende a infinito.
Consideremos la función
$$f(x) = \frac{1}{(x - 2)^2}.$$
Se grafica la función f. El eje x va de 0 a 4. La gráfica consta de una curva que se acerca al eje y en (0, 0.25), se mueve hacia arriba, tiene una asíntota vertical en x=2 y luego la curva vuelve a bajar acercándose al eje y en (4, 0.25).
A medida que $x$ se acerca a $2$ desde la izquierda ($x \to 2^-$), el valor de $f(x)$ aumenta sin límite, es decir,
$$\lim_{x \to 2^-} f(x) = +\infty.$$
De manera similar, a medida que $x$ se acerca a $2$ desde la derecha ($x \to 2^+$), el valor de $f(x)$ también aumenta sin límite:
$$\lim_{x \to 2^+} f(x) = +\infty.$$
Por lo tanto, decimos que el límite de $f$ en $x=2$ no es acotable y se expresa como:
$$\lim_{x \to 2} f(x) = +\infty.$$

> para los casos en el que el limíte tiende a cambiar de direccion infinita en ambos lados, se considera que el límite no existe.

### Límites unilaterales
Los límites unilaterales son aquellos que se evalúan desde un solo lado del punto de interés, ya sea desde la izquierda o desde la derecha. Estos límites son útiles para analizar el comportamiento de una función en puntos donde puede haber discontinuidades o cambios abruptos.
Consideremos la función
$$f(x) = \begin{cases}
x^2 & \text{si } x < 2 \\
4 & \text{si } x = 2 \\
x + 2 & \text{si } x > 2
\end{cases}$$

### Aproximar límites por medio de tablas
Para aproximar límites utilizando tablas, se evalúa la función en valores cercanos al punto de interés desde ambos lados. Esto ayuda a observar el comportamiento de la función a medida que se acerca al límite.
Consideremos la función
$$
\lim_{x \to 3} \frac{x^3 - 3x^2}{5x - 15}
$$
Para aproximar este límite, podemos crear una tabla de valores evaluando la función en puntos cercanos a $x=3$ desde ambos lados.
|   x   | f(x) = (x^3 - 3x^2) / (5x - 15) |
|-------|----------------------------------|
| 2.9   | 1.74                             |
| 2.99  | 1.974                            |
| 3     | 0                                |
| 3.01  | 0.026                           |
| 3.1   | 0.1                              |

> Nuestro valor de $x$ está aumentando entre valores consecutivos de $x$ deben hacerse cada vez más pequeñas mientras nos acercamos a $3$.
Al realizarlo de manera constante, ejemplo: 3, 5, 7, etc..., $2$ unidades. De esta manera no nos estamos acercando claramente a ningún valor en particular.
