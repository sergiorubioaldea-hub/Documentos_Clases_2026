### **Evaluación de Probabilidad: Modelos Bernoulli y Binomial**

**Objetivo de Aprendizaje:** Comprender y aplicar los modelos de probabilidad de Bernoulli y Binomial, construyendo e interpretando árboles de probabilidad para resolver problemas en diversos contextos (cotidianos, lúdicos y algebraicos).

**Instrucciones:** Lee atentamente cada situación y selecciona la alternativa correcta. En todos los problemas se utiliza $P(X=1)$ para denotar la probabilidad de éxito y $P(X=0)$ para denotar la probabilidad de fracaso.

---

#### **I. Conceptos Fundamentales (Preguntas 1 a 5)**

**1. En un experimento modelado mediante una distribución de Bernoulli, ¿qué representan $P(X=1)$ y $P(X=0)$ respectivamente?**

A) $P(X=1)$ es la cantidad de intentos y $P(X=0)$ es la cantidad de fracasos.

B) $P(X=1)$ es la probabilidad del suceso seguro y $P(X=0)$ es la probabilidad del suceso imposible.

C) $P(X=1)$ es la variable aleatoria y $P(X=0)$ es el espacio muestral.

D) $P(X=1)$ es la probabilidad de éxito y $P(X=0)$ es la probabilidad de fracaso.

E) $P(X=1)$ es el número de éxitos deseados y $P(X=0)$ es la probabilidad de obtenerlos.

**2. Al construir un árbol de probabilidades para un experimento que se repite $n$ veces, ¿qué condición se debe cumplir respecto a las ramas finales?**
A) La suma de las probabilidades de todas las ramas finales debe ser igual a 1.

B) La suma de las probabilidades de todas las ramas finales debe ser igual a $n$.

C) Todas las ramas finales deben tener exactamente la misma probabilidad.

D) La probabilidad de cada rama debe ser mayor que 1.

E) La suma de las probabilidades de las ramas finales depende de si el experimento es dependiente o independiente.

**3. En la fórmula de probabilidad Binomial, se utiliza el coeficiente binomial $\binom{n}{k}$. En el contexto de un árbol de probabilidades, ¿qué representa este coeficiente?**

A) La probabilidad total de obtener $k$ éxitos.

B) La cantidad de ramas en el árbol que contienen exactamente $k$ éxitos.

C) La probabilidad de una única rama que contiene $k$ éxitos y $n-k$ fracasos.

D) El número total de ramas que tiene el árbol completo.

E) El producto entre la probabilidad de éxito y la probabilidad de fracaso.

**4. Para que un experimento repetido varias veces pueda ser modelado correctamente mediante una distribución Binomial, los eventos deben ser:**

A) Mutuamente excluyentes y dependientes.

B) Simultáneos y con probabilidad variable.

C) Dicotómicos e independientes entre sí.

D) Dicotómicos, donde la probabilidad de éxito cambia en cada intento.

E) Excluyentes, sin importar si tienen dos o más resultados posibles.

**5. Si $p$ es la probabilidad de éxito, ¿cuál es la expresión matemática correcta para $P(X=0)$ en un solo ensayo de Bernoulli?**

A) $P(X=0) = p - 1$

B) $P(X=0) = \frac{1}{p}$

C) $P(X=0) = p^0$

D) $P(X=0) = 1 + p$

E) $P(X=0) = 1 - p$

---

#### **II. Construcción y Análisis de Árbol de Probabilidades (Preguntas 6 a 10)**

*Para esta sección, construye un árbol de probabilidades para el siguiente experimento: "Se lanza una moneda trucada 3 veces. La probabilidad de obtener cara (Éxito, $X=1$) es de $0{,}6$ y la probabilidad de obtener sello (Fracaso, $X=0$) es de $0{,}4$".*

**6. ¿Cuántas ramas finales (resultados posibles) tiene en total tu árbol de probabilidades?**

A) 3

B) 6

C) 9

D) 8

E) 12

**7. Si sigues una única rama que represente la secuencia exacta de resultados (Éxito, Fracaso, Éxito) en ese orden específico, ¿cuál es la probabilidad de esa única rama?**

A) $0{,}6 + 0{,}4 + 0{,}6$

B) $0{,}6 \cdot 0{,}4 \cdot 0{,}6$

C) $3 \cdot (0{,}6 \cdot 0{,}4)$

D) $0{,}6 \cdot 0{,}6 \cdot 0{,}6$

E) $\binom{3}{2} \cdot 0{,}6^2 \cdot 0{,}4^1$

**8. Observa tu árbol. ¿Cuántas ramas distintas contienen exactamente 2 éxitos y 1 fracaso, sin importar el orden?**

A) 3

B) 1

C) 2

D) 4

E) 6

**9. Utilizando la información de las preguntas anteriores, ¿cuál es la probabilidad total de obtener exactamente 2 éxitos en los 3 lanzamientos?**

A) $0{,}6 \cdot 0{,}4 \cdot 0{,}6$

B) $0{,}6^2 \cdot 0{,}4^1$

C) $0{,}6^3$

D) $3 \cdot (0{,}6 + 0{,}4)$

E) $3 \cdot (0{,}6^2 \cdot 0{,}4^1)$

**10. ¿Cuál es la probabilidad de que en los 3 lanzamientos se obtengan 0 éxitos (es decir, puro fracaso)?**
A) $0{,}4 \cdot 3$

B) $1 - (0{,}6)^3$

C) $0{,}4^3$

D) $3 \cdot 0{,}4^3$

E) $0{,}4 + 0{,}4 + 0{,}4$

---

#### **III. Aplicación en Contexto (Preguntas 11 a 15)**

