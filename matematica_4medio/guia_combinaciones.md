# Guía de Clase: Introducción a las Combinaciones
**Objetivo:** Comprender cómo contar agrupaciones cuando el orden no importa y prepararnos para calcular probabilidades complejas.

---

## 1. El límite humano: ¿Por qué necesitamos contar?

Imagina que lanzamos una moneda al aire 3 veces y queremos saber cuántos caminos posibles nos dan exactamente **2 Caras**. 

Si dibujamos un **Diagrama de Árbol**, es fácil contarlo a mano. Los caminos son 3:
1. (Cara - Cara - Cruz)
2. (Cara - Cruz - Cara)
3. (Cruz - Cara - Cara)

**El problema:** ¿Qué pasa si lanzamos la moneda **10 veces** y queremos **4 Caras**? 
Dibujar ese árbol nos tomaría horas. Necesitamos un "atajo" matemático que cuente las ramas por nosotros.

---

## 2. La Combinación: Cuando el orden da igual

En el ejemplo de la moneda, nos da lo mismo si sale (Cara, Cara, Cruz) o (Cruz, Cara, Cara); lo que nos importa es el grupo final de resultados. 

Cuando queremos elegir elementos de un grupo total y **el orden en que los elegimos NO importa**, usamos una **Combinación**.

### La Fórmula Mágica
Para calcular una combinación, usamos los **factoriales** (ej. $5! = 5 \times 4 \times 3 \times 2 \times 1$).

$$C(n,k) = \binom{n}{k} = \frac{n!}{k!(n-k)!}$$

**Donde:**
*   **$n$**: Es el total de elementos disponibles.
*   **$k$**: Es la cantidad de elementos que queremos elegir.

**Resolviendo el problema de la moneda:**
Queremos 2 caras de un total de 3 lanzamientos.
$$\binom{3}{2} = \frac{3!}{2!(3-2)!} = \frac{3 \times 2 \times 1}{(2 \times 1)(1)} = \frac{6}{2} = 3$$
¡El atajo matemático coincide perfectamente con los 3 caminos de nuestro árbol!

---

## 3. El truco del espejo: Simetría Combinatoria

Imagina que hay 10 estudiantes y el profesor tiene 3 entradas VIP para un concierto. ¿De cuántas formas puede elegir a los 3 afortunados?
$$\binom{10}{3} = \frac{10!}{3! \cdot 7!} = 120 \text{ formas}$$

Pero piénsalo así: **cada vez que eliges a 3 personas para IR, automáticamente estás eligiendo a 7 personas para NO IR.**

Crear un grupo de 3 es exactamente la misma acción que crear un grupo de 7. Por lo tanto:
$$\binom{10}{3} = \binom{10}{7}$$

Esto se llama **Simetría**. En la fórmula de $\binom{10}{7}$, los números de abajo simplemente cambian de posición $(7! \cdot 3!)$, pero el resultado de la multiplicación es el mismo. ¡Esto te ahorrará mucho tiempo de cálculo!

---

## 4. Ejemplos Cotidianos

¿Cómo saber si un problema es de combinación? Haz la "Prueba de la inversión": Si elijo A y luego B, ¿es lo mismo que elegir B y luego A? Si la respuesta es sí, ¡es combinación!

1.  **Armar una Pizza:** Si ofrezco 6 ingredientes y puedes elegir 2. Una pizza de (Pepperoni y Champiñón) es igual a una de (Champiñón y Pepperoni).
    *   **Cálculo:** $\binom{6}{2} = 15$ pizzas distintas.
2.  **Jugos de Fruta:** Tienes 5 frutas y haces un jugo mezclando 3. En la licuadora el orden desaparece.
    *   **Cálculo:** $\binom{5}{3} = 10$ jugos distintos.
3.  **Apretones de Manos:** En una sala hay 6 personas. Todos se saludan una vez. El saludo entre Juan y María es el mismo que entre María y Juan.
    *   **Cálculo:** $\binom{6}{2} = 15$ saludos en total.

---

## 5. Ejercicios Prácticos

**Parte A: Cálculo rápido (Simplificando factoriales)**
Desarrolla los siguientes cálculos simplificando antes de multiplicar (puedes comprobar con la tecla `nCr` de tu calculadora):

1.  $\binom{5}{2} = ?$
2.  $\binom{7}{3} = ?$
3.  Calcula mentalmente, usando la simetría: Si $\binom{100}{98}$ es muy difícil, ¿qué cálculo equivalente es mucho más fácil?

**Parte B: Problemas de aplicación**

