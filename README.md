# Integrales de camino usando Algoritmo de Metrópolis

## Resumen

Este código implementa el algoritmo de Metroplis para calcular la energía promedio de un oscilador armónico cuántico a diferentes temperaturas usando integrlaes de caminos. El código utiliza el algoritmo Metropolis-Hastings para simular trayectorias de la partícula y calcular la energía promedio de estas trayectorias. Se grafican y comparan los resultados del algoritmo con el valor exacto de la energía obtenido para diferente números de pasos máximos de Metroplis.

## Autores

    Lucas Quiceno
    Jhoan Eusse

## Archivos

    main.ipynb: Notebook principal con el código fuente.
    N20.png: Gráfica de la energía promedio y el error en la energía promedio para un máximo de 20 pasos de Metropolis.
    N200.png: Gráfica de la energía promedio y el error en la energía promedio para un máximo de 200 pasos de Metropolis.
    N2000.png: Gráfica de la energía promedio y el error en la energía promedio para un máximo de 2000 pasos de Metropolis.
    N20000.png: Gráfica de la energía promedio y el error en la energía promedio para un máximo de 20000 pasos de Metropolis.
    N200000.png: Gráfica de la energía promedio y el error en la energía promedio para un máximo de 200000 pasos de Metropolis.

## Instalación

Las siguientes librerías son necesarias para ejecutar el código:

    NumPy
    Matplotlib

## Ejecución

Para ejecutar el código, abre el notebook main.ipynb en un entorno Jupyter Notebook o JupyterLab. Luego, ejecuta las celdas en orden.

## Resultados

El código genera varias gráficas que muestran los resultados del PIMC:

    La energía promedio en función de la temperatura inversa (beta).
    El error en la energía promedio en función del número de pasos de Metropolis.

## Conclusiones

El código muestra que el PIMC puede utilizarse para calcular con precisión la energía promedio de un oscilador armónico cuántico. El error en la energía promedio disminuye a medida que se aumenta el número de pasos de Metropolis.
