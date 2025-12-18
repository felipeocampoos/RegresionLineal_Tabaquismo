# Análisis de Costo del Seguro Médico con Regresión Polinómica

## Introducción

En este proyecto, analizamos cómo diversos factores afectan los costos médicos utilizando **Regresión Polinómica**. El objetivo es identificar qué variables tienen mayor impacto en los cargos de los costos médicos y desarrollar un modelo que prediga estos costos. Para ello, exploramos datos relacionados con características como la edad, el índice de masa corporal (IMC), el tabaquismo y la cantidad de hijos.

### Factores Considerados

Los factores que se analizan en este proyecto son:

- **Edad:** Edad del beneficiario principal.
- **IMC:** Índice de masa corporal, que proporciona información sobre el peso relativo con respecto a la altura.
- **Tabaquismo:** Si el beneficiario es fumador o no.
- **Número de hijos:** Número de dependientes cubiertos por el seguro médico.

## Objetivos del Proyecto

1. **Análisis exploratorio de datos (EDA):** Analizar y visualizar cómo se distribuyen los costos médicos según diferentes factores.
2. **Impacto de los factores:** Evaluar cómo factores como el tabaquismo, la edad, el IMC y el número de hijos afectan los costos médicos.
3. **Construcción de modelos:** Probar diferentes modelos de regresión para predecir los costos médicos, con un enfoque en **Regresión Polinómica**.
4. **Evaluación del modelo:** Medir el rendimiento del modelo de regresión y cómo se compara con los factores observados.

## Resultados Clave

- **Tabaquismo:** El tabaquismo es el factor con el mayor impacto en los costos médicos.
- **IMC y Edad:** Aunque el impacto del IMC y la edad es significativo, es menor que el del tabaquismo.
- **Número de hijos:** Las personas con hijos tienden a tener costos médicos más altos en general.
- **Regresión Polinómica:** La regresión polinómica resultó ser el mejor modelo para predecir los costos médicos.

## Librerías Utilizadas

En este proyecto se utilizaron las siguientes librerías:

- **Scikit-learn:** Para la construcción de los modelos de regresión.
- **Matplotlib y Seaborn:** Para la visualización de los resultados y gráficos.
- **Pandas:** Para la manipulación y análisis de los datos.

## Procedimiento

1. **Preparación de datos:** Carga y preprocesamiento del dataset.
2. **Análisis exploratorio de datos (EDA):** Visualización de la distribución de los cargos médicos según factores como la región, el tabaquismo y el número de hijos.
3. **Regresión Polinómica:** Aplicación de regresión polinómica para mejorar la predicción de los costos médicos.
4. **Evaluación:** Comparación del rendimiento del modelo con otros enfoques y análisis de la relevancia de cada factor.
