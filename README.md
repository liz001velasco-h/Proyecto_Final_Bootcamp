# Predicción de Abandono de Clientes mediante Machine Learning

## Descripción del proyecto

Este proyecto desarrolla un modelo de **Machine Learning para la predicción del abandono de clientes (Customer Churn)** utilizando técnicas de aprendizaje supervisado. El objetivo es identificar de manera anticipada a los clientes con mayor probabilidad de cancelar un servicio, proporcionando información que permita diseñar estrategias de retención más efectivas.

El proyecto sigue un flujo completo de Ciencia de Datos, desde la exploración y preparación de los datos hasta la construcción, evaluación e interpretación de diferentes modelos de clasificación.

---

## Objetivos

- Analizar el comportamiento de los clientes mediante técnicas de análisis exploratorio de datos (EDA).
- Preparar y transformar el conjunto de datos para el entrenamiento de modelos predictivos.
- Implementar diferentes algoritmos de clasificación.
- Comparar el desempeño de los modelos mediante métricas de evaluación.
- Seleccionar el modelo con mejor capacidad predictiva para apoyar la toma de decisiones empresariales.

---

## Dataset

Se utilizó el conjunto de datos **Telco Customer Churn**, ampliamente empleado para el estudio de problemas de clasificación en Ciencia de Datos.

Las variables incluyen información relacionada con:

- Características demográficas.
- Servicios contratados.
- Tipo de contrato.
- Tiempo de permanencia del cliente.
- Facturación.
- Método de pago.
- Cargos mensuales y totales.
- Variable objetivo: **Churn** (abandono del cliente).

---

## Tecnologías utilizadas

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Metodología

El desarrollo del proyecto siguió las siguientes etapas:

### 1. Importación de librerías

Carga de las librerías necesarias para el análisis y modelado.

### 2. Exploración de datos (EDA)

- Análisis de variables.
- Identificación de valores faltantes.
- Detección de registros duplicados.
- Estadística descriptiva.
- Visualización de distribuciones.
- Análisis de correlaciones.

### 3. Preprocesamiento

- Limpieza de datos.
- Conversión de tipos de variables.
- Codificación de variables categóricas.
- Escalamiento de variables numéricas.
- División del conjunto de datos en entrenamiento y prueba.

### 4. Entrenamiento de modelos

Se implementaron tres algoritmos de clasificación:

- Regresión Logística
- Árbol de Decisión
- Random Forest

### 5. Evaluación

Los modelos fueron comparados mediante las siguientes métricas:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Matriz de Confusión
- Curva ROC

### 6. Selección del mejor modelo

Finalmente, se comparó el desempeño de todos los modelos para seleccionar la alternativa con mejores resultados predictivos.

---

## Resultados

El análisis permitió comparar el desempeño de diferentes algoritmos de clasificación y evaluar su capacidad para identificar clientes con riesgo de abandono.

Las métricas obtenidas permitieron determinar el modelo con mejor equilibrio entre precisión, sensibilidad y capacidad de discriminación, constituyendo una herramienta útil para apoyar estrategias de retención de clientes.

---

## Aplicación práctica

La predicción del abandono de clientes constituye una herramienta estratégica para las organizaciones, ya que permite identificar clientes con alta probabilidad de cancelar un servicio antes de que esto ocurra.

Los resultados obtenidos pueden utilizarse para:

- Diseñar campañas de fidelización.
- Reducir la tasa de abandono.
- Optimizar recursos comerciales.
- Mejorar la satisfacción del cliente.
- Apoyar la toma de decisiones basada en datos.

---

## Autora

**Lizbeth Velasco Hernández**

## Licencia

Este proyecto fue desarrollado con fines académicos como parte de un Bootcamp de Ciencia de Datos.
