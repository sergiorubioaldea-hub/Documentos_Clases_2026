# Base de Datos Técnica: IPC, UF y Educación Financiera (IV Medio)

## 1. Definiciones Fundamentales
* **IPC (Índice de Precios al Consumidor):** Indicador económico elaborado por el INE que mide la variación mensual de los precios de una "Canasta Básica" de bienes y servicios representativa del gasto de los hogares en Chile.
* **Inflación:** Fenómeno económico que consiste en el aumento generalizado y sostenido de los precios. Se mide a través de la variación porcentual del IPC.
* **Canasta Básica:** Selección de más de 300 productos (alimentos, transporte, vivienda, salud, educación) cuyos precios se monitorean mes a mes.

## 2. Formulaciones Matemáticas
Para el análisis de datos financieros, se utilizan las siguientes expresiones:

### A. Variación Porcentual Mensual
$$\text{Inflación del mes} (\%) = \left( \frac{IPC_{mes\_actual} - IPC_{mes\_anterior}}{IPC_{mes\_anterior}} \right) \times 100$$

### B. El Sueldo Real (Poder Adquisitivo)
El sueldo real determina la capacidad de compra efectiva. Si el sueldo nominal aumenta en una tasa $i$ y el IPC en una tasa $\pi$:
$$\text{Variación Real} \approx i - \pi$$
* Si $i > \pi$: Hay ganancia de poder adquisitivo.
* Si $i < \pi$: Hay pérdida de poder adquisitivo (aunque el sueldo en pesos suba).

## 3. La Unidad de Fomento (UF)
La UF es una unidad de cuenta reajustable de acuerdo con la inflación. Su objetivo es asegurar que el valor adquisitivo de los ahorros y contratos se mantenga en el tiempo.
* **Mecanismo:** Si el IPC de marzo es 1%, la UF subirá un 1% de forma prorrateada durante el mes siguiente.
* **Aplicaciones comunes:** Dividendos hipotecarios, planes de Isapre, contratos de arriendo, aranceles universitarios.

## 4. Toma de Decisiones Estratégicas
En contextos de alta inflación (IPC alto), las decisiones financieras cambian:
1. **Ahorro:** Buscar instrumentos que ofrezcan tasas de interés reales positivas (Tasa nominal > IPC).
2. **Deuda:** Preferir créditos con tasa fija en pesos sobre créditos en UF cuando se proyecta inflación alta.
3. **Consumo:** Diferir compras de bienes no esenciales si las tasas de interés (TPM) suben para frenar el IPC.

## 5. El Rol de la Ciencia de Datos en el IPC
El cálculo moderno del IPC integra técnicas de Ingeniería de Datos:
* **Web Scraping:** Recolección automatizada de precios de retail online.
* **Procesamiento de Grandes Volúmenes:** Análisis de tickets de venta reales (Scanner Data) para ajustar las ponderaciones de la canasta.
* **Modelos Predictivos:** Uso de series de tiempo para proyectar la inflación futura.

## 6. Contexto para Estudiantes de IV Medio
El objetivo pedagógico es que el estudiante reconozca que el IPC no es solo un número estadístico, sino un factor determinante en:
* El costo de vida post-secundaria (aranceles y transporte).
* La negociación de sus futuros sueldos.
* La gestión de su primer ahorro previsional o cuenta bancaria.