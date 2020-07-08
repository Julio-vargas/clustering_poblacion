# clustering_poblacion
Estudio de algoritmos de clasificación no supervisada y optimización de hiperparametros para la creación de grupos poblacionales

Es un proyecto en Python que contiene el código fuente para la preparación de los datos y entrenamiento de modelos de clustering para la creación de grupos poblacionales.

**Trabajo**: Estudio de algoritmos de clasificación no supervisada y optimización de hiperparametros para la creación de grupos poblacionales

**Autor**: Julio Enrique Vargas Monzón

**E-Mail**: julio.v.monzon@gmai.com


Dependencias:
============
**Paquetes utilizados**: sklearn, PyClustering, pandas, numpy

**Versión de Python**: >=3.5

Archivos:
============

1. **Analisis_y_preparacion_datos.ipynb**: script en el que se describen los datos, así mismo realiza las transformaciones para prepararlos para el entrenamiento de modelos de clustering.

-- Entrada: datos de censo poblacional 2018 de Guatemala, disponibles en https://www.censopoblacion.gt/descarga

-- Salida: datos procesados
2. **Entrenamiento_DBSCAN-v2.ipynb**: script que realiza el entrenamiento de modelos de clustering utilizando el algoritmo DBSCAN.

-- Entrada: datos procesados

-- Salida: datos agrupados en clusters y métricas de ejecución
3. **Entrenamiento_Kmeans.ipynb**: script que realiza el entrenamiento de modelos de clustering utilizando el algoritmo Kmeans.

-- Entrada: datos procesados

-- Salida: datos agrupados en clusters y métricas de ejecución
2. **Entrenamiento_Cure_v2.ipynb**: script que realiza el entrenamiento de modelos de clustering utilizando el algoritmo Cure.

-- Entrada: datos procesados

-- Salida: datos agrupados en clusters y métricas de ejecución

Visualización de resultados:
============

Los resultados obtenidos pueden visualizarse e interpretarse en los archivos generados y en los scripts.
Adicionalmente, se construyeron visualizaciones para facilitar la interpretación, disponibles en: https://public.tableau.com/profile/julio.vargas5953#!/vizhome/resultados_clustering/1_portada

