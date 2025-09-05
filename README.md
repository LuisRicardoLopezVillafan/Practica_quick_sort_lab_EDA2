# Práctica 3. Algoritmos de Ordenamiento.
## Quick Sort.

La práctica consta de ejercicios, las instrucciones de los cuales se presentan a continuación.

## Ejercicio 1.
Termina de escribir la implementación del algoritmo QuickSort (recuerda que en la última clase, se nos acabó el tiempo antes de terminar la versión final del pseudocódigo).

## Ejercicio 2.
Escribe una implementación diferente para el algoritmo QuickSort en el que el pivote es el promedio de los valores ingresados (incluso si éste no pertenece a la lista).

Restricción: 
En el arreglo de salida solamente pueden aparecer los valores que estaban en el arreglo original de entrada.

## Ejercicio 3. El problema del papá tacaño.
Una familia está de viaje en una ciudad nueva. Cada día del viaje, observan las opciones de lugares que hay por visitar para planear su itinerario. El papá tacaño, en lugar de ver lo atractivo de las opciones, ve el costo que les tomará llegar a cada uno de dichos lugares. No queriendo ser injusto con su familia, les propone el lugar cuyo costo se aproxima a la media de los costos en total. 

Restricciones: 
1. Siempre se consideran al menos tres destinos turísticos.
2. El costo de todo destino turístico es un entero positivo.
3. En cada lista de opciones, se considera, al menos, una opción cuyo costo es desconocido, lo que se representa con una letra mayúscula (por ejemplo, `X`), y al menos una opción cuyo costo es conocido. Un ejemplo de entrada admisible es `Input: [241, 42, 362, X, 79, Y]`.
4. Siempre se supone que los destinos cuyo costo es desconocido tienen un costo mayor que aquellos para los cuales es conocido.
5. Si en una lista de opciones, la mayoría de los destinos tiene costo desconocido, entonces se elige un al azar.

## Ejercicio 4. Problema de las tuercas y los tornillos. 
Se tiene un conjunto de `n` tuercas de diferentes tamaños y `n` tornillos de diferentes tamaños. Existe una correspondencia uno a uno entre las tuercas y los tornillos (cada tornillo corresponde exactamente a una tuerca). El problema consiste en emparejar eficientemente tuercas y tornillos.

Restricción:
No está permitido comparar una tuerca con otra tuerca, ni un tornillo con otro tornillo. Solo se puede comparar una tuerca con un tornillo (o un tornillo con una tuerca) para determinar cuál es más grande o más pequeño.
