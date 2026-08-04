# Guía de Ejercicios: De la Regla de Laplace al Modelo de Bernoulli

**Nombre:** __________________________________ **Curso:** 4° Medio **Fecha:** ________

## Objetivo
*   Relacionar la Regla de Laplace con el Modelo de Probabilidad de Bernoulli.
*   Identificar los conceptos de "éxito" ($p$) y "fracaso" ($q$) en diversos contextos.
*   Construir la función de probabilidad de Bernoulli garantizando que $p + q = 1$.

---

## Ítem I: Identificación de Éxito y Fracaso

Para cada una de las siguientes situaciones, se define un experimento y lo que consideraremos como "éxito". Determina el valor de la probabilidad de éxito ($p$), la probabilidad de fracaso ($q$) y verifica que la suma sea igual a $1$.

1.  **Lanzamiento de un dado:** Se lanza un dado tradicional de 6 caras. Se define como éxito "obtener un número mayor que 4".
    *   $p =$
    *   $q =$
    *   Verificación ($p + q = 1$): 

2.  **Prueba de alternativas:** Un estudiante responde una pregunta de opción múltiple al azar. La pregunta tiene 5 alternativas y solo una es correcta. Se define como éxito "achuntar a la respuesta correcta".
    *   $p =$
    *   $q =$
    *   Verificación ($p + q = 1$):

3.  **Control de calidad:** En una fábrica, se sabe que el $4\%$ de las ampolletas producidas salen defectuosas. Se extrae una ampolleta al azar. Se define como éxito "que la ampolleta esté defectuosa" (Recuerda: el "éxito" estadístico es lo que estamos buscando observar).
    *   $p =$
    *   $q =$
    *   Verificación ($p + q = 1$):

---

## Ítem II: Laplace vs. Bernoulli

Lee con atención el siguiente problema y resuélvelo desde los dos enfoques estudiados.

**Problema:** De una baraja de naipe inglés (52 cartas en total: 13 de corazones, 13 de diamantes, 13 de tréboles y 13 de picas), se extrae una carta al azar. Queremos calcular la probabilidad de que la carta extraída sea de **corazones**.

**A. Desde el punto de vista de Laplace:**
1.  ¿Cuál es el número de casos posibles?
2.  ¿Cuál es el número de casos favorables?
3.  Aplica la Regla de Laplace para encontrar la probabilidad de sacar un corazón.

**B. Desde el punto de vista de Bernoulli:**
Define una variable aleatoria $X$ tal que:
*   $X = 1$ si la carta es de corazones (Éxito).
*   $X = 0$ si la carta NO es de corazones (Fracaso).

1.  ¿Cuánto vale $p = P(X=1)$? (Simplifica la fracción).
2.  ¿Cuánto vale $q = P(X=0)$? 
3.  Escribe el modelo matemático completo indicando $X \sim \text{Bernoulli}(p)$.

---

## Ítem III: Construcción de la Función de Probabilidad

El modelo de Bernoulli se define mediante la siguiente función de probabilidad, donde $x \in \{0, 1\}$:

$$P(X=x) = p^x \cdot (1-p)^{1-x}$$

Para cada uno de los siguientes experimentos, define la variable aleatoria $X$, identifica el parámetro $p$ y escribe la función de probabilidad específica reemplazando los valores correspondientes.

1.  **La moneda cargada:** Tienes una moneda trucada donde la probabilidad de obtener "Cara" es el triple que la de obtener "Sello". Si lanzas la moneda y defines como éxito obtener "Cara":
    *   ¿Cuál es el valor de $p$ y $q$? (Pista: plantea la ecuación $p = 3q$ sabiendo que $p + q = 1$).
    *   Función de probabilidad $P(X=x)$:

2.  **El semáforo:** Un estudiante llega todos los días al mismo semáforo de camino al colegio. Históricamente, el semáforo está en verde el $65\%$ de las veces que él llega. Se define como éxito "encontrar el semáforo en verde".
    *   $p$ (en forma decimal):
    *   $q$ (en forma decimal):
    *   Función de probabilidad $P(X=x)$:

