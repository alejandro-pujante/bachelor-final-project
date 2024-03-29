# Estimación de flujos de emisión atmosférica mediante técnicas de modelado inverso y simulaciones de Montecarlo.

Este es el repositorio de mi Trabajo Final de Grado para optar al Grado en Física por la Universidad de Murcia, tutelado por el profesor Rafael García Molina, profesor de física computacional y Antonio J. Jara Valera, director de I+D en Libelium. 
El documento puede encontrarse pinchando [aquí](https://digitum.um.es/digitum/bitstream/10201/133766/1/TFG%20Alejandro%20Pujante%20P%C3%A9rez.pdf)


## Descripción

El trabajo está marcado dentro del contexto de los modelos de propagación de contaminantes y del uso de dispositivos IoT (Internet of Things) que monitorean concentración de gases en el aire para la estimación de flujos de emisión atmosférica mediante técnicas de modelado inverso y simulaciones de Montecarlo.
En él se propone un algoritmo capaz de estimar la tasa o flujo de emisión de diferentes fuentes de contaminación atmosférica a través de datos de concentración reportados por dispositivos de calidad del aire. Basado en una metodología de ingeniería inversa, se trata de invertir un modelo matemático para dar con la solución
que más se adapta a los datos de campo medidos por los dispositivos mediante un análisis de Montecarlo.

El directorio gaussian_plume hace este análisis utilizando un modelo sencillo de dispersión de contaminantes en forma de distribución normal, mientras que el directorio Montecarlo-analysis lo hace resolviendo la ecuación de difusión-convección. Este modelo es libre de uso y hay un README completo en el directorio.



