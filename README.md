# **Clasificación de Tumores de Mama**

Este proyecto utiliza una base de datos sobre cáncer de mama obtenida de los Hospitales de la Universidad de Wisconsin, Madison, recopilada por el Dr. William H. Wolberg. El objetivo de este análisis es explorar y preparar estos datos para implementar un modelo de clasificación que determine si un tumor es benigno o maligno.

# **Relevancia del Proyecto**

La detección temprana y precisa de tumores malignos es fundamental para el tratamiento eficaz del cáncer de mama, que es una de las principales causas de muerte por cáncer en mujeres a nivel mundial. Implementar modelos de clasificación eficientes permite a los profesionales de la salud tomar decisiones informadas y rápidas, mejorando así las tasas de supervivencia y reduciendo la carga de tratamientos innecesarios para los pacientes con tumores benignos.

El dataset está compuesto por varias características recopiladas de muestras de células de pacientes. La mayoría de estas características son de tipo entero y están codificadas en una escala ordinal del 1 al 10, consideradas como variables categóricas ordinales. Esto incluye el espesor del grupo celular, uniformidad del tamaño de célula, uniformidad de forma celular, adhesión marginal, tamaño de célula epitelial única, cromatina suave, núcleos desnudos, nucleolos normales y el índice de mitosis.

# Funcionamiento

En este proyecto, se realiza el siguiente flujo de trabajo:

**1**. Análisis Exploratorio de Datos (EDA) y preprocesamiento de datos: 
Exploración inicial de los datos para comprender su estructura y características y limpieza y transformación de los datos, incluyendo la imputación de valores faltantes y la codificación de variables categóricas.

**2**. Entrenamiento de Modelos: 
Implementación y evaluación de diferentes modelos de clasificación, como la Regresión Logística, SVM, y Random Forest.

**3**. Evaluación del Modelo: 
Evaluación de la precisión y otras métricas de rendimiento de los modelos entrenados.

**4**. Análisis de los resultados obtenidos

# Tecnologías Empleadas

Lenguaje de Programación: Python
Bibliotecas Principales:
* pandas: para manipulación y análisis de datos
* numpy: para operaciones numéricas
* scikit-learn: para implementación de modelos de machine learning, validación cruzada y metricas de desempeño
* matplotlib y seaborn: para visualización de datos
* Entorno de Desarrollo: Jupyter Notebook
