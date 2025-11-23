# MINE4101-202520-Taller2

Presentado por:
- Juan Manuel Rivera  - 201534131
- Johana Alejandra Rátiva - 202513844

# Objetivo

El objetivo de este cuadernillo es analizar el precio de venta de inmuebles de tipo apartamento en venta en la ciudad de Bogotá a partir de modelos de machine learning permitiendo descubrir insights, sugerir accionables y calcular el valor ganado de la implementación de una iniciativa ML.

# Alcance

A partir de un dataset de inmuebles ofertados en Bogotá, se construye un modelo de estimación de precio de venta que permita reducir el tiempo invertido por un perito avaluador de 6 horas a 1 hora mediante una herramienta automatizada.

Para ello, se desarrollaron las siguientes etapas:

1. Entendimiento y preparación de los datos:
Identificación de tipos de variables y filtros iniciales para seleccionar únicamente apartamentos usados en venta (nicho de interés).

2. Análisis exploratorio:
Visualización de variables categóricas, numéricas y booleanas para comprender sus distribuciones. Se estudiaron frecuencias y correlaciones para priorizar variables relevantes para el modelado.

3. Limpieza y preparación del dataset:
Eliminación de valores nulos y realización de imputaciones utilizando únicamente el conjunto de entrenamiento (train) para evitar fugas de información (data leakage).

4. Modelado:
División del dataset en train, validation y test.
Escalamiento de variables usando parámetros ajustados únicamente con train.
Experimentación con regresión lineal y regresión Ridge mediante búsqueda de hiperparámetros.
La métrica seleccionada fue RMSE, eligiendo la regresión lineal como mejor modelo.

5. Análisis de residuos:
Comparación entre precios reales y predichos para identificar el porcentaje de inmuebles subestimados en más de 20 millones. Esto permite evaluar la calidad del modelo y detectar intervalos de precio donde presenta mejor desempeño.

6. Interpretabilidad (LIME y SHAP):
Análisis de las contribuciones de las variables sobre predicciones específicas (LIME) y evaluación global de su impacto sobre el conjunto de test (SHAP).

7. Análisis de generación de valor:
Estimación del impacto operativo de la automatización del cálculo del precio de venta.

# Conclusiones (insights)



# Instrucciones de ejecución

# Dependencias
