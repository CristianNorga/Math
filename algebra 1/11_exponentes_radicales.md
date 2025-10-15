# Exponentes y radicales
## Exponentes
Los exponentes son una forma de expresar la multiplicación repetida de un mismo número. Por ejemplo, $ a^n $ significa que el número $ a $ se multiplica por sí mismo $ n $ veces. Aquí hay algunas reglas básicas de los exponentes:
- **Producto de potencias con la misma base:** $ a^m \cdot a^n = a^{m+n} $
- **Cociente de potencias con la misma base:** $ \frac{a^m}{a^n} = a^{m-n} $ (donde $ m > n $)
- **Potencia de una potencia:** $ (a^m)^n = a^{m \cdot n} $
- **Potencia de un producto:** $ (ab)^n = a^n \cdot b^n $
- **Potencia de un cociente:** $ \left(\frac{a}{b}\right)^n = \frac{a^n}{b^n} $
- **Exponente cero:** $ a^0 = 1 $ (siempre que $ a \neq 0 $)
- **Exponente negativo:** $ a^{-n} = \frac{1}{a^n} $ (siempre que $ a \neq 0 $)

### Multiplicar y dividir potencias con exponentes enteros
Los exponentes enteros son aquellos que son números enteros, ya sean positivos, negativos o cero. Aquí hay una breve explicación de cada caso:
- **Exponentes positivos:** Indican la multiplicación repetida del número base.

**Ejemplo #1:**
$$ 2^3 = 2 \cdot 2 \cdot 2 = 8 $$

**Ejemplo #2:**
$$ \frac{12^{-7}}{12^{-5}} = 12^{-7 - (-5)} = 12^{-2} = \frac{1}{12^2} = \frac{1}{144} $$
> Nota: El exponente negativo indica que debemos tomar el recíproco de la base elevada al exponente positivo.

**Ejemplo #3 (con variables):**
$$ \frac{x^{-20}}{x^5} $$
$$ = x^{-20 - 5} = x^{-25} = \frac{1}{x^{25}} $$

**Ejemplo #4:**
$$ (4^{11})(4^{-8}) $$
$$ = 4^{11 + (-8)} = 4^3 = 64 $$

### Potencias de productos y cocientes (exponentes enteros)
Cuando se tiene una potencia de un producto o un cociente, se aplica el exponente a cada factor del producto o del cociente.

**Ejemplo #1:**
$$ (3^{-8} \cdot 7^{3})^{-2} $$
$$ = 3^{-8 \cdot (-2)} \cdot 7^{3 \cdot (-2)} $$
$$ = 3^{16} \cdot 7^{-6} $$

Se puede simplificar:

$$ = \frac{3^{16}}{7^{6}} $$

> Nota: El exponente negativo en el segundo término indica que debemos tomar el recíproco de la base elevada al exponente positivo.

Donde a su vez es equivalente a:
$$ \frac{3^{16}}{7^{6}} = (\frac{7^{3}}{3^{8}})^{-2}$$

**Ejemplo #2:**
$$ (a^{-2} \cdot 8^{7})^{2} $$
$$ = a^{-2 \cdot 2} \cdot 8^{7 \cdot 2} $$
$$ = a^{-4} \cdot 8^{14} $$
$$ = \frac{8^{14}}{a^{4}} $$

**Ejemplo #3:**
$$ (\frac{2^{-10}}{4^{2}})^{7} $$
$$ = \frac{2^{-10 \cdot 7}}{4^{2 \cdot 7}} $$
$$ = \frac{2^{-70}}{4^{14}} $$

Ahora es posible simplificarlo llevando la potencia del dominador `4` a base `2`:

$$ = \frac{2^{-70}}{(2^2)^{14}} $$
$$ = \frac{2^{-70}}{2^{28}} $$
$$ = 2^{-70 - 28} $$
$$ = 2^{-98} $$

**Ejemplo #4:**

$$ (\frac{3^{6}}{y^{-5}})^{2} $$
$$ = \frac{(3^{6})^{2}}{(y^{-5})^{2}} $$
$$ = \frac{3^{12}}{y^{-10}} $$
$$ = 3^{12} \cdot y^{10} $$

**Equivalencia #1:**
$$ \frac{5^2}{5^8} = 5^{2-8} = 5^{-6} = \frac{1}{5^{6}} = (5^{2})^{-3} $$

Explicación:
- **$ \frac{1}{5^{6}} $** indica que debemos tomar el recíproco de la base elevada al exponente positivo. 
- **$ (5^{2})^{-3} $** indica que debemos tomar el recíproco de la base elevada al exponente positivo.

Resolucion detallada:
$$ \frac{5^2}{5^8} $$
$$ = 5^{2-8} $$
$$ = 5^{-6} $$
$$ = \frac{1}{5^{6}} $$
$$ = (5^{2})^{-3} $$

**Equivalencia #2:**
$$ 4^{-2} \cdot 7^{-2} = \frac{1}{4^{2}} \cdot \frac{1}{7^{2}} = \frac{1}{4^{2} \cdot 7^{2}} = (4 \cdot 7)^{-2} = 28^{-2} $$

Explicación:
- **$ 28^{-2} $** indica que debemos tomar el recíproco de la base elevada al exponente positivo.

Resolucion detallada:
$$ 4^{-2} \cdot 7^{-2} $$
$$ = \frac{1}{4^{2}} \cdot \frac{1}{7^{2}} $$
$$ = \frac{1}{4^{2} \cdot 7^{2}} $$
$$ = (4 \cdot 7)^{-2} $$
$$ = 28^{-2} $$

> donde a su vez es equivalente a:
$$ \frac{1}{(28)^{2}} $$

> Nota: El exponente negativo indica que debemos tomar el recíproco de la base elevada al exponente positivo.

## Radicales
Los radicales son la operación inversa de los exponentes. La raíz cuadrada de un número $ a $ se denota como $ \sqrt{a} $ y representa un número que, al ser multiplicado por sí mismo, da como resultado $ a $. Aquí hay algunas reglas básicas de los radicales:
- **Producto de radicales:** $ \sqrt{a} \cdot \sqrt{b} = \sqrt{ab} $
- **Cociente de radicales:** $ \frac{\sqrt{a}}{\sqrt{b}} = \sqrt{\frac{a}{b}} $ (donde $ b \neq 0 $)
- **Radical de un producto:** $ \sqrt{ab} = \sqrt{a} \cdot \sqrt{b} $
- **Radical de un cociente:** $ \sqrt{\frac{a}{b}} = \frac{\sqrt{a}}{\sqrt{b}} $ (donde $ b \neq 0 $)
- **Radical de una potencia:** $ \sqrt[n]{a^m} = a^{\frac{m}{n}} $
- **Radical de un radical:** $ \sqrt[m]{\sqrt[n]{a}} = \sqrt[m \cdot n]{a} $