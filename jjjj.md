# Reporte de Prueba de Renderizado Matemático

Este documento evalúa la capacidad de **Pandoc** para transformar sintaxis LaTeX compleja a ecuaciones nativas editables en Microsoft Word (OMML).

---

## 1. Ecuaciones en Línea y Álgebra

Sea una función cuadrática general $f(x) = ax^2 + bx + c$, con discriminante $\Delta = b^2 - 4ac$. Sus raíces exactas en el plano complejo se expresan mediante:

$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

La identidad de Euler vincula las constantes fundamentales mediante:

$$e^{i\pi} + 1 = 0 \quad \Longleftrightarrow \quad e^{ix} = \cos(x) + i\sin(x)$$

---

## 2. Cálculo Diferencial e Integral

### Integral Gaussiana y Límites
El valor exacto de la distribución normal integral se define como:

$$\int_{-\infty}^{+\infty} e^{-x^2} \, dx = \sqrt{\pi}$$

Definición formal de derivada por paso al límite:

$$f'(x_0) = \lim_{h \to 0} \frac{f(x_0 + h) - f(x_0)}{h} = \left. \frac{df}{dx} \right|_{x=x_0}$$

### Teorema Fundamental del Cálculo Multivariable (Stokes)
Relación entre la integral de superficie del rotacional de un campo vectorial $\mathbf{F}$ y la integral de línea a lo largo de su frontera $\partial S$:

$$\oint_{\partial S} \mathbf{F} \cdot d\mathbf{r} = \iint_{S} (\nabla \times \mathbf{F}) \cdot d\mathbf{S}$$

Donde el operador nabla en coordenadas cartesianas tridimensionales viene dado por:

$$\nabla = \mathbf{i}\frac{\partial}{\partial x} + \mathbf{j}\frac{\partial}{\partial y} + \mathbf{k}\frac{\partial}{\partial z}$$

---

## 3. Álgebra Lineal y Matrices

Transformación lineal expresada en forma matricial para un sistema de ecuaciones $A\mathbf{x} = \mathbf{b}$:

$$\begin{pmatrix}
a_{11} & a_{12} & \dots & a_{1n} \\
a_{21} & a_{22} & \dots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{m1} & a_{m2} & \dots & a_{mn}
\end{pmatrix}
\begin{pmatrix}
x_1 \\
x_2 \\
\vdots \\
x_n
\end{pmatrix}
=
\begin{pmatrix}
b_1 \\
b_2 \\
\vdots \\
b_m
\end{pmatrix}$$

El determinante de una matriz de $3 \times 3$ evaluado por cofactores:

$$\det(M) = \begin{vmatrix}
\lambda - a & b & c \\
d & \lambda - e & f \\
g & h & \lambda - i
\end{vmatrix} = (\lambda - a)\big((\lambda - e)(\lambda - i) - fh\big) - b\big(d(\lambda - i) - fg\big) + c\big(dh - g(\lambda - e)\big)$$

---

## 4. Sumatorias, Series y Funciones Especiales

### Serie de Taylor
Desarrollo en serie de potencias alrededor del punto $x = a$:

$$f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!} (x - a)^n = f(a) + f'(a)(x-a) + \frac{f''(a)}{2!}(x-a)^2 + \dots$$

### Función por Partes
Definición analítica de una función discontinua:

$$f(x) = \begin{cases} 
0 & \text{si } x < 0 \\
\displaystyle \frac{\sin(x)}{x} & \text{si } x > 0 \\
1 & \text{si } x = 0 
\end{cases}$$

### Ecuación de Schrödinger Independiente del Tiempo
Mecánica cuántica unidimensional para una partícula bajo un potencial $V(x)$:

$$-\frac{\hbar^2}{2m} \frac{d^2\psi(x)}{dx^2} + V(x)\psi(x) = E\psi(x)$$