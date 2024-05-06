### Clustering y Reducción de Dimensionalidad

Este informe presenta un análisis de diferentes algoritmos de clustering aplicados a la base de datos Mice Protein Expression, que contiene niveles de expresión de proteínas en células cerebrales de ratones. Se evaluarán los algoritmos K-Means, DBSCAN y Clustering Aglomerativo, junto con pruebas de diferentes parámetros. Además, se aplicará PCA para reducir la dimensionalidad de los datos y se comparará su efecto en las métricas de rendimiento. Se analizarán cuatro métricas (completeness, homogeneidad, v-measure y silhouette) para evaluar la capacidad de los algoritmos para manejar outliers y determinar el número de clusters.

#### Objetivos Principales:
- Evaluar el rendimiento de algoritmos de clustering en la base de datos Mice Protein Expression.
- Comparar K-Means, DBSCAN y Clustering Aglomerativo.
- Aplicar PCA para reducir la dimensionalidad de los datos y analizar su efecto.

#### Metodología:
1. Lectura y preprocesamiento de datos.
2. Análisis exploratorio de datos.
3. Benchmarking de algoritmos de clustering.
4. Entrenamiento de algoritmos de clustering.
5. Evaluación de resultados.

#### Resultados y Conclusiones:
- Se observaron diferentes distribuciones en los datos y se identificaron outliers.
- Los algoritmos de clustering DBSCAN y sus variantes mostraron un buen rendimiento en comparación con K-Means.
- La inclusión o exclusión de outliers como un cluster extra afectó el desempeño de los algoritmos.
- La aplicación de PCA disminuyó la eficiencia de los algoritmos de clustering en esta base de datos.

Este informe proporciona información sobre la selección y evaluación de algoritmos de clustering, así como el efecto de la reducción de dimensionalidad en el rendimiento del clustering en la base de datos Mice Protein Expression.
