# Guía N°2 (Matemática): Tabulación y Procesamiento Digital
**Proyecto:** "Bio-Check Escolar"
**Objetivo:** Organizar y tabular datos estadísticos mediante hojas de cálculo para calcular el Índice de Carga Procesada ($ICP$).

---

## 1. Instrucciones de Inicio
En esta sesión, el **Secretario** liderará la digitación de las encuestas en **Google Sheets** o **Excel**.El objetivo es transformar las respuestas cualitativas en una base de datos cuantitativa para el análisis de la Hora 6.

---

## 2. Estructura de la Matriz de Datos (Formato Hoja de Cálculo)
Diseñen su primera pestaña de la siguiente forma, asegurando que cada fila sea un encuestado diferente:

| ID | Edad | Género | Ítem 1 | Ítem 2 | ... | Ítem 18 | **Puntaje Total ICP** |
| :--- | :--- | :--- | :---: | :---: | :---: | :---: | :---: |
| 001 | 17 | M | *f* | *f* | ... | *f* | **(Cálculo)** |
| 002 | 18 | F | *f* | *f* | ... | *f* | **(Cálculo)** |

### Reglas de Llenado:
1. **Frecuencias ($f$):** En las columnas de ítems, ingresen solo números: **0** (Nunca), **1** (A veces) o **2** (Siempre).
2. **Pesos ($w$):** Al calcular el puntaje, recuerden que cada ítem tiene un peso según su categoría:
   * **G1 (No procesados):** Peso 0 (Ítems: 1, 4, 7, 10, 13, 16).
   * **G2 (Procesados):** Peso 1 (Ítems: 3, 6, 9, 12, 15, 18).
   * **G3 (Ultraprocesados):** Peso 2 (Ítems: 2, 5, 8, 11, 14, 17).

---

## 3. Automatización del Índice de Carga Procesada ($ICP$)
Para cada estudiante ($i$), el **Puntaje Total ICP** debe ser la suma de los productos entre frecuencia y peso:

$$ICP_i = \sum_{j=1}^{18} (w_j \cdot f_j)$$

**Fórmula sugerida para Excel/Sheets:**
`=(D2*0) + (E2*2) + (F2*1) + ...` *(Ajusten las celdas y pesos según el orden de su matriz).*

---

## 4. Tabla de Frecuencia por Intervalos
Agrupen los puntajes finales obtenidos para obtener la visión general del curso:

| Rango de ICP (Intervalo) | Clasificación | Frecuencia Absoluta ($f_i$) | Frecuencia Relativa (%) |
| :--- | :--- | :---: | :---: |
| **0 - 9 pts** | Nivel Bajo | | |
| **10 - 18 pts** | Nivel Medio | | |
| **19 - 27 pts** | Nivel Alto | | |
| **28 - 36 pts** | Nivel Crítico | | |
| **Total** | | **N=** | **100%** |

---

## ⚖️ Evaluación de Responsabilidad (25%)
Para validar esta guía, el docente revisará:
* **Registro de Firmas:** Bitácora firmada para la Hora 3.
* **Gestión de Recursos:** Uso de fórmulas para automatizar el $ICP$.
* **Trabajo Colaborativo:** Participación activa según los roles asignados.