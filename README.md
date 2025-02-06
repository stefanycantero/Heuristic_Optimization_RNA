# Trabajo 01: Optimización heurística
Este repositorio contiene los archivos relacionados con el código fuente para la elaboración del Trabajo 01 de la asignatura Redes Neuronales Aritificiales y Algoritmos Bioinspirados para el semestre 2024-02. Se aplican técnicas de optimización heurística con el objetivo de resolver problemas de alta complejidad como optimizar funciones en espacios de dos y tres dimensiones, y el problema del vendedor viajero. Se divide en dos partes: optimización numérica y optimización combinatoria. 

Equipo 01 conformado por: 
* Verónica Pérez Zea
* Sebastian Aguinaga Velasquez
* Stefany Cantero Cárdenas
* María Del Pilar Mira Londoño

## Parte 1: Optimización numérica

### Técnicas utilizadas
* Para optimizar las funciones con descenso del gradiente se crearon las funciones para hacerlo.
* Para optimizar con algoritmos evolutivos se uso la librería PyGAD.
* Para realizar Optmización de partículas se utilizo la librería PySwarms.
* Para optimizar con evolución diferencial se utilizó SciPy.

#### Librerías 
* Numpy
* PyGAD
* PySwamrs
* Scipy

### Resultados esperados

Mejor solución encontrada con cada implementación, ya sea costo o posición, y su respectiva evaluación en cada una de las funciones elegidas.
## Parte 2: Optimización combinatoria

### Técnicas utilizadas

* Para obtener la matriz de costos necesaria para resolver el TSP se hizo uso de web scrapping con la librería Selenium.
* Para el Algoritmo de Colonia de Hormingas se realizó la construcción del algoritmo por medio de programación sin librerías adicionales a las relacionadas con cálculos numéricos y manejo de datos.
* Para el Algoritmo Genético se hizo uso de la librería PyGAD y de funciones personalizadas para el cálculo de la mejor aptitud (fitness), mecanismo de mutación, la creación de la población y el tipo de cruzamiento.  

#### Librerías

* Selenium
* Numpy
* Cartopy
* PyGAD
* Pandas
* Geopandas
* Matplotlib
* Imageio
  
### Resultados esperados

En ambos algoritmos se espera como salida el costo mínimo en pesos mexicanos junto con la ruta óptima de las ciudades visitadas por el vendedor. 