*En Minecraft, al talar un árbol de roble existe un 15% de probabilidad de que caiga una manzana. Utilizaremos el modelo donde $X=1$ representa que cae una manzana (éxito) y $X=0$ representa que no cae (fracaso).*

**11. ¿Cómo se expresa esta situación para la tala de un solo árbol utilizando el modelo de Bernoulli?**

A) $P(X=1) = 0{,}15$ ; $P(X=0) = 0{,}15$

B) $P(X=1) = 15$ ; $P(X=0) = 85$

C) $P(X=1) = 0{,}85$ ; $P(X=0) = 0{,}15$

D) $P(X=1) = 0{,}15$ ; $P(X=0) = 0{,}85$

E) $P(X=1) = 0{,}15$ ; $P(X=0) = -0{,}15$

**12. Si se talan 3 árboles de roble, ¿cuál es la expresión correcta para calcular la probabilidad de obtener exactamente 2 manzanas?**

A) $(0{,}15)^2 \cdot (0{,}85)^1$

B) $3 \cdot (0{,}15)^2 \cdot (0{,}85)^1$

C) $2 \cdot (0{,}15)^3 \cdot (0{,}85)^0$

D) $3 \cdot (0{,}15)^1 \cdot (0{,}85)^2$

E) $\binom{3}{2} + 0{,}15^2 + 0{,}85^1$

**13. Si ahora el jugador tala 10 árboles de roble, ¿cuál es la probabilidad de obtener exactamente 4 manzanas?**

A) $\binom{10}{4} \cdot (0{,}15)^6 \cdot (0{,}85)^4$

B) $4 \cdot (0{,}15)^4 \cdot (0{,}85)^6$

C) $\binom{10}{4} \cdot (0{,}15)^4$

D) $(0{,}15)^4 \cdot (0{,}85)^6$

E) $\binom{10}{4} \cdot (0{,}15)^4 \cdot (0{,}85)^6$

**14. Si se talan 5 árboles, ¿cuál de las siguientes opciones permite calcular la probabilidad de obtener exactamente 1 manzana?**

A) $5 \cdot (0{,}15)^1 \cdot (0{,}85)^4$

B) $1 \cdot (0{,}15)^1 \cdot (0{,}85)^4$

C) $\binom{5}{1} \cdot (0{,}15)^1 \cdot (0{,}85)^5$

D) $(0{,}15)^1 \cdot (0{,}85)^4$

E) $5 \cdot (0{,}15)^4 \cdot (0{,}85)^1$

**15. Si quisieras calcular la probabilidad de obtener 3 manzanas al talar 6 arboles usando un árbol de probabilidad, ¿cuántas ramas tendrías que sumar (es decir, cuántas ramas tienen exactamente 3 éxitos en 6 intentos)?**

A) 6 ramas

B) 10 ramas

C) 20 ramas

D) 15 ramas

E) 64 ramas

---

#### **IV. Análisis de Modelo Algebraico (Preguntas 16 a 20)**

*El modelo de probabilidad de un experimento dicotómico está dado por la siguiente expresión, donde $X \in \{0, 1\}$:*
$$P(X=x) = 0{,}34^x \cdot 0{,}66^{1-x}$$

**16. A partir de la expresión, ¿cuál es el valor de $P(X=1)$ (probabilidad de éxito)?**

A) $0{,}66$

B) $1$

C) $0{,}50$

D) $0$

E) $0{,}34$

**17. Si repites este experimento 3 veces, ¿cuál es la probabilidad de una **única rama** específica del árbol que tenga 2 éxitos y 1 fracaso?**

A) $0{,}34 \cdot 0{,}66$

B) $3 \cdot (0{,}34^2 \cdot 0{,}66^1)$

C) $0{,}34^2 \cdot 0{,}66^1$

D) $0{,}34^1 \cdot 0{,}66^2$

E) $\binom{3}{2} \cdot 0{,}34$

**18. Si se realiza el experimento 12 veces, ¿qué expresión permite calcular cuántas ramas del árbol tendrán exactamente 8 éxitos?**

A) $12 \cdot 8$

B) $8^{12}$

C) $12^8$

D) $\binom{12}{8}$

E) $\binom{12}{4} \cdot 8$

**19. Calcula la probabilidad (dejando la expresión planteada) de obtener exactamente 3 éxitos en 10 repeticiones del experimento.**

A) $\binom{10}{3} \cdot 0{,}34^3 \cdot 0{,}66^7$

B) $3 \cdot 0{,}34^3 \cdot 0{,}66^7$

C) $\binom{10}{3} \cdot 0{,}34^7 \cdot 0{,}66^3$

D) $0{,}34^3 \cdot 0{,}66^7$

E) $\binom{10}{3} \cdot (0{,}34 \cdot 0{,}66)^{10}$

**20. Si se evalúa la función del modelo para $X=0$, ¿cuál es el resultado de $0{,}34^0 \cdot 0{,}66^{1-0}$ y qué significa en el contexto del problema?**

A) Da como resultado $0{,}34$, y representa la probabilidad de éxito.

B) Da como resultado $0{,}66$, y representa la probabilidad de fracaso $P(X=0)$.

C) Da como resultado $0{,}66$, y representa la probabilidad de éxito.

D) Da como resultado $1$, porque la suma de probabilidades es $1$.

E) Da como resultado $0$, porque $X=0$ anula la multiplicación.

---

### **Pauta de Corrección**

| Pregunta | Respuesta | Pregunta | Respuesta | Pregunta | Respuesta | Pregunta | Respuesta |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **1** | D | **6** | D | **11** | D | **16** | E |
| **2** | A | **7** | B | **12** | B | **17** | C |
| **3** | B | **8** | A | **13** | E | **18** | D |
| **4** | C | **9** | E | **14** | A | **19** | A |
| **5** | E | **10** | C | **15** | C | **20** | B |