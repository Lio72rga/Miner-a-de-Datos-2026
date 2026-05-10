Clustering en Minería de Datos

Este repositorio contiene el desarrollo práctico de la Clase 6 de Minería de Datos, enfocada en técnicas de clustering utilizando Python y Scikit-learn.

El objetivo principal del trabajo fue aplicar algoritmos de aprendizaje no supervisado para detectar agrupamientos naturales dentro de distintos conjuntos de datos y comparar sus resultados mediante métricas de evaluación.

Objetivos del Trabajo
Comprender el funcionamiento del clustering.
Aplicar el algoritmo K-Means.
Aplicar el algoritmo DBScan.
Comparar distintos enfoques de segmentación.
Evaluar la calidad de los clusters.
Interpretar resultados y visualizaciones.
Tecnologías Utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Estructura del Proyecto
📁 Clase_6_Clustering
│
├── 📄 README.md
├── 📄 Clase_6_Clustering.ipynb
└── 📁 images
Contenido del Notebook
1. Introducción al Clustering

Se desarrolló una explicación teórica sobre:

aprendizaje no supervisado
clustering
tipos de agrupamiento
aplicaciones reales

También se trabajó con datasets sintéticos para visualizar agrupamientos naturales.

2. Aplicación de K-Means

Se implementó el algoritmo K-Means utilizando datasets sintéticos y el dataset Iris.

Actividades realizadas
generación de clusters
visualización de centroides
aplicación del método del codo
segmentación de datos
análisis de resultados
Resultados

K-Means logró separar correctamente grupos relativamente compactos y bien definidos.

3. Aplicación de DBScan

Se trabajó con el algoritmo DBScan utilizando datasets con formas complejas y presencia de ruido.

Actividades realizadas
ajuste de parámetros (eps y min_samples)
detección de outliers
segmentación basada en densidad
comparación con K-Means
Resultados

DBScan permitió detectar agrupamientos más flexibles y reconocer valores atípicos etiquetados como -1.

4. Evaluación de Clustering

Se utilizaron métricas para evaluar la calidad de los clusters generados.

Métricas utilizadas
Silhouette Score
Davies-Bouldin Index
Objetivo

Comparar objetivamente la separación y compactación de los grupos obtenidos por cada algoritmo.

Principales Aprendizajes

Durante esta actividad se logró:

comprender el funcionamiento del aprendizaje no supervisado
aplicar algoritmos de clustering
interpretar visualizaciones y métricas
ajustar hiperparámetros en DBScan
comparar distintos métodos de segmentación
analizar ventajas y limitaciones de cada algoritmo
Conclusiones
K-Means funciona mejor en datasets con clusters compactos y esféricos.
DBScan resulta más flexible frente a ruido y formas complejas.
La selección de parámetros influye significativamente en los resultados.
Las métricas de evaluación ayudan a validar la calidad del clustering obtenido.
Bibliografía
Scikit-learn Documentation
Seaborn Documentation
Python Documentation
