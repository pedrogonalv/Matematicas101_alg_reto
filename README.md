# Matematicas101_alg_reto
Resolución del reto propuesto en el módulo de matemáticas, bootcamp ia

El notebook contiene, a parte de la implementación de las funciones propuestas, la implementación de las siguientes funciones adicionales:

1: Versión para manejar tanto imágenes (numpy.array) en escala de grises como en RGB (image_compresssion_trunc)
  - La detección de formato RGB o escala de grises es automática.
  - Cambian los parámetros suministrados a la función. En vez de seleccionar la cantidad de valores singulares se selecciona un porcentaje (100%-> todos los valores singulares).
  - Se modifica la función de reconstrucción de imagen para considerar sólo valores de byte (truncamiento).
  - Se entrega como resultado un valor de cálculo del error alternativa (sse medio por pixel) dado que permite valorar el error con independencia de la cantidad de píxeles de la imagen de partida.

2: Versión mejorada del algoritmo de compresión (image_compression_round) que realiza la reconstrucción de la imagen aplicando redondeo para evitar los errores generados por el truncamiento de la versión anterior.

3: Comparación del error generado entre ambas versiones.

4: Adicionalmente se generan funciones que facilitan la presentación de resultados para cada uno de los algoritmos, incluyendo tanto la imagen reconstruida como los errores generados.


