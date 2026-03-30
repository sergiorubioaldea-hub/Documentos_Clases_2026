# Guía de Aprendizaje: Fundamentos Algebraicos para Funciones por Tramo
**Asignatura:** Electivo Límites, Derivadas e Integrales  
**Unidad:** Funciones y Modelamiento

---

## 1. Identificación
* **Objetivo de Aprendizaje (Curriculum):** OA 1. Utilizar diversas formas de representación al interpretar y resolver problemas que involucran funciones (lineales, cuadráticas, raíz cuadrada, racional, etc.).
* **Objetivo de la Guía:** Determinar dominio, recorrido y evaluación de funciones elementales de forma algebraica como preparación para el estudio de funciones definidas por partes y el concepto de límite.

---

## 2. Introducción Teórica
Antes de dividir una función en "trozos" o tramos, debemos dominar el comportamiento individual de cada "bloque de construcción". El análisis se divide en tres pilares:

1.  **Evaluación:** ¿Qué valor de $y$ obtengo al ingresar un $x$?
2.  **Dominio ($Dom f$):** ¿Qué valores de $x$ tienen permiso para entrar en la función? (Restricciones).
3.  **Recorrido ($Rec f$):** ¿Qué valores de $y$ resultan de ese dominio?

---

## 3. Bloques de Construcción: Funciones Relevantes

### A. La Función Lineal ($f(x) = mx + n$)
Es la más simple pero la más usada en tramos. 
* **Análisis:** No tiene restricciones. Su dominio y recorrido son siempre $\mathbb{R}$.
* **Importancia en Tramos:** Al restringir su dominio a un intervalo $[a, b]$, el recorrido se obtiene simplemente evaluando $f(a)$ y $f(b)$.

> **[INSERTAR AQUÍ: Captura de Geogebra de una función lineal f(x)=2x+1 restringida al intervalo [1, 3]]**

### B. La Función Cuadrática ($f(x) = ax^2 + bx + c$)
* **Dominio:** Siempre $\mathbb{R}$.
* **Recorrido:** Depende de la ordenada del vértice ($q$). 
    * Si $a > 0$, $Rec f = [q, +\infty[$
    * Si $a < 0$, $Rec f = ]-\infty, q]$
* **Fórmula del Vértice ($x_v$):** $x_v = \frac{-b}{2a}$

> **[INSERTAR AQUÍ: Captura de Geogebra de una parábola indicando el punto del vértice y cómo este limita el eje Y]**

### C. La Función Raíz Cuadrada ($f(x) = \sqrt{g(x)}$)
Aquí aparece la primera **restricción algebraica** real.
* **Condición de Dominio:** El argumento $g(x)$ debe ser mayor o igual a cero ($g(x) \geq 0$).
* **Recorrido:** Generalmente $[0, +\infty[$, a menos que haya traslaciones verticales.

> **[INSERTAR AQUÍ: Gráfico de f(x)=sqrt(x-2), mostrando que la curva nace en x=2 y no existe hacia la izquierda]**

### D. La Función Racional ($f(x) = \frac{p(x)}{q(x)}$)
* **Condición de Dominio:** El denominador **nunca** puede ser cero ($q(x) \neq 0$).
* **Recorrido:** Se encuentra despejando $x$ en función de $y$ y buscando las nuevas restricciones para $y$.

### E. Función Exponencial ($f(x) = a^x$ con $a > 0, a \neq 1$)
Es la función del "crecimiento explosivo". En el electivo, la verás principalmente como $f(x) = e^x$.
* **Dominio:** Siempre es $\mathbb{R}$. No hay restricción sobre qué número puedes poner en el exponente.
* **Recorrido:** Siempre son los reales positivos ($Rec f = ]0, +\infty[$). 
* **Clave para Tramos:** Como nunca toca el cero (asíntota horizontal), es vital para entender límites que tienden a cero o a infinito.

> **[INSERTAR AQUÍ: Gráfico de f(x)=e^x comparada con f(x)=2^x en Geogebra]**

### F. Función Logarítmica ($f(x) = \log_a(g(x))$)
Es la inversa de la exponencial y presenta una de las restricciones más fuertes.
* **Condición de Dominio:** El argumento **debe ser estrictamente mayor a cero** ($g(x) > 0$). No existe el logaritmo de cero ni de números negativos.
* **Recorrido:** Siempre es $\mathbb{R}$.
* **Clave para Tramos:** En funciones por tramos, el logaritmo suele usarse para generar asíntotas verticales.

> **[INSERTAR AQUÍ: Gráfico de f(x)=ln(x) mostrando la asíntota en el eje Y y cómo el dominio solo existe para x > 0]**

## 3. Cuadro Comparativo de Restricciones Algebraicas
Para evaluar funciones por tramos sin graficar, el estudiante debe chequear esta tabla antes de operar:

| Si la función tiene... | La restricción algebraica es... | Ejemplo de Dominio |
| :--- | :--- | :--- |
| **Denominador ($1/x$)** | Denominador $\neq 0$ | $x \in \mathbb{R} \setminus \{valor\}$ |
| **Raíz Par ($\sqrt{x}$)** | Interior $\geq 0$ | $[inicio, +\infty[$ |
| **Logaritmo ($\log x$)** | Interior $> 0$ | $]inicio, +\infty[$ |
| **Exponencial ($e^x$)** | **Sin restricción** | $\mathbb{R}$ |

---

## 4. Estrategia Algebraica: Cálculo de Recorrido sin Gráfica
Para encontrar el recorrido de forma analítica, sigue estos pasos:
1. Reemplaza $f(x)$ por $y$.
2. Despeja la variable $x$ (deja la $x$ sola a un lado de la igualdad).
3. Analiza la expresión resultante: ¿Hay alguna $y$ en un denominador o bajo una raíz par? Esa es tu restricción.

**Ejemplo:** $f(x) = \frac{1}{x-3}$
* $y = \frac{1}{x-3} \Rightarrow x-3 = \frac{1}{y} \Rightarrow x = \frac{1}{y} + 3$
* **Análisis:** Como $y$ quedó en el denominador, $y \neq 0$.
* **Resultado:** $Rec f = \mathbb{R} \setminus \{0\}$.

---

## 5. Ejercicios de Práctica

### I. Evaluación de Expresiones
Dada $f(x) = 3x^2 - 5$, determine de forma simplificada:
1. $f(-2) =$
2. $f(a + h) =$

### II. Dominio y Recorrido Analítico
Determine el Dominio y Recorrido de las siguientes funciones sin graficar:
1. $g(x) = \frac{2x}{x+4}$
2. $h(x) = \sqrt{3x - 9}$
3. $j(x) = x^2 - 4x + 5$ (Pista: Busca el vértice)

Determine el Dominio y Recorrido de las siguientes funciones analíticamente:

1.  **Función Exponencial:** $f(x) = e^{x-2} + 3$  
    *(Pista: Si $e^x$ siempre es $>0$, ¿qué pasa si le sumas 3?)*
2.  **Función Logarítmica:** $g(x) = \ln(x + 5)$  
    *(Pista: ¿Qué valores de $x$ hacen que $x+5$ sea mayor a cero?)*
3.  **Combinada:** $h(x) = \frac{1}{e^x - 1}$  
    *(Desafío: Aquí tienes una exponencial en un denominador. ¿Cuándo $e^x - 1 = 0$?)*
    
---
**Desafío para la próxima clase:** ¿Qué sucede con el recorrido de $f(x) = x^2$ si te digo que el dominio ya no es $\mathbb{R}$, sino que es solo el intervalo $[-1, 2]$? Piénsalo algebraicamente.