4.  Un entrenador tiene 8 jugadores suplentes y necesita hacer 2 cambios al mismo tiempo. ¿Cuántas parejas distintas de jugadores pueden entrar a la cancha?
5.  **El puente hacia la probabilidad:** Volvamos al caso de lanzar 3 monedas y querer 2 Caras. Ya sabemos que hay 3 "caminos" posibles. 
    *   Si asumimos que la moneda es justa (50% o 0.5 para Cara y Cruz).
    *   La probabilidad de un solo camino, por ejemplo (Cara - Cara - Cruz) es: $0.5 \times 0.5 \times 0.5 = 0.125$.
    *   Sabiendo que hay 3 caminos posibles y cada uno tiene una probabilidad de $0.125$, ¿Cuál es la probabilidad total de sacar exactamente 2 caras en 3 lanzamientos?
  
## Guía de Práctica: Combinaciones y Probabilidades Básicas

**Instrucciones:** Lee atentamente cada situación. Identifica si el orden importa o no, plantea la fórmula correspondiente y resuelve. Recuerda que puedes usar el truco de la simetría para facilitar tus cálculos.

---

### Nivel 1: Soltando la mano (Cálculo directo)

1. Calcula el valor de las siguientes combinaciones simplificando los factoriales antes de usar la calculadora:
   * a) $\binom{8}{3}$
   * b) $\binom{12}{2}$

2. **Aplicando simetría:** Tienes que calcular $\binom{15}{13}$. En lugar de hacer ese cálculo tan largo, ¿qué combinación equivalente (y más fácil) puedes usar? Calcula el resultado.

---

### Nivel 2: Problemas de aplicación (¿Importa el orden?)

3. **El Taller de Ajedrez:** El profesor del taller extracurricular de ajedrez tiene a 10 estudiantes destacados. Necesita seleccionar a 4 de ellos para que representen al colegio en un torneo regional por equipos. Como todos jugarán en la misma categoría, no hay capitán ni jerarquías. ¿De cuántas formas distintas puede armar el equipo representante?

4. **El Horno Artesanal:** Una panadería artesanal tiene una oferta especial de fin de semana: "Lleva 3 panes distintos por un precio fijo". Si en la vitrina tienen 7 variedades de pan (integral, centeno, masa madre, ciabatta, etc.), ¿cuántas combinaciones diferentes de panes se puede llevar un cliente?

5. **El Personaje Nivel 70:** En un videojuego de rol, tu personaje llega al nivel máximo y desbloquea 6 habilidades defensivas especiales. Sin embargo, en la barra de acción solo tienes espacio para equipar 3 de esas habilidades al mismo tiempo. ¿Cuántas combinaciones distintas de habilidades defensivas puedes equipar para ir a pelear con el jefe final?

---

### Nivel 3: El puente hacia la probabilidad

6. **Probabilidad en los dados:** Imagina que lanzamos un dado normal (de 6 caras) 3 veces. Nuestro objetivo es obtener exactamente **2 números pares**.
   
   * a) ¿De cuántas formas distintas se pueden ordenar esos 2 éxitos (números pares) y 1 fracaso (número impar) en los 3 lanzamientos? (Pista: Usa combinatoria para elegir los 2 lugares de los éxitos: $\binom{3}{2}$).
   * b) La probabilidad de sacar un número par en un tiro es $0.5$ y de sacar un impar es $0.5$. Calcula la probabilidad de un camino específico (por ejemplo: Par - Par - Impar).
   * c) Multiplica el número de caminos (respuesta a) por la probabilidad de un solo camino (respuesta b) para obtener la probabilidad total.

---

### 🔑 Solucionario para el Profesor

*   **1. a)** $\binom{8}{3} = \frac{8 \times 7 \times 6}{3 \times 2 \times 1} = 56$
*   **1. b)** $\binom{12}{2} = \frac{12 \times 11}{2 \times 1} = 66$
*   **2.** Usando simetría, $\binom{15}{13}$ es lo mismo que $\binom{15}{2}$. $\frac{15 \times 14}{2 \times 1} = 105$.
*   **3. Taller de Ajedrez:** $\binom{10}{4} = \frac{10!}{4! \cdot 6!} = 210$ equipos distintos.
*   **4. Horno Artesanal:** $\binom{7}{3} = \frac{7!}{3! \cdot 4!} = 35$ combinaciones de pan.
*   **5. Videojuego:** $\binom{6}{3} = \frac{6!}{3! \cdot 3!} = 20$ combinaciones de habilidades.
*   **6. a) Caminos posibles:** $\binom{3}{2} = 3$ formas.
*   **6. b) Probabilidad de un camino:** $0.5 \times 0.5 \times 0.5 = 0.125$.
*   **6. c) Probabilidad total:** $3 \times 0.125 = 0.375$ (o $37.5\%$).