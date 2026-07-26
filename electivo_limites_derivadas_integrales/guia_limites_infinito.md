# Guía de Ejercicios: Límites al Infinito y Asíntotas Horizontales

**Objetivo:** Comprender y calcular límites al infinito de diversas funciones, analizar su relación geométrica con las asíntotas horizontales y reflexionar sobre el comportamiento asintótico a través de herramientas gráficas y comparación de magnitudes.

---

### I. Cálculo de Límites en Funciones Polinómicas y Racionales
Calcula el valor de los siguientes límites detallando tu procedimiento algebraico (por ejemplo, factorizando o dividiendo por la mayor potencia de $x$):

1. $$ \lim_{x \to \infty} ( -2x^3 + 5x^2 - 4x + 1 ) $$
2. $$ \lim_{x \to \infty} \frac{3x^2 - 5x + 2}{7x^2 + 4x - 1} $$
3. $$ \lim_{x \to -\infty} \frac{4x^3 - 1}{2x^2 + x} $$
4. $$ \lim_{x \to \infty} \frac{x^2 + 8}{x^4 - 3x^2 + 5} $$
5. $$ \lim_{x \to -\infty} \frac{\sqrt{9x^2 + 2}}{4x - 3} $$

### II. Límites al Infinito de Funciones Trascendentes
Determina los siguientes límites utilizando las propiedades de las funciones exponenciales, logarítmicas y trigonométricas, o teoremas pertinentes (como el Teorema del Sándwich o Compresión):

1. $$ \lim_{x \to \infty} e^{-3x} $$
2. $$ \lim_{x \to \infty} \ln\left( \frac{5}{x} \right) $$
3. $$ \lim_{x \to \infty} \frac{\sin(2x)}{x} $$
4. $$ \lim_{x \to -\infty} (5^x - 2) $$
5. $$ \lim_{x \to \infty} \arctan(x) $$

### III. Comparación de Magnitudes (Jerarquía de Infinitos)
Analiza y calcula los siguientes límites comparando la velocidad de crecimiento (orden de magnitud) de las funciones involucradas al tender al infinito:

1. $$ \lim_{x \to \infty} (e^x - x^3) $$
   *(Pista: Factoriza el término de mayor crecimiento, en este caso $e^x$, para analizar el comportamiento del factor resultante).*
2. $$ \lim_{x \to \infty} \frac{\ln(x)}{\sqrt{x}} $$
   *(Pista: Considera la jerarquía de infinitos entre las funciones logarítmicas y las funciones potencia / raíces cuando $x \to \infty$).*

### IV. Análisis de Asíntotas Horizontales
Utilizando el concepto de límite al infinito, resuelve los siguientes problemas:

1. Determina la ecuación de la asíntota horizontal de la función $f(x) = \frac{4x - 7}{2x + 3}$.
2. Encuentra **todas** las asíntotas horizontales de la función $g(x) = \frac{3e^x}{e^x + 5}$. *(Pista: debes evaluar qué ocurre tanto cuando $x \to \infty$ como cuando $x \to -\infty$)*.
3. Analiza si la función $h(x) = \frac{x}{\sqrt{x^2 + 1}}$ posee asíntotas horizontales y justifica tu respuesta calculando los límites respectivos.

### V. Análisis Gráfico con GeoGebra
Abre el software GeoGebra, grafica las siguientes funciones e interactúa con el plano cartesiano para responder las preguntas:

1. **Comportamiento asintótico:** Grafica la función $f(x) = \frac{3x^2 - 12}{x^2 + 2}$. Observa qué sucede con la curva a medida que te desplazas hacia los extremos del eje $X$. Ingresa también la recta $y = 3$. ¿Qué relación geométrica observas entre la curva y la recta?
2. **Oscilación amortiguada:** Grafica $g(x) = e^{-0.2x} \cos(x)$. Haz un alejamiento (zoom out) en la vista gráfica. ¿Qué ocurre con la amplitud de la onda a medida que $x \to \infty$? Con base en lo que ves, ¿cuál es el valor de $\lim_{x \to \infty} g(x)$?
3. **Límites que definen constantes:** Grafica $h(x) = \left(1 + \frac{1}{x}\right)^x$. Usa la herramienta de tabla de valores o desplaza la gráfica hacia valores muy grandes de $x$. ¿A qué número irracional famoso se aproxima esta función?

