# Proyecto: Mini EDA y Diseño de Pipelines con Scikit-Learn

Este proyecto forma parte de la serie de aprendizaje en **Ciencia de Datos 2**. En este repositorio se demuestra la implementación de un flujo de trabajo completo de preprocesamiento de datos utilizando el dataset clásico **Iris**.

## Objetivo
El objetivo principal es consolidar los conceptos de análisis exploratorio (EDA) y la creación de flujos de trabajo automatizados (Pipelines) para preparar datos para modelos de Machine Learning de manera eficiente y reproducible.

## Contenido del Proyecto

1.  **Análisis Exploratorio de Datos (Mini EDA):**
    *   Identificación y clasificación de tipos de variables (Numéricas Continuas, Categóricas Nominales).
    *   Visualización de distribuciones y relaciones entre variables mediante `pairplot` y mapas de calor de correlación con `Seaborn`.
    *   Detección de valores faltantes y análisis estadístico descriptivo.

2.  **Ingeniería de Características:**
    *   Implementación de una función personalizada (`calculate_area`) para obtener el área del pétalo.
    *   Uso de `FunctionTransformer` para integrar lógica personalizada dentro del pipeline de Scikit-Learn.

3.  **Diseño de Pipelines de Procesamiento:**
    *   **Pipeline Numérico:** Imputación de valores faltantes (estrategia de mediana) y estandarización de escalas (`StandardScaler`).
    *   **Pipeline Categórico:** Codificación de variables nominales mediante `OneHotEncoder`.
    *   **ColumnTransformer:** Integración de múltiples transformadores en un único objeto para procesar el conjunto de datos de forma paralela y organizada.

## Herramientas Utilizadas
- **Python 3**
- **Pandas** y **NumPy** (Manipulación de datos)
- **Matplotlib** y **Seaborn** (Visualización)
- **Scikit-Learn** (Pipelines, Preprocesamiento y Transformadores)

## Resultados
El flujo de trabajo transforma las 5 columnas originales en un conjunto de **8 características optimizadas**, incluyendo variables escaladas, variables binarias (One-Hot) y nuevas métricas calculadas, listas para ser consumidas por cualquier algoritmo de clasificación.

---
**Elaborado por:** Juan Guillermo Marulanda Mesa
**Fecha:** Marzo 2026
