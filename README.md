# ProyectoDataScience_Zito
Proyecto Final Data Science Coderhouse 
# Proyecto Final - Data Science

## Análisis y Modelado de Indicadores de Desarrollo Sostenible (UNSDG)

**Autor:** Guillermo Zito Vanni

---

## 1. Introducción

El presente proyecto tiene como objetivo analizar indicadores vinculados a los Objetivos de Desarrollo Sostenible (UNSDG) a partir de un dataset internacional que contiene información de múltiples países y años.

Se busca comprender las relaciones entre variables económicas, sociales y ambientales, y construir un modelo predictivo que permita clasificar el nivel de desarrollo de los países.

---

## 2. Objetivos

* Analizar el comportamiento de los indicadores de desarrollo sostenible.
* Identificar relaciones entre variables relevantes.
* Detectar patrones según el nivel de desarrollo de los países.
* Construir un modelo de clasificación para predecir el nivel de desarrollo.

---

## 3. Preguntas de investigación

* ¿Qué variables tienen mayor influencia en el nivel de desarrollo de un país?
* ¿Existen diferencias claras entre países desarrollados y en desarrollo?
* ¿Es posible predecir el nivel de desarrollo a partir de los indicadores disponibles?

---

## 4. Dataset

Se utilizó un dataset que contiene información de distintos países a lo largo del tiempo, incluyendo variables económicas, sociales y ambientales, así como una clasificación del nivel de desarrollo.

Archivo: `unsdg_2002_2020_dataset limpio.xlsx`

---

## 5. Análisis exploratorio de datos

Se realizaron análisis univariados, bivariados y multivariados con el objetivo de:

* Comprender la distribución de las variables
* Identificar correlaciones
* Detectar valores atípicos
* Analizar diferencias entre grupos

Se utilizaron gráficos como histogramas, boxplots y gráficos de dispersión.

---

## 6. Tratamiento de datos

* Identificación de valores faltantes
* Eliminación de registros incompletos relevantes
* Preparación de variables para el modelado
* Exclusión de la categoría "Not Specified" en la variable objetivo

---

## 7. Modelado

Se desarrolló un modelo de clasificación supervisada para predecir el nivel de desarrollo.

Etapas principales:

1. Selección de variables (feature selection)
2. División en conjunto de entrenamiento y prueba
3. Entrenamiento del modelo
4. Evaluación de resultados

---

## 8. Métricas de evaluación

Se utilizaron las siguientes métricas:

* Accuracy
* Precision
* Recall
* F1-score

---

## 9. Resultados y conclusiones

El análisis permitió identificar variables relevantes asociadas al nivel de desarrollo de los países.

El modelo de clasificación mostró un desempeño adecuado, permitiendo distinguir entre distintos niveles de desarrollo con resultados consistentes.

Se concluye que la combinación de variables económicas, sociales y ambientales resulta clave para explicar el desarrollo sostenible.

---

## 10. Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 11. Estructura del repositorio

* ProyectoFinal+ZitoVanni.ipynb
* unsdg_2002_2020_dataset limpio.xlsx
* README.md

---

## 12. Ejecución del proyecto

Abrir el archivo .ipynb en Jupyter Notebook, Visual Studio Code o Google Colab y ejecutar todas las celdas.

---