### VI. Análisis Conceptual
Responde de forma fundamentada. Puedes apoyarte en ejemplos gráficos o algebraicos:

1. Si sabemos que $\lim_{x \to \infty} f(x) = L$, ¿significa esto que la gráfica de la función $f$ **nunca** puede cruzar la recta $y = L$? Justifica tu respuesta (si crees que es falso, proporciona un contraejemplo gráfico).
2. Imagina que estamos modelando el crecimiento de una población de bacterias en el tiempo ($t$). Explica con tus propias palabras la diferencia conceptual entre obtener como resultado $\lim_{t \to \infty} P(t) = \infty$ y obtener $\lim_{t \to \infty} P(t) = C$ (donde $C$ es una constante).
3. Sabemos que el límite $\lim_{x \to \infty} \cos(x)$ no existe. Explica con tus propias palabras por qué ocurre esto basándote en la definición intuitiva de límite y en el comportamiento de la función.

# Pauta de Corrección: Límites al Infinito y Asíntotas Horizontales

---

### I. Cálculo de Límites en Funciones Polinómicas y Racionales

**1.** 
$$ \lim_{x \to \infty} ( -2x^3 + 5x^2 - 4x + 1 ) $$

**Desarrollo:** El comportamiento de una función polinómica en el infinito está dominado por el término de mayor grado.
$$ \lim_{x \to \infty} x^3 \left( -2 + \frac{5}{x} - \frac{4}{x^2} + \frac{1}{x^3} \right) $$
Al evaluar en infinito, los términos con $x$ en el denominador tienden a cero: $\infty \cdot (-2 + 0 - 0 + 0) = -\infty$.
**Respuesta:** $-\infty$

**2.** 
$$ \lim_{x \to \infty} \frac{3x^2 - 5x + 2}{7x^2 + 4x - 1} $$
**Desarrollo:** Dividimos numerador y denominador por la mayor potencia de $x$ ($x^2$):
$$ \lim_{x \to \infty} \frac{\frac{3x^2}{x^2} - \frac{5x}{x^2} + \frac{2}{x^2}}{\frac{7x^2}{x^2} + \frac{4x}{x^2} - \frac{1}{x^2}} = \lim_{x \to \infty} \frac{3 - \frac{5}{x} + \frac{2}{x^2}}{7 + \frac{4}{x} - \frac{1}{x^2}} $$
Los términos con $x$ en el denominador tienden a cero.
**Respuesta:** $\frac{3}{7}$

**3.** 
$$ \lim_{x \to -\infty} \frac{4x^3 - 1}{2x^2 + x} $$
**Desarrollo:** El grado del numerador (3) es mayor que el del denominador (2). Dividiendo por $x^2$:
$$ \lim_{x \to -\infty} \frac{4x - \frac{1}{x^2}}{2 + \frac{1}{x}} = \frac{-\infty - 0}{2 + 0} $$
**Respuesta:** $-\infty$

**4.** 
$$ \lim_{x \to \infty} \frac{x^2 + 8}{x^4 - 3x^2 + 5} $$
**Desarrollo:** El grado del denominador (4) es mayor que el del numerador (2). Al dividir por $x^4$:
$$ \lim_{x \to \infty} \frac{\frac{1}{x^2} + \frac{8}{x^4}}{1 - \frac{3}{x^2} + \frac{5}{x^4}} = \frac{0 + 0}{1 - 0 + 0} $$
**Respuesta:** $0$

