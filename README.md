Método de Elementos Finitos (FEM) 1D y 2D

Implementación del Método de Elementos Finitos (FEM) para resolver ecuaciones diferenciales parciales, comenzando con el caso unidimensional (1D) y extendiéndose a 2D.

En este proyecto se resuelve la ecuación de Poisson en el intervalo ( (0,1) ) utilizando el método de Galerkin, pasando de su forma fuerte a la formulación variacional, y posteriormente a un sistema de ecuaciones lineales:

[
A \alpha = b
]

donde:

( A ) es la matriz de rigidez
( b ) es el vector de cargas
🔍 Contenido
Implementación de funciones base (tipo "sombrero")
Construcción de la matriz de rigidez y vector de carga
Resolución del sistema lineal
Comparación con solución analítica
Extensión a FEM 2D
