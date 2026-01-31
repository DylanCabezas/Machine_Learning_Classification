# Proyecto 2: Métodos de Clasificación con Manim

## Introducción

Se desarrolla una demostración visual e interactiva de algoritmos de clasificación supervisada,
específicamente K-Nearest Neighbors (KNN) y Árboles de Decisión, utilizando la librería
Manim Community para la creación de animaciones y scikit-learn para la implementación
y evaluación de los modelos.

El objetivo principal es facilitar la comprensión conceptual y práctica de estos métodos
mediante visualizaciones animadas, comparaciones experimentales y métricas de desempeño.

## Integrantes

Ricardo Manuel Meza León  
Miguel Ángel Ramos Bonilla  
Dylan Andrés Cabezas Ramírez  
Frans Josep Trujillo Flores  

## Requisitos

Python 3.9+  
Manim Community  
scikit-learn  
matplotlib  
seaborn  
numpy  


Cada escena explica un concepto:

Introducción  
Teoría de KNN  
Teoría de Árboles de Decisión  
Experimentos con datasets  
Visualización de métricas  

## Estrategias del Proyecto

### Visualización inicial (Iris)

Se restringieron las clases y características del dataset Iris para permitir la visualización
de fronteras de decisión en dos dimensiones.

### Explicación teórica

Se desarrollaron animaciones con texto y fórmulas matemáticas para explicar el funcionamiento
de KNN y Árboles de Decisión.

### Comparación práctica (Wine)

Ambos modelos fueron entrenados y evaluados bajo las mismas condiciones utilizando el dataset Wine,
permitiendo una comparación justa de su desempeño.

### Evaluación

Se analizaron métricas de desempeño y tiempos de ejecución para evaluar la precisión y eficiencia
computacional de cada algoritmo.

### Visualización

Los resultados se presentaron mediante gráficos de barras animados que facilitan la comparación
entre los métodos evaluados.

## Métricas Utilizadas

### Accuracy

Mide la proporción de predicciones correctas sobre el total de ejemplos.
Se utiliza como una primera referencia del desempeño global del modelo.

### F1-Score (ponderado)

Combina precisión y recall en una sola métrica.
Es especialmente útil en problemas de clasificación multiclase, como el dataset Wine,
ya que equilibra el rendimiento entre todas las clases.

### Tiempo de entrenamiento y predicción

Evalúa la eficiencia computacional de cada algoritmo.

KNN: más costoso en la etapa de predicción, ya que calcula distancias contra todas las instancias.  
Árbol de Decisión: más rápido, debido a que aplica reglas jerárquicas previamente aprendidas.

### Matriz de confusión

Representa los aciertos y errores por clase.
Permite identificar qué clases se confunden con mayor frecuencia y analizar errores específicos.

## Resultados

Ambos algoritmos alcanzaron una alta accuracy en el dataset Wine.
El Árbol de Decisión presentó mejor eficiencia computacional y una buena interpretabilidad.
KNN depende fuertemente de la distribución de los datos y resulta más costoso en predicción.
Las animaciones y visualizaciones gráficas facilitaron la comprensión de los conceptos y resultados.


## Referencias

Bishop, C. M. Pattern Recognition and Machine Learning. Springer, 2006.  
Hastie, T., Tibshirani, R., Friedman, J. The Elements of Statistical Learning. Springer, 2009.  
Manim Community Documentation: https://docs.manim.community/en/stable/  
Scikit-learn Documentation: https://scikit-learn.org/stable/
