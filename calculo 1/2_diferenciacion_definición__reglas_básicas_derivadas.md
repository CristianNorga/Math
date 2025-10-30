# Diferenciación Definición. Reglas básicas de derivadas

## La derivada como la pendiente de una curva

### Newton, Leibniz y Usain Bolt
Antes de entrar en la definición formal de la derivada, es útil entender el concepto de tasa de cambio. Imagina que estás observando a Usain Bolt correr una carrera de 100 metros. La tasa de cambio de su posición con respecto al tiempo nos da su velocidad instantánea en cualquier punto de la carrera.

Esta idea de velocidad instantánea es fundamental en el cálculo y se relaciona directamente con el concepto de derivada.

### La derivada como concepto
La derivada de una función en un punto mide la tasa de cambio instantánea de la función en ese punto. Se puede interpretar geométricamente como la `pendiente` de la tangente a la curva en ese punto.

La derivada de una función $f(x)$ en un punto $x=a$ se define como:
$$
f'(a) = \lim_{h \to 0} \frac{f(a+h) - f(a)}{h}
$$
Si este límite existe, decimos que $f$ es derivable en $x=a$.

> Recordar que se requiere entender los límites y la tasa de cambio para comprender completamente esta definición.

#### Reglas básicas de derivadas
Existen varias reglas que nos permiten calcular derivadas de manera más sencilla. Algunas de las más importantes son:

1. **Regla de la potencia**:
   $
   \frac{d}{dx} x^n = nx^{n-1}
   $
   donde $n$ es un número real.

2. **Regla de la suma**:
   $
   \frac{d}{dx} (f(x) + g(x)) = f'(x) + g'(x)
   $

3. **Regla del producto**:
   $
   \frac{d}{dx} (f(x)g(x)) = f'(x)g(x) + f(x)g'(x)
   $

4. **Regla del cociente**:
   $
   \frac{d}{dx} \left(\frac{f(x)}{g(x)}\right) = \frac{f'(x)g(x) - f(x)g'(x)}{(g(x))^2}
   $

5. **Regla de la cadena**:
   $
   \frac{d}{dx} f(g(x)) = f'(g(x))g'(x)
   $

### Rectas secantes y razones de cambio promedio
Para entender mejor la derivada, consideremos la idea de una recta secante. Una recta secante es una línea que intersecta una curva en dos puntos. La pendiente de esta recta secante entre los puntos $(a, f(a))$ y $(a+h, f(a+h))$ se calcula como:
$$
\text{Pendiente de la secante} = \frac{f(a+h) - f(a)}{h}
$$

A medida que $h$ se acerca a 0, la recta secante se aproxima a la tangente en el punto $a$, y la pendiente de la secante se aproxima a la derivada $f'(a)$.

#### Tasa de cambio promedio
La tasa de cambio promedio de una función $f$ entre dos puntos $x=a$ y $x=b$ se define como:
$$
\text{Tasa de cambio promedio} = \frac{f(b) - f(a)}{b - a}
$$

### La derivada como la pendiente de una curva
La derivada en un punto específico nos da la pendiente de la curva en ese punto. Si la derivada es positiva, la función está aumentando en ese punto; si es negativa, la función está disminuyendo. Si la derivada es cero, la función tiene un punto crítico, que podría ser un máximo, un mínimo o un punto de inflexión.

### La derivada y las ecuaciones de la recta tangente
La ecuación de la recta tangente a la curva en un punto $x=a$ se puede escribir utilizando la derivada:
$$
y - f(a) = f'(a)(x - a)
$$
Esta ecuación nos permite encontrar la recta tangente en cualquier punto de la curva, proporcionando una aproximación lineal de la función en ese punto.

#### Ejemplo de ecuación de la recta tangente

1. Para una función $h$, sabemos que $h(-2)=-5$ y $h'(-2)=-9$.

¿Cuál es la ecuación de la recta tangente a la gráfica de $h$ en $x=-2$?

