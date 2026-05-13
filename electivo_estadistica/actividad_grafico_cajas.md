# Guía de Actividades: Análisis de Datos con Box Plot
**Asignatura:** Probabilidades y Estadística Descriptiva e Inferencial  
**Nivel:** Tercero Medio  

---

## Actividad 1: Construcción y Detección de Valores Atípicos

### Contexto
Una panadería artesanal de la zona poniente, conocida por su trabajo con masa madre de larga fermentación, ha registrado la cantidad de hogazas de pan de campo vendidas diariamente durante un periodo de dos semanas (14 días). Los datos recolectados son los siguientes:

**15, 18, 12, 20, 22, 14, 18, 25, 21, 19, 28, 30, 45, 16**

### Instrucciones
1.  **Ordenamiento:** Organiza el conjunto de datos de menor a mayor.
2.  **Resumen de los 5 números:** Calcula los valores necesarios para el gráfico:
    * Mínimo:
    * Primer Cuartil ($Q_1$):
    * Mediana ($Q_2$):
    * Tercer Cuartil ($Q_3$):
    * Máximo:
3.  **Dispersión:** Calcula el Rango Intercuartil ($RIC = Q_3 - Q_1$).
4.  **Identificación de Outliers:** Utiliza la regla de los valores atípicos:
    * Límite Inferior: $Q_1 - 1,5 \cdot RIC$
    * Límite Superior: $Q_3 + 1,5 \cdot RIC$
    * ¿Existe algún valor atípico? En caso de ser así, ¿qué explicación podrías dar para ese dato en el contexto de la panadería?
5.  **Representación Gráfica:** Construye el diagrama de caja y bigotes utilizando una escala graduada adecuada.

---

## Actividad 2: Interpretación y Comparación de Distribuciones

### Contexto
Un grupo de estudiantes interesados en la astronomía realizó un registro del número de estrellas fugaces observadas por hora durante una lluvia de meteoros. Para comparar el efecto de la contaminación lumínica, se instalaron en dos puntos distintos: **Lampa** (zona periférica) y el **Centro de Santiago**.

A continuación, se presentan los datos resumidos de las observaciones:

| Medida Estadística | Lampa | Santiago Centro |
| :--- | :---: | :---: |
| Mínimo | 15 | 2 |
| Cuartil 1 ($Q_1$) | 25 | 5 |
| Mediana ($Q_2$) | 35 | 8 |
| Cuartil 3 ($Q_3$) | 45 | 12 |
| Máximo | 55 | 18 |
| *Valores Atípicos* | *No hay* | **30** |

### Preguntas de Análisis
1.  **Tendencia Central:** Compara las medianas de ambos lugares. ¿Cuál es la diferencia absoluta entre ellas y qué conclusión puedes sacar respecto a la visibilidad del cielo en ambas zonas?
2.  **Variabilidad:** Observando el Rango Intercuartil ($RIC$), ¿en qué ubicación los datos son más dispersos? Justifica tu respuesta mencionando el tamaño de la "caja".
3.  **El Caso Atípico:** En el gráfico de Santiago Centro aparece un valor atípico de 30 estrellas fugaces en una hora. Propón una hipótesis (climatológica, técnica o de otro tipo) que podría explicar este suceso inusual en plena ciudad.
4.  **Toma de Decisiones:** Un turista desea observar al menos 25 estrellas fugaces por hora para que su viaje valga la pena. Basándote **únicamente** en los gráficos de caja, ¿a qué lugar le asegurarías que cumplirá su objetivo y por qué?

---

## Pauta de Corrección (Exclusivo Docente)

### Solución Actividad 1
* **Datos ordenados:** 12, 14, 15, 16, 18, 18, 19, 20, 21, 22, 25, 28, 30, 45.
* **5 Números:** Mín=12, $Q_1$=16, Mediana=19.5, $Q_3$=25, Máx=45.
* **RIC:** $25 - 16 = 9$.
* **Límites:** Sup = $25 + (1.5 \cdot 9) = 38.5$. 
* **Atípico:** El valor **45** es un outlier superior.
* **Gráfico:** Los bigotes deben llegar hasta el 12 (mínimo) y el 30 (valor más alto no atípico). El 45 se marca con un asterisco.

### Solución Actividad 2
1.  **Mediana:** Lampa (35) vs Santiago (8). La visibilidad es significativamente mayor en la periferia.
2.  **Dispersión:** Lampa tiene un $RIC$ de 20, mientras que Santiago tiene un $RIC$ de 7. Lampa presenta mayor variabilidad en los avistamientos.
3.  **Atípico:** Posible corte de luz masivo en el sector, uso de equipos especializados (telescopios) por un momento o un pico real de la lluvia de meteoros.
4.  **Decisión:** Lampa. El 75% de los datos de Lampa están por sobre las 25 estrellas (desde $Q_1$ hacia arriba), lo que ofrece una garantía estadística mucho mayor.