# 📊 Guía Técnica para Tabulación de Datos: "Bio-Check Escolar"

Esta guía permite clasificar las respuestas de la encuesta de hábitos alimenticios en tres categorías principales según el grado de procesamiento industrial, facilitando el análisis estadístico posterior.

---

## 1. Definiciones de Categorías para el Análisis

| Categoría | Definición Técnica | Criterio de Identificación |
| :--- | :--- | :--- |
| **G1: No Procesados** | Alimentos naturales obtenidos directamente de plantas o animales sin alteración química. | No contienen sal, azúcar, aceites ni aditivos añadidos. |
| **G2: Procesados** | Alimentos naturales modificados industrialmente para aumentar su durabilidad o mejorar sabor. | Conservan la identidad del alimento original, pero tienen sal, azúcar o aceite añadido. |
| **G3: Ultraprocesados** | Formulaciones industriales elaboradas mayoritariamente con sustancias extraídas de alimentos y aditivos. | No se reconoce el alimento original; suelen tener más de 5 ingredientes y muchos aditivos. |

---

## 2. Matriz de Clasificación de Alimentos (Para Tabuladores)

Utilicen esta tabla para asignar el **Peso Numérico ($w$)** a cada respuesta.Este peso es fundamental para el cálculo del **Puntaje de Carga Procesada**.

| Alimento de la Encuesta | Categoría | Peso Sugerido ($w$) |
| :--- | :---: | :---: |
| Fruta entera (manzana, plátano, etc.) | **G1** | 0 |
| Huevo duro | **G1** | 0 |
| Frutos secos naturales (sin sal) | **G1** | 0 |
| Bastoncitos de verdura (zanahoria, apio) | **G1** | 0 |
| Leche blanca natural | **G1** | 0 |
| Agua mineral o purificada | **G1** | 0 |
| Pan de panadería (marraqueta, hallulla) | **G2** | 1 |
| Queso lámina o fresco | **G2** | 1 |
| **Sándwich de queso** (pan + queso) | **G2** | 1 |
| Atún en conserva | **G2** | 1 |
| Fruta en conserva (en almíbar) | **G2** | 1 |
| Jamón de pavo cocido | **G2** | 1 |
| Yoghurt con sabor | **G3** | 2 |
| Leche saborizada (chocolate, frutilla) | **G3** | 2 |
| Barra de cereal | **G3** | 2 |
| Galletas rellenas o con cobertura | **G3** | 2 |
| Papas fritas o snacks en bolsa | **G3** | 2 |
| Bebida gaseosa o jugo en caja | **G3** | 2 |

---

## 3. Procedimiento de Cálculo (Matemática - Hora 6)

Para cada estudiante encuestado ($i$), el equipo de análisis debe calcular su **Puntaje de Procesamiento Individual ($P_i$)** sumando los pesos correspondientes a los alimentos que consume habitualmente en el liceo:

$$P_i = \sum w$$

  **Resultados esperados:** Un puntaje cercano a **0** representa un perfil alimenticio saludable, mientras que puntajes altos indican una dieta con predominio de ultraprocesados, lo cual debe ser graficado mediante **Diagramas de Caja ($box-plots$)** para identificar la dispersión del curso.