Usamos la fórmula de la recta tangente:
$$
y - h(a) = h'(a)(x - a)
$$
Sustituyendo $a = -2$, $h(-2) = -5$ y $h'(-2) = -9$:
$$
y - (-5) = -9(x - (-2))
$$
Simplificando:
$$
y + 5 = -9(x + 2)
$$
$$
y + 5 = -9x - 18
$$
$$
y = -9x - 23
$$
Por lo tanto, la ecuación de la recta tangente a la gráfica de $h$ en $x=-2$ es:
$$
y = -9x - 23
$$

2. La recta tangente a la gráfica de la función 
$h$ en el punto 
$(-2,-4)$ pasa por el punto 
$(1,5)$.
Encuentra 
$h'(-2)$.

Usamos la fórmula de la pendiente:
$$
m = \frac{y_2 - y_1}{x_2 - x_1}
$$
Sustituyendo los puntos $(-2, -4)$ y $(1, 5)$:
$$
m = \frac{5 - (-4)}{1 - (-2)} = \frac{9}{3} = 3
$$
Por lo tanto, $h'(-2) = 3$.

#### Ejemplos de derivadas utilizando las reglas básicas
1. **Derivada de una potencia**:
   Sea $f(x) = x^3$. Usando la regla de la potencia:
   $$
   f'(x) = 3x^{2}
   $$
2. **Derivada de una suma**:
   Sea $f(x) = x^2 + 5x$. Usando la regla de la suma:
   $$
   f'(x) = 2x + 5
   $$
3. **Derivada de un producto**:
   Sea $f(x) = x^2 \cdot \sin(x)$. Usando la regla del producto:
   $$
   f'(x) = 2x \sin(x) + x^2 \cos(x)
   $$
4. **Derivada de un cociente**:
   Sea $f(x) = \frac{x^2}{\cos(x)}$. Usando la regla del cociente:
   $$
   f'(x) = \frac{2x \cos(x) + x^2 \sin(x)}{\cos^2(x)}
   $$
5. **Derivada de una función compuesta**:
   Sea $f(x) = \sin(x^2)$. Usando la regla de la cadena:
   $$
   f'(x) = \cos(x^2) \cdot 2x = 2x \cos(x^2)
   $$
Estos ejemplos ilustran cómo aplicar las reglas básicas de derivación para encontrar las derivadas de diversas funciones. Con práctica, calcular derivadas se vuelve una tarea más sencilla y automática.

---

## Definición de la derivada de una función y utilizar la notación de derivada

### La definición formal de la derivada como un límite

#### Pendiente de la tangente mediante límites
Consideremos una curva representada por una función $f(x)$. Si tomamos dos puntos en la curva, digamos $(a, f(a))$ y $(a+h, f(a+h))$, podemos calcular la pendiente de la línea secante que conecta estos dos puntos usando la fórmula de la pendiente:
$$\text{Pendiente tangente} = \frac{f(a+h) - f(a)}{(a+h) - a} = \frac{f(a+h) - f(a)}{h}$$

Para encontrar la pendiente en un punto específico, necesitamos considerar el límite cuando la distancia entre los dos puntos se acerca a cero.

La derivada de una función $f(x)$ en un punto $x=a$ se define formalmente como el límite:
$$
f'(a) = \lim_{h \to 0} \frac{f(a+h) - f(a)}{h}
$$

### Definición alternativa usando $x$ y $c$
Otra forma de expresar la definición de la derivada es utilizando $x$ y un punto fijo $c$. En este caso, la derivada de $f(x)$ en el punto $x=c$ se define como:
$$
f'(c) = \lim_{x \to c} \frac{f(x) - f(c)}{x - c}
$$

Inicialmente recordar. que si deseamos encontrar una pendiente, podriamos usar la formula de la pendiente entre dos puntos.

$$\text{Pendiente} = \frac{f(b) - f(a)}{b - a}$$

$$\text{Pendiente secante} = \lim_{x \to a} \frac{f(b) - f(a)}{b - a}$$

> esta formula funciona bien para lineas rectas, pero cuando trabajamos con curvas, la pendiente cambia en cada punto, por lo que necesitamos un nuevo enfoque.

#### Ejercicios:

1. Ayuda a calcular la derivada
$f'\left(4\right)$ para 
$f(x)=\sqrt{x}$?