**5.** 
$$ \lim_{x \to -\infty} \frac{\sqrt{9x^2 + 2}}{4x - 3} $$
**Desarrollo:** *¡Cuidado con el signo!* Como $x \to -\infty$, asumimos $x < 0$, por lo que $x = -\sqrt{x^2}$. Dividimos numerador y denominador por $x$.
En el numerador, dividir por $x$ es equivalente a dividir el interior de la raíz por $x^2$ pero sacando un signo negativo:
$$ \lim_{x \to -\infty} \frac{ \frac{\sqrt{9x^2 + 2}}{-\sqrt{x^2}} }{ \frac{4x - 3}{x} } = \lim_{x \to -\infty} \frac{ -\sqrt{9 + \frac{2}{x^2}} }{ 4 - \frac{3}{x} } $$
Evaluando el límite: $\frac{-\sqrt{9 + 0}}{4 - 0} = -\frac{3}{4}$.
**Respuesta:** $-\frac{3}{4}$

---

### II. Límites al Infinito de Funciones Trascendentes

**1.** 
$$ \lim_{x \to \infty} e^{-3x} $$
**Desarrollo:** $e^{-3x} = \frac{1}{e^{3x}}$. Si $x \to \infty$, $e^{3x} \to \infty$. Por lo tanto, $1 / \infty \to 0$.
**Respuesta:** $0$

**2.** 
$$ \lim_{x \to \infty} \ln\left( \frac{5}{x} \right) $$
**Desarrollo:** Cuando $x \to \infty$, el argumento $\frac{5}{x}$ se acerca a $0$ por la derecha ($0^+$). El logaritmo natural de un número que tiende a $0^+$ es $-\infty$.
**Respuesta:** $-\infty$

**3.** 
$$ \lim_{x \to \infty} \frac{\sin(2x)}{x} $$
**Desarrollo:** Se utiliza el Teorema del Sándwich. Sabemos que $-1 \leq \sin(2x) \leq 1$. Dividiendo por $x$ (con $x>0$):
$$ -\frac{1}{x} \leq \frac{\sin(2x)}{x} \leq \frac{1}{x} $$
Como $\lim_{x \to \infty} -\frac{1}{x} = 0$ y $\lim_{x \to \infty} \frac{1}{x} = 0$, el límite central también es $0$.
**Respuesta:** $0$

**4.** 
$$ \lim_{x \to -\infty} (5^x - 2) $$
**Desarrollo:** Cuando $x \to -\infty$, la expresión $5^x = \frac{1}{5^{-x}} \to 0$. Por lo tanto, el límite es $0 - 2$.
**Respuesta:** $-2$

**5.** 
$$ \lim_{x \to \infty} \arctan(x) $$
**Desarrollo:** Por definición de la función arcotangente, a medida que el valor de entrada crece hacia el infinito positivo, el ángulo se acerca asintóticamente a $\frac{\pi}{2}$ radianes (90°).
**Respuesta:** $\frac{\pi}{2}$

---

### III. Comparación de Magnitudes (Jerarquía de Infinitos)

**1.** 
$$ \lim_{x \to \infty} (e^x - x^3) $$
**Desarrollo:** La función exponencial crece mucho más rápido que cualquier función polinómica. Factorizamos el término dominante ($e^x$):
$$ \lim_{x \to \infty} e^x \left( 1 - \frac{x^3}{e^x} \right) $$
Por jerarquía de infinitos, $\lim_{x \to \infty} \frac{x^3}{e^x} = 0$. La expresión queda $\infty \cdot (1 - 0) = \infty$.
**Respuesta:** $\infty$

**2.** 
$$ \lim_{x \to \infty} \frac{\ln(x)}{\sqrt{x}} $$
**Desarrollo:** La función logarítmica crece más lentamente que cualquier función potencia o raíz cuadrada positiva (cuando $x \to \infty$). Por jerarquía de infinitos, el denominador domina.
**Respuesta:** $0$

---

### IV. Análisis de Asíntotas Horizontales

**1.** $f(x) = \frac{4x - 7}{2x + 3}$
**Desarrollo:** Calculamos los límites hacia $\pm\infty$. Al tener igual grado, el límite es el cociente de los coeficientes principales: $\frac{4}{2} = 2$.
**Respuesta:** La asíntota horizontal es la recta $y = 2$.

