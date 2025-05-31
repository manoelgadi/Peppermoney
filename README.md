# Peppermoney - Propuesta de Curso de Modelado Predictivo

Este repositorio contiene la propuesta de un curso o plan de estudios enfocado en técnicas de modelado predictivo, cubriendo desde modelos lineales generalizados hasta redes neuronales y detección de anomalías. El objetivo es proporcionar una base sólida tanto teórica como práctica en diversas áreas del aprendizaje automático aplicado.

## Estructura del Curso (Propuesta)

La propuesta se organiza en módulos temáticos, cada uno con una duración estimada en horas. Se enfatiza la comprensión conceptual y la aplicación práctica de cada técnica.

### 1\. Seis Estadios de desarrollo de modelos
  * **Duración:** 2 horas
  * **Contenido:**
      * Explicación de Regresión Lineal.
      * Explicación de los estadios de desarrollo de modelos para Regresión Lineal.
      * Enfoque del impacto del estadio 1 (objetivo), en el estadio 2 (diseño de vairables) y del estadio 2 en el estadio 4 (elección del modelo), y finalmente en el estadio 3 (supuesto del modelo elegido).
* **Conclusión:**
      * Esta sesión crear los pilares para GLM, donde de cambian elementos de los estadios para ajustar a fallas en los supuestos del modelo.
        

### 2\. Modelos Lineales Generalizados (Generalized Linear Models)

  * **Duración:** 2 horas
  * **Contenido:**
      * Explicación de GLM y penalización.
      * Manejo de multicolinealidad y cómo esta la afecta.
      * Modelos de regresión (L1, L2, ElasticNet, Logística).
 
### 3\. Modelos Lineales Generalizados (Generalized Linear Models)

  * **Duración:** 2 horas
  * **Contenido:**
      * Explicación de GLM y cambio en las distribuiciones.
      * Distribuciones (Binomial, Gaussiana, Poisson, Tweedie, Gamma, Huber).
      * Casos especiales de modelos de dos etapas (Binomial/Gaussiana) para regresión no correlacionada.


### 4\. Máquinas de Soporte Vectorial (Support Vector Machines)

  * **Duración:** 2 horas
  * **Contenido:**
      * Explicación de SVM.
      * Cómo SVM maneja outliers y cómo esta técnica elimina la multicolinealidad y los outliers multivariantes (concepto de Distancia de Mahalanobis).
      * Kernels (lineal, polinomial, radial, RBF).
      * Conceptos de liblinear y libsvm.

### 5\. Modelos Aditivos Generalizados (Generalized Additive Models)

  * **Duración:** 0 horas (No se cree relevante para la práctica, ya que los árboles de decisión funcionan mejor cuando la relación no es lineal o no hay patrón).
  * **Contenido:**
      * GAM y GA2M.

### 6\. Modelos Basados en Árboles (Tree-based Models)

  * **Duración:** 2 horas
  * **Contenido:**
      * Árboles de decisión (o CART).
      * Bosques aleatorios (Random Forests).
      * XGBoost (o GBDT) - Binomial, Gaussiana, Poisson, Tweedie, Gamma, Huber.
      * Otros conceptos de ensamblaje (Voting Hard/Soft y Stacking).
      * LightGBM, CatBoost, AdaBoost, RuleFit.

### 7\. Modelos de Series de Tiempo (Time series-specific Models)

  * **Duración:** 2 horas
  * **Contenido:**
      * ARIMA.
      * Modelos exponenciales suavizados.
      * TBATS.
      * Prophet.
      * LSTMs.

### 8\. Modelos No Supervisados (Unsupervised Models)

  * **Duración:** 2 horas
  * **Contenido:**
      * Jerárquico, k-Means, HDBSCAN.

### 9\. Reducción de Dimensionalidad (Dimensionality Reduction)

  * **Duración:** 2 horas
  * **Contenido:**
      * Análisis de Componentes Principales (PCA).
      * Análisis de Ecuaciones Estructurales (SEM) para identificar patrones ocultos.

### 10\. Marketing - Encuestas de Opinión / Entrevista con Expertos / Análisis Cualitativo

  * **Duración:** 2 horas
  * **Contenido:**
      * **AHP:** [Cómo aplicar el método de análisis de jerarquía analítica](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DkYcQk4Hqe5VY)
      * **Delphi:** [Delphi para la investigación de políticas: una guía para el investigador](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3D0kFj2fVRqQGM)
      * **Modified Delphi:** [Una explicación del método Delphi modificado](https://www.google.com/search?q=https://www.youtube.com/watch%3Fv%3DDCVgaqZPJXk)

### 11\. Detección de Anomalías (Anomaly Detection Models)

  * **Duración:** 2 horas (Se cree que en dos horas se puede, pero hay que ver).
  * **Contenido:**
      * Aislamiento del bosque (Isolation Forest).
      * One-Class SVM.
      * Mediana Desviación Absoluta.
      * Clúster de densidad.
      * Mezcladores de modelos de anomalías.
      * Deep Autoencoder (keras).
      * Variational Autoencoder (keras).

### 12\. Otros Métodos (Other Methods)

  * **Duración:** 2 horas (Se puede aplicar algoritmo genético para esta y otras aplicaciones).
  * **Contenido:**
      * Programación Genética (algoritmo genético para regresión simbólica).
      * K-Nearest Neighbors (K-NN - tres distancias).
      * Clasificadores basados en reglas (Rule-based classifiers).
      * Regresión isótónica (Isotonic Regression) - se utiliza para predecir puntuaciones de otros modelos.