Usamos la definición alternativa:
$$
f'\left(4\right) = \lim_{x \to 4} \frac{f\left(x\right) - f\left(4\right)}{x - 4}
$$
Sustituyendo $f(x) = \sqrt{x}$ y $f(4) = 2$:
$$
f'\left(4\right) = \lim_{x \to 4} \frac{\sqrt{x} - 2}{x - 4}
$$
Para simplificar esta expresión, multiplicamos el numerador y el denominador por el conjugado del numerador:
$$
f'\left(4\right) = \lim_{x \to 4} \frac{\sqrt{x} - 2}{x - 4} \cdot \frac{\sqrt{x} + 2}{\sqrt{x} + 2}
$$
$$
= \lim_{x \to 4} \frac{x - 4}{(x - 4)(\sqrt{x} + 2)} = \lim_{x \to 4} \frac{1}{\sqrt{x} + 2}
$$
Evaluando el límite cuando $x$ se acerca a 4:
$$
= \frac{1}{\sqrt{4} + 2} = \frac{1}{2 + 2} = \frac{1}{4}
$$
Por lo tanto, la derivada de $f(x) = \sqrt{x}$ en $x = 4$ es:
$$
f'\left(4\right) = \frac{1}{4}
$$

2. Encuentra $x = ?$ y $f(x) = ?$ en la siguiente expresión de la definición de la derivada:
$$
f'(1) = \lim_{h \to 0}\dfrac{\dfrac{1}{1+h}-1}{h}
$$
para encontrar x, primero identificamos la función $f(x)$ y el punto en el que se está evaluando la derivada.
Observamos que la expresión dentro del límite tiene la forma de la definición de la derivada:
$$
f'(1) = \lim_{h \to 0}\dfrac{\dfrac{1}{1+h}-1}{h}
$$
Por lo tanto, podemos identificar que:
- El punto en el que se evalúa la derivada es $x = 1$

Ahora, para encontrar la función $f(x)$, observamos la expresión $\dfrac{1}{1+h}$, que sugiere que $f(x) = \dfrac{1}{x}$, ya que al sustituir $x = 1 + h$, obtenemos $f(1 + h) = \dfrac{1}{1 + h}$.

### La derivada de x² en x=3 por medio de la definición formal
Vamos a calcular la derivada de la función $f(x) = x^2$ en el punto $x = 3$ utilizando la definición formal de la derivada.
Usamos la definición de la derivada:
$$
f'(a) = \lim_{h \to 0} \frac{f(a+h) - f(a)}{h}
$$
Sustituyendo $a = 3$ y $f(x) = x^2$:
$$
f'(3) = \lim_{h \to 0} \frac{(3+h)^2 - 3^2}{h}
$$
Expandiendo el numerador:
$$
= \lim_{h \to 0} \frac{(9 + 6h + h^2) - 9}{h}
$$
$$
= \lim_{h \to 0} \frac{6h + h^2}{h}
$$
Simplificando la fracción:
$$
= \lim_{h \to 0} \frac{6 + h}{1} = 6
$$
Por lo tanto, la derivada de $f(x) = x^2$ en $x = 3$ es:
$$
f'(3) = 6
$$

### La derivada de x² en cualquier punto por medio de la definición formal
Vamos a calcular la derivada de la función $f(x) = x^2$ en un punto general $x = a$ utilizando la definición formal de la derivada.
Usamos la definición de la derivada:
$$
f'(a) = \lim_{h \to 0} \frac{f(a+h) - f(a)}{h}
$$
Sustituyendo $f(x) = x^2$:
$$
f'(a) = \lim_{h \to 0} \frac{(a+h)^2 - a^2}{h}
$$
Expandiendo el numerador:
$$
= \lim_{h \to 0} \frac{(a^2 + 2ah + h^2) - a^2}{h}
$$
$$
= \lim_{h \to 0} \frac{2ah + h^2}{h}
$$
Simplificando la fracción:
$$
= \lim_{h \to 0} \frac{2a + h}{1} = 2a
$$
Por lo tanto, la derivada de $f(x) = x^2$ en $x = a$ es:
$$
f'(a) = 2a
$$
