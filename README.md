# Análisis y Predicción de Cancelación de Clientes (Churn)

Este proyecto tiene como objetivo analizar los factores que influyen en la cancelación de clientes (churn) y desarrollar modelos predictivos para identificar a los clientes en riesgo.

## Contenido del Notebook

El notebook incluido (`[nombre_de_tu_notebook].ipynb`) realiza los siguientes pasos:

1.  **Extracción y Carga de Datos:** Carga el conjunto de datos de clientes.
2.  **Limpieza y Preprocesamiento de Datos:** Manejo de valores nulos, codificación de variables categóricas y preparación de los datos para el modelado.
3.  **Análisis Exploratorio de Datos:** Visualización y análisis de la distribución de la variable objetivo (Churn) y la correlación entre variables.
4.  **Análisis de Multicolinealidad:** Identificación y tratamiento de la multicolinealidad entre las variables predictoras.
5.  **Modelado Predictivo:** Entrenamiento y evaluación de varios modelos de clasificación para predecir el churn.
6.  **Evaluación de Modelos:** Comparación del rendimiento de los modelos utilizando métricas como Accuracy, ROC AUC, Precision y Recall.
7.  **Análisis de Factores Clave de Cancelación y Estrategias de Retención:** Un informe detallado que resume los principales hallazgos y propone estrategias para reducir la cancelación de clientes.
8.  **Serialización del Modelo:** Guardado del modelo predictivo entrenado para su uso futuro.

## Factores Clave de Cancelación Identificados

El análisis ha revelado que los principales factores que influyen en la cancelación de clientes incluyen (pero no se limitan a):

*   Antigüedad del cliente (`customer.tenure`)
*   Tipo de servicio de internet (fibra óptica vs. sin internet)
*   Tipo de contrato (contratos a largo plazo vs. corto plazo)
*   Método de pago (cheque electrónico)

Para un análisis más detallado, consulta el informe en el notebook.

## Estrategias de Retención Propuestas

Basado en los factores identificados, se sugieren diversas estrategias de retención, como programas de fidelización para clientes nuevos, mejora de servicios específicos, incentivos para contratos a largo plazo y segmentación de clientes en riesgo para ofertas dirigidas. Consulta el informe en el notebook para más detalles.

## Requisitos

Para ejecutar el notebook, necesitarás las siguientes librerías de Python:

*   pandas
*   numpy
*   matplotlib
*   seaborn
*   sklearn
*   imblearn
*   statsmodels

Puedes instalar estas dependencias usando pip:
