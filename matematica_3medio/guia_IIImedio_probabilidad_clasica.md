# Guía de Estudio: Probabilidad Clásica y Regla de Laplace

Esta guía resume los conceptos fundamentales para comprender la probabilidad como una proporción de incertidumbre, sentando las bases para la toma de decisiones.

---

## 1. Conceptos Fundamentales: El "Terreno de Juego"

Antes de realizar cálculos, es esencial definir los elementos básicos de un experimento:

* **Experimento Aleatorio:** Aquel cuyo resultado no se puede predecir con total certeza, como lanzar un dado.
* **Espacio Muestral ($\Omega$):** El conjunto que agrupa **todos** los resultados posibles de un experimento. Se considera el "universo total".
* **Evento o Suceso ($A$):** Un subconjunto específico del espacio muestral; representa lo que queremos que ocurra.

> **Nota clave:** Entender que el espacio muestral es el universo total es vital. Más adelante, verás que la probabilidad condicional lo que hace es "encoger" este universo.

---

## 2. La Regla de Laplace

Se aplica exclusivamente cuando todos los sucesos son **equiprobables** (tienen la misma probabilidad de ocurrir).

$$P(A) = \frac{\text{Número de casos favorables}}{\text{Número de casos posibles}}$$ 

### Propiedades Esenciales
1.  **Rango:** $0 \leq P(A) \leq 1$.
2.  **Evento Imposible ($P(\emptyset) = 0$):** El suceso no puede ocurrir.
3.  **Evento Seguro ($P(\Omega) = 1$):** El suceso ocurrirá siempre.
4.  **Evento Complementario ($A^c$):** La probabilidad de que NO ocurra $A$ es $P(A^c) = 1 - P(A)$. Esta propiedad es fundamental para resolver problemas complejos.

---

## 3. Ejemplos de Aplicación

### Ejemplo 1: El dado de 6 caras
¿Cuál es la probabilidad de obtener un número primo?
* $\Omega = \{1, 2, 3, 4, 5, 6\} \rightarrow n(\Omega) = 6$.
* $A = \{2, 3, 5\} \rightarrow n(A) = 3$.
* **Cálculo:** $P(A) = \frac{3}{6} = 0.5 = 50\%$.

### Ejemplo 2: Baraja Española (40 cartas)
¿Probabilidad de sacar un "Rey" o un "As"?  
* Casos posibles: 40.
* Casos favorables: 4 Reyes + 4 Ases = 8.
* **Cálculo:** $P(A) = \frac{8}{40} = \frac{1}{5} = 0.2$.

---

## 4. Ejercicios de Práctica

Resuelve los siguientes desafíos expresando tus resultados en **fracción, decimal y porcentaje**:

1.  **Lanzamiento de Dos Monedas:** Calcula la probabilidad de obtener al menos una cara. 
    *(Pista: El espacio muestral es $\Omega = \{CC, CX, XC, XX\})$*.
2.  **Suma de Dados:** Al lanzar dos dados, ¿cuál es la probabilidad de que la suma sea 7? 
    *(Se recomienda usar una tabla de doble entrada)*.
3.  **La Urna:** En una urna hay 5 bolitas rojas, 3 azules y 2 verdes.
    * a) Probabilidad de sacar una roja.
    * b) Probabilidad de **no** sacar una azul.
## III. Ejercicios de Aplicación (Ampliación)
Resuelve los siguientes desafíos expresando tus resultados en **fracción, decimal y porcentaje**.
1. **Lanzamiento de Dos Monedas:** Calcula la probabilidad de obtener al menos una cara.*(Pista: El espacio muestral es $\Omega = \{CC, CX, XC, XX\})$*.
2. **Suma de Dados:** Al lanzar dos dados, ¿cuál es la probabilidad de que la suma sea 7?.*(Uso de tabla de doble entrada recomendado)*.
3. **La Urna con Bolitas:** En una urna hay 5 bolitas rojas, 3 azules y 2 verdes.
    *a) Probabilidad de sacar una roja.
    *b) Probabilidad de no sacar una azul.
