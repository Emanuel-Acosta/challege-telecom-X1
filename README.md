# Análisis de Evasión de Clientes (Churn) en TelecomX

## Descripción

Este proyecto tiene como objetivo principal analizar los patrones de evasión (churn) de clientes en la empresa TelecomX, una compañía del sector telecomunicaciones. La evasión de clientes impacta directamente en los ingresos y crecimiento de la empresa, por lo que comprender sus causas es vital para diseñar estrategias efectivas de retención.

A través de técnicas de limpieza, normalización y análisis exploratorio de datos (EDA), se identifican las variables que influyen en la cancelación del servicio, permitiendo orientar acciones comerciales y operativas para mejorar la fidelización.

## Contenido del Proyecto

1. Extracción de Datos  
   Obtención de datos en formato JSON desde una fuente pública (GitHub), correspondiente a un conjunto de clientes con características demográficas, detalles de servicios contratados y estado de cancelación.

2. Limpieza y Preprocesamiento  
   - Normalización de estructuras JSON anidadas a un DataFrame plano.  
   - Identificación y manejo de valores nulos, vacíos y duplicados.  
   - Conversión adecuada de tipos de datos, especialmente numéricos y categóricos.  
   - Creación de variables derivadas para mejorar la interpretación y análisis.

3. Análisis Exploratorio de Datos (EDA)  
   - Cálculo de tasa general de churn.  
   - Evaluación del impacto de variables categóricas como género, tipo de contrato, método de pago y servicios contratados.  
   - Análisis de variables numéricas, incluyendo tiempo en contrato y cargos totales, mediante visualizaciones como boxplots.  
   - Visualización y comparación clara de los perfiles de clientes que permanecen activos versus los que cancelan.

4. Conclusiones y Recomendaciones  
   - Identificación de factores clave asociados a la evasión.  
   - Sugerencias para políticas de retención y mejoras en la experiencia del cliente.  
   - Base para el desarrollo de modelos predictivos futuros.

## Tecnologías Utilizadas

- Python 3  
- Librerías: pandas, requests, matplotlib, seaborn

## Uso y Ejecución

El análisis está diseñado para ejecutarse en un entorno de Jupyter Notebook. El flujo es el siguiente:

1. Ejecutar la extracción de datos desde la URL especificada.  
2. Realizar la normalización y limpieza del dataset.  
3. Ejecutar las celdas de análisis exploratorio para obtener insights visuales y estadísticos.  
4. Revisar el informe final para la interpretación de resultados.

## Autor

Emanuel Acosta  
Ciencia de Datos | ONE + Alura LATAM


Para dudas, sugerencias o colaboraciones, contactar a:  
emacosta@example.com  (reemplazar con tu email real)
