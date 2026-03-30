# Guía de Ejercicios: Estadística Descriptiva
**Unidad:** Medidas de Tendencia Central y de Dispersión (Datos No Agrupados)  
**Nivel:** Tercero Medio  

**Objetivo:** Calcular medidas de tendencia central y de dispersión para conjuntos de datos no agrupados, e interpretar sus resultados para la toma de decisiones.

---

## I. Resumen de Fórmulas

Para un conjunto de $n$ datos no agrupados: $x_1, x_2, x_3, \dots, x_n$

### Medidas de Tendencia Central
Buscan resumir en un solo valor el centro de la distribución de los datos.

* **Media Aritmética (Promedio - $\bar{x}$):** Es el centro de gravedad de los datos.
  $$\bar{x} = \frac{\sum_{i=1}^{n} x_i}{n}$$

* **Mediana ($Me$):** Es el valor que ocupa la posición central cuando los datos están ordenados de menor a mayor. Si $n$ es impar, es el dato central. Si $n$ es par, es el promedio de los dos datos centrales.

* **Moda ($Mo$):** Es el valor (o valores) que más se repite en el conjunto de datos.

### Medidas de Dispersión
Indican qué tan alejados están los datos respecto a su centro (generalmente respecto a la media aritmética).

* **Rango ($R$):** Diferencia entre el valor máximo y el mínimo.
  $$R = x_{\max} - x_{\min}$$

* **Desviación Media ($D_{\bar{x}}$):** Promedio de las distancias absolutas de cada dato respecto a la media aritmética.
  $$D_{\bar{x}} = \frac{\sum_{i=1}^{n} |x_i - \bar{x}|}{n}$$

* **Varianza ($\sigma^2$):** Promedio de las desviaciones al cuadrado respecto a la media.
  $$\sigma^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n}$$

* **Desviación Estándar ($\sigma$):** Raíz cuadrada de la varianza. Indica, en promedio, cuánto se alejan los datos de la media aritmética.
  $$\sigma = \sqrt{\sigma^2}$$

---

## II. Ejercicios Prácticos

**Instrucciones:** Para cada una de las siguientes situaciones, realiza los cálculos solicitados dejando registro de tu desarrollo. Luego, responde la pregunta de interpretación.

### Ejercicio 1: El rendimiento académico
Un estudiante ha obtenido las siguientes calificaciones en la asignatura de Matemáticas durante el semestre:  
**4.2 - 5.5 - 6.0 - 5.5 - 4.8 - 6.4**

1. Calcula la Media, Mediana y Moda de las notas.
2. Calcula el Rango, la Desviación Media, la Varianza y la Desviación Estándar.
3. **Interpretación:** Compara el valor de la Desviación Media con el de la Desviación Estándar. ¿Qué nos dice la Desviación Media sobre la "distancia promedio" de las notas del estudiante respecto a su promedio final? Si el profesor jefe te pregunta si las notas son consistentes, ¿qué le responderías?

### Ejercicio 2: Selección para la competencia
El profesor de Educación Física debe elegir a un estudiante para representar al colegio en una competencia de atletismo de 100 metros planos. Ha cronometrado los últimos 5 entrenamientos (en segundos) de sus dos mejores corredores:

* **Corredor A:** 12.1 - 12.5 - 12.3 - 12.2 - 12.4
* **Corredor B:** 11.5 - 13.2 - 11.8 - 13.5 - 11.5

1. Calcula el tiempo promedio ($\bar{x}$) para ambos corredores.
2. Calcula la desviación estándar ($\sigma$) para ambos corredores.
3. **Interpretación:** Analizando los resultados, ambos corredores tienen el mismo tiempo promedio. ¿A cuál corredor debería elegir el profesor si busca al atleta más "confiable" y regular en su rendimiento? Justifica tu respuesta.

### Ejercicio 3: Control de calidad en la industria
Una pequeña fábrica de pan artesanal envasa sus productos en bolsas que deberían pesar idealmente 500 gramos. Se toma una muestra de 8 bolsas al azar de la producción de hoy, registrando los siguientes pesos (en gramos):  
**495 - 505 - 502 - 498 - 500 - 501 - 499 - 500**

1. Calcula las medidas de tendencia central (Media, Mediana, Moda).
2. Calcula las medidas de dispersión (Rango, Desviación Media, Varianza, Desviación Estándar).
3. **Interpretación:** Al día siguiente, una falla en la máquina hace que una de las bolsas pese 410 gramos, mientras que el resto se mantiene similar. Sin hacer cálculos nuevamente, ¿cuál medida de tendencia central se verá más afectada por este valor extremo? ¿Qué pasará con la Desviación Estándar? Explica brevemente.

---

## III. Solucionario (Uso exclusivo del docente)

**Ejercicio 1:**
* $\bar{x} = 5.4$
* $Me = 5.5$ (datos ordenados: 4.2, 4.8, 5.5, 5.5, 6.0, 6.4)
* $Mo = 5.5$
* $R = 2.2$
* $D_{\bar{x}} = 0.6$
* $\sigma^2 \approx 0.54$
* $\sigma \approx 0.73$
* **Interpretación esperada:** En promedio, las notas se alejan 0.6 décimas del promedio general (5.4). Es un rendimiento moderadamente consistente.

**Ejercicio 2:**
* $\bar{x}_A = 12.3$ s | $\bar{x}_B = 12.3$ s
* $\sigma_A \approx 0.14$ s | $\sigma_B \approx 0.88$ s
* **Interpretación esperada:** Se debe elegir al Corredor A. Su baja desviación estándar (0.14 s) indica que es mucho más consistente y predecible que el Corredor B.

**Ejercicio 3:**
* $\bar{x} = 500$ g | $Me = 500$ g | $Mo = 500$ g
* $R = 10$ g
* $D_{\bar{x}} = 2.25$ g
* $\sigma^2 = 8.5$
* $\sigma \approx 2.91$ g
* **Interpretación esperada:** La Media será la más afectada, arrastrada hacia abajo por el valor atípico (410g). La Mediana se mantendrá casi intacta. La Desviación Estándar aumentará drásticamente por el aumento en la dispersión.