3.  **Evaluación de la función:** Usando la función que construiste en el problema anterior (El semáforo), calcula algebraicamente el valor de $P(X=1)$ y $P(X=0)$ reemplazando la $x$ en la fórmula. ¿Coinciden los resultados con tu $p$ y tu $q$? Demuestra tu desarrollo.
   
# Pauta de Corrección: De la Regla de Laplace al Modelo de Bernoulli

## Ítem I: Identificación de Éxito y Fracaso

**1. Lanzamiento de un dado:** 
Éxito = "obtener un número mayor que 4" (es decir, obtener un 5 o un 6).
*   $p = \frac{2}{6} = \frac{1}{3}$
*   $q = \frac{4}{6} = \frac{2}{3}$
*   **Verificación:** $\frac{1}{3} + \frac{2}{3} = \frac{3}{3} = 1$

**2. Prueba de alternativas:** 
Éxito = "achuntar a la respuesta correcta" (1 correcta entre 5 opciones).
*   $p = \frac{1}{5} = 0,2$
*   $q = \frac{4}{5} = 0,8$
*   **Verificación:** $0,2 + 0,8 = 1$ (o $\frac{1}{5} + \frac{4}{5} = \frac{5}{5} = 1$)

**3. Control de calidad:** 
Éxito = "que la ampolleta esté defectuosa".
*   $p = \frac{4}{100} = 0,04$ (o simplificado $\frac{1}{25}$)
*   $q = \frac{96}{100} = 0,96$ (o simplificado $\frac{24}{25}$)
*   **Verificación:** $0,04 + 0,96 = 1$

---

## Ítem II: Laplace vs. Bernoulli

**A. Desde el punto de vista de Laplace:**
1.  **Casos posibles:** 52 (el total de cartas en la baraja).
2.  **Casos favorables:** 13 (el total de cartas de corazones).
3.  **Regla de Laplace:** $P(\text{corazón}) = \frac{\text{Casos favorables}}{\text{Casos posibles}} = \frac{13}{52} = \frac{1}{4}$ (o $0,25$).

**B. Desde el punto de vista de Bernoulli:**
1.  **Valor de $p$:** $p = P(X=1) = \frac{13}{52} = \frac{1}{4}$
2.  **Valor de $q$:** $q = P(X=0) = \frac{52 - 13}{52} = \frac{39}{52} = \frac{3}{4}$ (también calculable como $1 - \frac{1}{4}$)
3.  **Modelo matemático:** $X \sim \text{Bernoulli}(\frac{1}{4})$ o $X \sim \text{Bernoulli}(0,25)$.

---

## Ítem III: Construcción de la Función de Probabilidad

**1. La moneda cargada:**
*   **Cálculo de $p$ y $q$:** 
    Sabemos que $p = 3q$ y que $p + q = 1$. 
    Reemplazando la primera ecuación en la segunda:
    $3q + q = 1$
    $4q = 1 \implies q = \frac{1}{4}$
    Por lo tanto, $p = 3 \cdot (\frac{1}{4}) = \frac{3}{4}$.
*   **Función de probabilidad:** 
    $P(X=x) = \left(\frac{3}{4}\right)^x \cdot \left(\frac{1}{4}\right)^{1-x} \quad \text{para } x \in \{0, 1\}$

**2. El semáforo:**
*   **$p$ (en forma decimal):** $0,65$
*   **$q$ (en forma decimal):** $0,35$ (calculado como $1 - 0,65$)
*   **Función de probabilidad:** 
    $P(X=x) = (0,65)^x \cdot (0,35)^{1-x} \quad \text{para } x \in \{0, 1\}$

**3. Evaluación de la función:**
Usando la función $P(X=x) = (0,65)^x \cdot (0,35)^{1-x}$:

*   **Para $x = 1$ (Éxito):**
    $P(X=1) = (0,65)^1 \cdot (0,35)^{1-1}$
    $P(X=1) = (0,65)^1 \cdot (0,35)^0$
    $P(X=1) = 0,65 \cdot 1 = 0,65$
    *(Coincide con el valor de $p$)*

*   **Para $x = 0$ (Fracaso):**
    $P(X=0) = (0,65)^0 \cdot (0,35)^{1-0}$
    $P(X=0) = (0,65)^0 \cdot (0,35)^1$
    $P(X=0) = 1 \cdot 0,35 = 0,35$
    *(Coincide con el valor de $q$)*