4. **El Dado de 6 Caras:** ¿Cuál es la probabilidad de obtener un número que sea múltiplo de 3?.
5. **Extracción de Cartas:** En una baraja española de 40 cartas, ¿cuál es la probabilidad de extraer una "Figura" (Sota, Caballo o Rey)?.
6. **Lanzamiento de una Moneda y un Dado:** Si lanzas una moneda y un dado simultáneamente, ¿cuál es la probabilidad de obtener "Cara" y un número mayor a 4?.
7. **Dígitos Aleatorios:** Si se elige un número al azar del 1 al 20, ¿cuál es la probabilidad de que sea un número primo?.
8. **Eventos Complementarios:** Si la probabilidad de que llueva mañana es de $3/10$, ¿cuál es la probabilidad de que sea un día despejado?.
9. **Bolas en la Urna (Variación):** Usando la misma urna (5 rojas, 3 azules, 2 verdes), ¿cuál es la probabilidad de que al sacar una bola, esta sea roja o verde?.
10. **Suma de Dados (Extensión):** Al lanzar dos dados, ¿cuál es la probabilidad de que la suma sea un número par?.
### Ejercicios Adicionales

11. **Lanzamiento de 3 Monedas:** 
    * a) Escribe el espacio muestral $\Omega$ de forma extensiva.
    * b) Indica su cardinalidad $n(\Omega)$.
    * c) Calcula la probabilidad de obtener exactamente 2 caras.

12. **Extracción con Reposición (Regla Multiplicativa):** En una urna hay 4 bolitas blancas y 6 negras. Si se extraen dos bolitas al azar, devolviendo la primera antes de sacar la segunda:
    * ¿Cuál es la probabilidad de que ambas sean blancas?
    * ¿Cuál es la probabilidad de que la primera sea negra y la segunda blanca?

13. **El Evento Imposible:** En un mazo de cartas españolas (40 cartas), ¿cuál es la probabilidad de extraer un "8 de tréboles"? [cite_start]Justifica tu respuesta usando el concepto de evento imposible[cite: 10, 12].

14. **Probabilidad Complementaria en el Aula:** En un curso de 40 estudiantes, la probabilidad de elegir un alumno al azar que use anteojos es de $3/8$. [cite_start]¿Cuál es la probabilidad de que el alumno elegido **no** use anteojos?[cite: 13].

15. **Dígitos del Sistema Decimal:** Si se elige un dígito al azar del 1 al 9:
    * a) Define el espacio muestral y su cardinalidad.
    * b) Calcula la probabilidad de que sea un número mayor que 9.

16. **Lanzamiento de un Dado y una Moneda (Regla Multiplicativa):** Se lanza un dado de 6 caras y una moneda simultáneamente.
    * a) ¿Cuál es la cardinalidad del espacio muestral total?
    * b) ¿Cuál es la probabilidad de obtener un número par en el dado y "Sello" en la moneda?

17. **Suma de Dados (Evento Complementario):** Al lanzar dos dados, se sabe que la probabilidad de que la suma sea 12 es $1/36$. ¿Cuál es la probabilidad de que la suma sea **distinta** de 12?

18. **La Ruleta de Colores:** Una ruleta está dividida en 8 sectores iguales: 4 rojos, 3 verdes y 1 amarillo.
    * a) Calcula la probabilidad de que salga verde.
    * b) Calcula la probabilidad de que **no** salga rojo.

19. **Extracción de Letras:** Se elige al azar una letra de la palabra "MATEMATICA".
    * a) Determina el espacio muestral (letras únicas posibles).
    * b) Calcula la probabilidad de que la letra sea una vocal.

20. **Eventos Independientes en el Taller:** Un técnico tiene una probabilidad de $0.8$ de reparar una falla de software y $0.7$ de reparar una de hardware. Si ambos problemas son independientes, ¿cuál es la probabilidad de que repare ambos?

21. **El Universo de los Primos:** Del 1 al 15, se elige un número al azar.
    * a) Determina $n(\Omega)$.
    * b) Calcula la probabilidad de que el número sea primo o par.
---

## 5. Hacia la Probabilidad Condicional

Considera este escenario: Sabemos que la probabilidad de sacar un "2" en un dado es $1/6$. Pero, si lanzamos el dado y alguien nos informa: **"Salió un número par"**, ¿se mantiene la probabilidad original?

* **Explicación:** Tu universo ya no es $\{1, 2, 3, 4, 5, 6\}$.
* **Nuevo universo reducido:** $\{2, 4, 6\}$.
* **Nueva probabilidad:** $1/3$.

**Conclusión:** La información previa cambia el espacio muestral. Este fenómeno se conoce como **Probabilidad Condicional**.