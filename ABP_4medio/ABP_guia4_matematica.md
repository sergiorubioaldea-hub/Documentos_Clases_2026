# Guía N°4 (Matemática hora 6 y 7): Análisis Estadístico y Visualización
**Proyecto:** "Bio-Check Escolar"
**Objetivo:** Calcular medidas de tendencia central y dispersión para construir gráficos de alta complejidad ($box-plots$ e histogramas) que evidencien la realidad de salud del curso.

---

## 1. Hora 6: Estadística Descriptiva (El "ADN" de los datos)
Utilizando la matriz de datos y los puntajes de **Índice de Carga Procesada ($ICP$)** calculados en la Hora 3, deben obtener los siguientes estadígrafos en su hoja de cálculo:

### A. Medidas de Tendencia Central
* **Media ($\bar{x}$):** El promedio de nivel de procesamiento del curso.
* **Mediana ($\tilde{x}$):** El valor central que divide la muestra en dos grupos del 50%.
* **Moda ($Mo$):** El puntaje de riesgo que más se repite en la muestra.

### B. Medidas de Dispersión e Incerteza (OA 2) 
Para entender qué tan variados son los hábitos del curso, calculen:
* **Rango:** Diferencia entre el puntaje máximo y mínimo de $ICP$.
* **Desviación Estándar ($\sigma$):** Indica cuánto se alejan, en promedio, los datos de la media aritmética.
* **Cuartiles ($Q_1, Q_2, Q_3$):** Valores que dividen los datos en cuatro partes iguales, necesarios para el Diagrama de Caja.

---

## 2. Hora 7: Visualización de Datos (Comunicando la brecha)
El producto de esta hora son los gráficos que se integrarán en el **Tablero de Bienestar Escolar**.

### A. Histograma de Frecuencias 
* **Eje X:** Intervalos de puntaje $ICP$ (0-9, 10-18, 19-27, 28-36).
* **Eje Y:** Cantidad de estudiantes (Frecuencia absoluta).
* **Propósito:** Visualizar la distribución del curso según niveles de riesgo (Bajo a Crítico)[cite: 33, 49].

### B. Diagrama de Caja (Box-plot) [cite: 33, 49, 64]
Este gráfico es vital para identificar la **incerteza** y los **valores atípicos ($outliers$)**[cite: 10, 33]. Debe mostrar claramente:
1.  El valor mínimo y máximo (Bigotes).
2.  La "caja" que contiene el 50% central de los datos ($Q_1$ a $Q_3$).
3.  La línea de la mediana ($Q_2$).
4.  Puntos aislados que representen casos extremos de riesgo o salud ($outliers$).



[Image of a box-plot with quartiles and outliers labeled]


---

## 📝 Rúbrica Técnica: Reporte Estadístico (75% Nota de Matemática)
*Esta rúbrica evalúa exclusivamente el componente técnico disciplinar del producto final en la asignatura de Matemática[cite: 56, 61, 63, 65].*

| Criterio | Destacado (4 pts) | Habilitado (3 pts) | Inicial (1 pt) |
| :--- | :--- | :--- | :--- |
| **Precisión del Cálculo** | Todos los estadígrafos ($\bar{x}, \sigma, Q_n$) son exactos y calculados mediante fórmulas correctas en la planilla[cite: 32, 64]. | Existen errores menores en el cálculo de medidas de dispersión o cuartiles. | Los cálculos son erróneos o no se presentan medidas de dispersión[cite: 32]. |
| **Calidad Gráfica** | El Histograma y el Box-plot tienen escalas precisas, títulos claros y leyendas legibles[cite: 33, 49, 64]. | Los gráficos son correctos pero carecen de títulos, etiquetas de ejes o limpieza visual. | Los gráficos son confusos, desproporcionados o no corresponden a los datos[cite: 33]. |
| **Análisis de Outliers** | Identifica y explica técnicamente la existencia de valores atípicos ($outliers$) en el consumo del curso[cite: 33]. | Menciona los valores extremos pero no los identifica correctamente como $outliers$. | No realiza análisis de dispersión ni identifica casos de salud/riesgo extremos. |
| **Interpretación de Datos** | Explica claramente el significado de la mediana y la desviación estándar en el contexto de hábitos de salud[cite: 64]. | Describe los resultados numéricos pero no logra conectarlos con el concepto de bienestar. | Solo presenta los gráficos sin ningún tipo de conclusión o análisis descriptivo. |


# 📊 Reporte de Ejemplo: Análisis de Carga Procesada (Grupo 1)
**Proyecto:** "Bio-Check Escolar"  
**Integrantes:** [Nombres de los alumnos]  
**Fecha:** 05 de abril, 2026

---

## 1. Matriz de Datos del Grupo (Muestra $n=5$)
Este reporte se basa en una muestra inicial de 5 estudiantes. Los puntajes de frecuencia ($f$) y peso ($w$) han sido tabulados para obtener el **Índice de Carga Procesada ($ICP$)**.

| Estudiante (ID) | Puntaje ICP ($P_i$) | Clasificación de Riesgo |
| :--- | :---: | :--- |
| 001 | 1 | Riesgo Bajo |
| 002 | 9 | Riesgo Bajo / Medio |
| 003 | 10 | Riesgo Medio |
| 004 | 3 | Riesgo Bajo |
| 005 | 12 | Riesgo Medio |

---

## 2. Análisis Estadístico (Matemática - OA 2)
A partir de los puntajes obtenidos, se calculan los estadígrafos que describen el comportamiento del grupo respecto al consumo de alimentos ultraprocesados.

### A. Medidas de Tendencia Central
* **Promedio ($\bar{x}$):** $7,0$ puntos.
* **Mediana ($\tilde{x}$):** $9,0$ puntos.
* **Interpretación:** El 50% de los estudiantes analizados presenta un nivel de procesamiento igual o superior a 9 puntos.