**2.** $g(x) = \frac{3e^x}{e^x + 5}$
**Desarrollo:** Evaluamos ambos extremos.
Hacia $+\infty$: Dividimos por $e^x \rightarrow \lim_{x \to \infty} \frac{3}{1 + \frac{5}{e^x}} = \frac{3}{1+0} = 3$.
Hacia $-\infty$: $e^x \to 0 \rightarrow \lim_{x \to -\infty} \frac{3(0)}{0 + 5} = \frac{0}{5} = 0$.
**Respuesta:** Tiene dos asíntotas horizontales distintas: $y = 3$ y $y = 0$.

**3.** $h(x) = \frac{x}{\sqrt{x^2 + 1}}$
**Desarrollo:** Hacia $+\infty$: $\lim_{x \to \infty} \frac{x}{\sqrt{x^2(1+\frac{1}{x^2})}} = \lim_{x \to \infty} \frac{x}{x\sqrt{1+\frac{1}{x^2}}} = \frac{1}{1} = 1$.
Hacia $-\infty$: Como $x < 0$, $\sqrt{x^2} = -x$. $\lim_{x \to -\infty} \frac{x}{-x\sqrt{1+\frac{1}{x^2}}} = \frac{1}{-1} = -1$.
**Respuesta:** Sí posee asíntotas. Son $y = 1$ y $y = -1$.

---

### V. Análisis Gráfico con GeoGebra

**1. Comportamiento asintótico:**
**Respuesta esperada:** Los estudiantes deben observar que a medida que $x$ toma valores muy grandes (positivos o negativos), la curva de $f(x)$ se "aplana" y se acerca cada vez más a la recta roja $y = 3$ sin separarse de ella. Geométricamente, $y = 3$ actúa como un límite o tope para la función en los extremos.

**2. Oscilación amortiguada:**
**Respuesta esperada:** La amplitud de las ondas (las "olas" del coseno) se va reduciendo (comprimiendo) progresivamente hacia el eje X. Al tender a infinito, la oscilación desaparece. Por observación gráfica, $\lim_{x \to \infty} g(x) = 0$.

**3. Límites que definen constantes:**
**Respuesta esperada:** Al analizar la tabla o ir muy a la derecha, el valor en $Y$ se estabiliza alrededor de $2.71828...$ El número irracional famoso al que se aproxima es el número de Euler ($e$).

---

### VI. Análisis Conceptual

**1. Cruce de asíntotas:**
**Respuesta esperada:** Es **Falso**. Una asíntota horizontal describe el comportamiento "en los extremos" (cuando $x \to \infty$), no el comportamiento local. Una función puede cruzar su asíntota horizontal muchas veces. *Contraejemplo válido:* Cualquier función de oscilación amortiguada como la del ítem V.2 ($y = e^{-0.2x} \cos(x)$ cruza infinitas veces el eje $X$ que es su asíntota horizontal $y=0$), o $f(x) = \frac{\sin(x)}{x}$.

**2. Población de bacterias:**
**Respuesta esperada:** Si el límite es $\infty$, significa que la población crecerá indefinidamente sin ninguna restricción, descontroladamente (ideal para modelos teóricos a corto plazo o con recursos infinitos). Si el límite es una constante $C$, significa que el crecimiento se estanca o estabiliza; la población tiene un tope máximo (conocido como capacidad de carga), dictado por recursos limitados como espacio o alimento.

**3. Inexistencia del límite del coseno:**
**Respuesta esperada:** La definición intuitiva de límite exige que la función "se acerque y se estabilice" en torno a un único valor fijo $L$ a medida que $x$ crece. Sin embargo, la función $\cos(x)$ es periódica; sigue subiendo a $1$ y bajando a $-1$ para siempre. Como nunca se detiene en un único número, no existe convergencia a un valor único y, por ende, el límite no existe.