# Integrales de camino usando Algoritmo de Metrópolis

## Resumen

Este código implementa el algoritmo de Metroplis para calcular la energía promedio de un oscilador armónico cuántico a diferentes temperaturas usando integrales de caminos. El código utiliza el algoritmo Metropolis-Hastings para simular trayectorias de la partícula y calcular la energía promedio de estas trayectorias. Se grafican y comparan los resultados del algoritmo con el valor exacto de la energía obtenido para diferente números de pasos máximos de Metroplis.

## Autores

* Lucas Quiceno
* Jhoan Eusse


## Archivos

* [IntegralCaminos_Metropolis.ipynb: ](https://github.com/EusseJhoan/InegralCaminos_Metropoliss/blob/main/IntegralCaminos_Metropolis.ipynb) Notebook principal con el código fuente.
* [N20.png: ](https://github.com/EusseJhoan/InegralCaminos_Metropoliss/blob/main/N20.png) Gráfica de la energía promedio y el error en la energía promedio para un máximo de 20 pasos de Metropolis.
* [N200.png: ](https://github.com/EusseJhoan/InegralCaminos_Metropoliss/blob/main/N200.png) Gráfica de la energía promedio y el error en la energía promedio para un máximo de 200 pasos de Metropolis.
* [N2000.png: ](https://github.com/EusseJhoan/InegralCaminos_Metropoliss/blob/main/N2000.png) Gráfica de la energía promedio y el error en la energía promedio para un máximo de 2000 pasos de Metropolis.
* [N20000.png: ](https://github.com/EusseJhoan/InegralCaminos_Metropoliss/blob/main/N20000.png) Gráfica de la energía promedio y el error en la energía promedio para un máximo de 20000 pasos de Metropolis.
* [N200000.png: ](https://github.com/EusseJhoan/InegralCaminos_Metropoliss/blob/main/N200000.png) Gráfica de la energía promedio y el error en la energía promedio para un máximo de 200000 pasos de Metropolis.

## Ejecución

Para ejecutar el código, abre el notebook [IntegralCaminos_Metropolis.ipynb ](https://github.com/EusseJhoan/InegralCaminos_Metropoliss/blob/main/IntegralCaminos_Metropolis.ipynb) en un entorno Jupyter Notebook o JupyterLab. Luego, ejecuta las celdas en orden.

## Conclusiones

La implementación del algoritmo de Metropolis-Hasting para calcular numéricamente la integral de caminos para un oscilador armónico. Observamos que, alrededor de 20000 iteraciones, el error en nuestra estimación se vuelve bajo y el método se estabiliza; lo que demuestra que el algoritmo Metropolis-Hastings es efectivo para aproximar la integral de camino en sistemas cuánticos y que a mayor recursos computacionales mejores resultados se obtienen.
