# Peppermoney - Propuesta de Curso de Modelado Predictivo

Este repositorio contiene la propuesta de un curso o plan de estudios enfocado en técnicas de modelado predictivo, cubriendo desde modelos lineales generalizados hasta redes neuronales y detección de anomalías. El objetivo es proporcionar una base sólida tanto teórica como práctica en diversas áreas del aprendizaje automático aplicado.

## Estructura del Curso (Propuesta)

La propuesta se organiza en módulos temáticos, cada uno con una duración estimada en horas. Se enfatiza la comprensión conceptual y la aplicación práctica de cada técnica.

### 1\. Seis Estadios de desarrollo de modelos
  * **Contenido:**
      * Explicación de Regresión Lineal.
      * Explicación de los estadios de desarrollo de modelos para Regresión Lineal.
      * Enfoque del impacto del estadio 1 (objetivo), en el estadio 2 (diseño de vairables) y del estadio 2 en el estadio 4 (elección del modelo), y finalmente en el estadio 3 (supuesto del modelo elegido).
* **Conclusión:**
      * Esta sesión crear los pilares para GLM, donde de cambian elementos de los estadios para ajustar a fallas en los supuestos del modelo.
        

### 2\. Modelos Lineales Generalizados (Generalized Linear Models)
  * **Contenido:**
      * Explicación de GLM y penalización.
      * Manejo de multicolinealidad y cómo esta la afecta.
      * Modelos de regresión (L1, L2, ElasticNet, Logística).
 
### 3\. Modelos Lineales Generalizados (Generalized Linear Models)
  * **Contenido:**
      * Explicación de GLM y cambio en las distribuiciones.
      * Distribuciones (Binomial, Gaussiana, Poisson, Tweedie, Gamma, Huber).
      * Casos especiales de modelos de dos etapas (Binomial/Gaussiana) para regresión no correlacionada.
   
### 4\. Modelos No Supervisados - Clustering (Segmentación)
  * **Contenido:**
      * Jerárquico, k-Means, HDBSCAN.

### 5\. Reducción de Dimensionalidad (Dimensionality Reduction)
  * **Contenido:**
      * Análisis de Componentes Principales (PCA).
      * Análisis de Ecuaciones Estructurales (SEM) para identificar patrones ocultos.

### 6\. Marketing - Encuestas de Opinión / Entrevista con Expertos / Análisis Cualitativo
  * **Contenido:**
      * **AHP:** [Cómo aplicar el método de análisis de jerarquía analítica](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DkYcQk4Hqe5VY)

### 7\. Máquinas de Soporte Vectorial (Support Vector Machines)
  * **Contenido:**
      * Explicación de SVM.
      * Cómo SVM maneja outliers y cómo esta técnica elimina la multicolinealidad y los outliers multivariantes (concepto de Distancia de Mahalanobis).
      * Kernels (lineal, polinomial, radial, RBF).
      * Conceptos de liblinear y libsvm.

### 8 y 9\. Modelos Basados en Árboles (Tree-based Models)
  * **Contenido:**
      * Árboles de decisión (o CART).
      * Bosques aleatorios (Random Forests).
      * XGBoost (o GBDT) - Binomial, Gaussiana, Poisson, Tweedie, Gamma, Huber.
      * Otros conceptos de ensamblaje (Voting Hard/Soft y Stacking).
      * LightGBM, CatBoost, AdaBoost, RuleFit.

### 10 y 11\. Modelos de Series de Tiempo (Time series-specific Models)
 * **Contenido:**
      * ARIMA.
      * Modelos exponenciales suavizados.
      * TBATS.
      * Prophet.
      * LSTMs.


### 12\. Detección de Anomalías (Anomaly Detection Models)
  * **Contenido:**
      * Aislamiento del bosque (Isolation Forest).
      * One-Class SVM.
      * Mediana Desviación Absoluta.
      * Clúster de densidad.
      * Mezcladores de modelos de anomalías.
      * Deep Autoencoder (keras).
      * Variational Autoencoder (keras).

### 13\. Otros Métodos (Other Methods)
  * **Contenido:**
      * Programación Genética (algoritmo genético para regresión simbólica).
      * K-Nearest Neighbors (K-NN - tres distancias).
      * Clasificadores basados en reglas (Rule-based classifiers).
      * Regresión isótónica (Isotonic Regression) - se utiliza para predecir puntuaciones de otros modelos.