### B. Medidas de Dispersión (Incerteza)
* **Rango:** $11$ puntos. Indica una variabilidad considerable entre los hábitos más saludables y los de mayor riesgo.
* **Cuartiles para el Box-plot:**
  * **Valor Mínimo:** 1
  * **$Q_1$ (25%):** 2,0
  * **$Q_2$ (Mediana):** 9,0
  * **$Q_3$ (75%):** 11,0
  * **Valor Máximo:** 12

> **Nota para el Panel:** El gráfico de **Diagrama de Caja (Box-plot)** debe construirse utilizando estos 5 valores para mostrar visualmente dónde se concentra la mayor cantidad de estudiantes.

---

## 3. Interpretación Biológica (Ciencias - OA 1)
Basándonos en la evidencia cuantitativa, el equipo de investigación concluye:

1. **Vulnerabilidad Detectada:** Aunque el promedio es de 7 puntos, el **25% superior de la muestra ($Q_3$)** ya alcanza puntajes de 11 o más. Esto refleja una dependencia incipiente a alimentos de la categoría G3 (Ultraprocesados).
2. **Impacto Sistémico:** Un $ICP$ elevado de forma sostenida se asocia con un aumento en la carga glucémica y la presencia de aditivos pro-inflamatorios, afectando el rendimiento académico y la salud metabólica a largo plazo.
3. **Acción Sugerida:** Se propone una campaña de "Intercambio Saludable" para sustituir el ítem 2 (Yoghurt industrial) por el ítem 16 (Leche blanca o kéfir natural).

---

## 📝 Check-list: Elementos del Producto Final
Para que el **Tablero de Bienestar Escolar** esté completo, asegúrense de incluir:

- [ ] **Título Impactante:** Relacionado con el eslogan del grupo.
- [ ] **Gráfico 1:** Histograma de frecuencias por niveles de riesgo.
- [ ] **Gráfico 2:** Diagrama de Caja ($box-plot$) con los cuartiles rotulados.
- [ ] **Análisis de Incerteza:** Breve texto explicando qué tan dispersos están los datos del curso.
- [ ] **Infografía de Salud:** Riesgos biológicos de los ultraprocesados detectados.
- [ ] **Propuesta de Mejora:** Una acción concreta basada en los datos.

---

## ⚖️ Validación de Responsabilidad (25%)
Este reporte debe estar archivado en la carpeta de proyecto. Recuerden que la **calificación de responsabilidad** depende de:
1. El orden y limpieza de este documento.
2. La presencia de las **11 firmas docentes** en la bitácora de trabajo.
3. La entrega puntual en la Hora 11 del proyecto.

# 📉 Tutorial: Cómo Crear un Diagrama de Caja (Box-plot) en Excel
**Proyecto:** "Bio-Check Escolar"  
**Objetivo:** Visualizar la dispersión y los valores atípicos del Índice de Carga Procesada ($ICP$).

---

## Paso 1: Preparación de los Datos
Para que Excel reconozca el gráfico, los datos deben estar organizados en una sola columna.

1. Selecciona la columna donde calculaste el **Puntaje Total ICP** de todos los encuestados.
2. Asegúrate de incluir solo los números (no incluyas el promedio o la suma al final de la columna).

---

## Paso 2: Insertar el Gráfico
Excel tiene una función nativa para este tipo de análisis estadístico avanzado:

1. Ve a la pestaña **Insertar** en la barra de herramientas superior.
2. Busca el grupo de **Gráficos** y haz clic en el ícono de **Gráficos de Estadística** (suele verse como un histograma azul).
3. Selecciona la opción **Cajas y Bigotes**.



---

## Paso 3: Personalización Profesional
Un gráfico de "Ciencia de Datos" debe ser fácil de leer. Realiza los siguientes ajustes:

1. **Título del Gráfico:** Haz doble clic y cámbialo por algo descriptivo, ej: *"Distribución de Carga Procesada - 4° Medio B"*.
2. **Etiquetas de Datos:** Haz clic derecho sobre una de las cajas y selecciona **Agregar etiquetas de datos**. Esto mostrará los valores exactos de los Cuartiles ($Q_1, Q_2, Q_3$) y los Valores Atípicos.
3. **Eje Vertical:** Asegúrate de que el eje Y comience en 0 y termine en 36 (el puntaje máximo posible de nuestra encuesta).

---

## Paso 4: ¿Qué estamos viendo? (Interpretación)
Una vez creado el gráfico, enséñale a tu equipo a identificar estos 4 puntos clave:

* **La "X" central:** Es el **Promedio ($\bar{x}$)** de consumo del curso.
* **La línea horizontal interna:** Es la **Mediana ($\tilde{x}$)**. Si está muy arriba, el curso tiene un problema serio de ultraprocesados.
* **Los puntos aislados (puntos sobre o bajo los bigotes):** Son los **Outliers**. Representan a estudiantes con hábitos extremadamente diferentes al resto del grupo.
* **El tamaño de la caja:** Mientras más larga sea la caja, mayor es la **incerteza** o variabilidad de los hábitos en el curso.

---

## 💡 Tip Pro para el Secretario (Excel Avanzado)
Si quieren comparar géneros (Masculino vs. Femenino), seleccionen **dos columnas**: una con el "Género" y otra con el "Puntaje ICP". Excel creará automáticamente dos cajas una al lado de la otra, permitiéndoles analizar si hay diferencias biológicas o sociales en el consumo según el género.

---
**Recuerden:** Una vez listo el gráfico, cópienlo y péguenlo en su reporte final para el **Tablero de Bienestar Escolar**. ¡La claridad visual suma puntos en su nota técnica!