📊 Práctica Profesional I – Análisis de Customer Churn

Repositorio correspondiente a la materia Práctica Profesional I de la Tecnicatura en Inteligencia Artificial y Ciencia de Datos del Instituto Superior Santo Domingo.

Primer semestre de 2026.

📚 Descripción del proyecto

En este trabajo realizamos un análisis de datos sobre el abandono de clientes (Customer Churn) en una empresa de telecomunicaciones.

Utilizamos el dataset IBM Telco Customer Churn, que contiene información de 7.043 clientes, incluyendo datos sobre su antigüedad, servicios contratados, tipo de contrato, cargos mensuales y abandono del servicio.

El objetivo fue explorar los datos, identificar posibles factores relacionados con el abandono de clientes y realizar las transformaciones necesarias para dejar el dataset preparado para un futuro modelo de Machine Learning.

🛠️ Tecnologías utilizadas

Python

Google Colab

Pandas

NumPy

Plotly

Scikit-learn

📊 Desarrollo del proyecto

1. Reconocimiento y exploración del dataset

Identificación de las dimensiones y variables.

Revisión de los tipos de datos.

Búsqueda de valores nulos y registros duplicados.

Análisis inicial de las características del dataset.

2. Limpieza de datos

Conversión de la variable TotalCharges a formato numérico.

Identificación y eliminación de 11 registros con valores faltantes.

Transformación de la variable SeniorCitizen para facilitar su interpretación.

Luego de la limpieza, el dataset quedó compuesto por 7.032 registros.

3. Planteamiento de hipótesis

Se plantearon diferentes hipótesis para analizar qué factores podrían estar relacionados con el abandono de clientes, considerando variables como:

Antigüedad del cliente.

Tipo de contrato.

Cantidad de servicios contratados.

Cargos mensuales.

4. Análisis exploratorio de datos (EDA)

Se realizaron diferentes visualizaciones interactivas utilizando Plotly para analizar:

La proporción de clientes que abandonaron el servicio.

La relación entre la antigüedad y el abandono.

El porcentaje de abandono según el tipo de contrato.

La cantidad de servicios contratados.

Los cargos mensuales según el tipo de servicio y contrato.

A partir de los gráficos se analizaron las hipótesis planteadas y se elaboraron conclusiones.

5. Preparación de datos para Machine Learning

Como última etapa del proyecto, se realizaron transformaciones para dejar los datos preparados para el desarrollo de un modelo de clasificación que permita predecir el abandono de clientes.

Se aplicaron las siguientes técnicas:

Label Encoding: conversión de variables categóricas binarias a valores numéricos.

One-Hot Encoding: transformación de variables categóricas con múltiples categorías.

StandardScaler: estandarización de variables numéricas mediante Z-score.

Eliminación de customerID: se quitó el identificador de cliente por no aportar información útil para el entrenamiento.

La variable objetivo Churn quedó codificada numéricamente, representando si el cliente abandonó o no el servicio.

El proyecto finaliza con el dataset transformado y preparado para la etapa de modelado. No se realizó el entrenamiento ni la evaluación de un modelo predictivo.

💡 Conclusión

Este trabajo nos permitió aplicar diferentes técnicas de análisis, limpieza y transformación de datos sobre un problema empresarial.

A través del análisis exploratorio pudimos estudiar distintos factores relacionados con el abandono de clientes y comprender la importancia de las visualizaciones para interpretar los datos.

También trabajamos en la preparación de las variables para Machine Learning, aprendiendo cómo transformar datos categóricos y estandarizar variables numéricas antes de utilizarlas en un modelo.

👩‍💻 Autora

Julia Belén Carrillo

Estudiante de Inteligencia Artificial y Ciencia de Datos.
