Método de Runge-Kutta de 4to Orden
Este repositorio contiene una implementación en Python del Método de Runge-Kutta de 4to orden para resolver ecuaciones diferenciales ordinarias (EDOs). Este método es una de las técnicas numéricas más populares debido a su alta precisión y eficiencia.

Descripción
El Método de Runge-Kutta de 4to orden es un método numérico para aproximar soluciones de EDOs de la forma:

𝑑
𝑦
𝑑
𝑥
=
𝑓
(
𝑥
,
𝑦
)
,
𝑦
(
𝑥
0
)
=
𝑦
0
dx
dy
​
 =f(x,y),y(x 
0
​
 )=y 
0
​
 
Este método calcula la solución aproximada de la ecuación diferencial mediante una combinación ponderada de varias evaluaciones de la función derivada en puntos intermedios. A través de este enfoque, se obtiene una precisión elevada sin la necesidad de tomar pasos extremadamente pequeños.

Ejemplo Implementado
En este repositorio se resuelve el siguiente problema:

Ecuación diferencial: 
𝑑
𝑦
𝑑
𝑥
=
𝑥
+
𝑦
dx
dy
​
 =x+y, con la condición inicial 
𝑦
(
0
)
=
1
y(0)=1.
Intervalo de solución: 
𝑥
∈
[
0
,
1
]
x∈[0,1]
Tamaño de paso: 
ℎ
=
0.1
h=0.1
Contenido del Repositorio
runge_kutta_4th_order.py: Código fuente en Python que implementa el Método de Runge-Kutta de 4to orden.
plot_results.py: Script para generar la gráfica de la solución numérica.
README.md: Este archivo, que proporciona una descripción general del proyecto.
Requisitos
Para ejecutar los scripts en este repositorio, necesitas tener instalados:

Python 3.x
Librerías: numpy, matplotlib
