# 📊 Aprendizaje Estadístico

[![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)]()
[![Pandas](https://img.shields.io/badge/Pandas-Análisis%20de%20Datos-150458?style=for-the-badge&logo=pandas&logoColor=white)]()
[![scikit-learn](https://img.shields.io/badge/scikit--learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)]()
[![Git](https://img.shields.io/badge/Git-Control%20de%20Versiones-F05032?style=for-the-badge&logo=git&logoColor=white)]()
[![License](https://img.shields.io/badge/Licencia-MIT-black?style=for-the-badge)]()

## Sesión 6 — Regresión Exponencial y Regresión Logística

## 📌 Descripción General

Este repositorio contiene el desarrollo del caso de estudio de la Sesión 6, centrado en la aplicación de **regresión exponencial** y **regresión logística** a un escenario real de negocio: **MiBolsillo**, una fintech colombiana con sede en Medellín que ofrece billetera digital y microcréditos.

A partir de dos conjuntos de datos simulados, se desarrollaron análisis orientados a responder dos preguntas de negocio completamente distintas:

- ¿Qué tan rápido está creciendo el número de usuarios nuevos por día tras el lanzamiento de una campaña de referidos, y qué implica esto para la capacidad de servidores y de soporte al cliente?
- ¿Cuál es la probabilidad de que un solicitante incumpla un microcrédito, a partir de su información disponible al momento de la solicitud, y qué tan confiable es un umbral fijo de aprobación del 50%?

El trabajo se desarrolló íntegramente en un **Jupyter Notebook**, combinando código, salidas (numéricas y gráficas) y celdas de interpretación redactadas en lenguaje de negocio.

------------------------------------------------------------------------

## 👨‍💻 Integrantes

- **Juan Daniel Bogotá Fuentes**
- **Jeisson David Sanchez Gomez**

------------------------------------------------------------------------

## 🧠 Estructura del Análisis (Notebook)

### Parte 1 — Crecimiento de usuarios tras la campaña de referidos (Regresión Exponencial)

Planteamiento del problema a partir del crecimiento acelerado de usuarios nuevos por día; análisis exploratorio de la serie de tiempo; ajuste del modelo exponencial mediante linearización con `scikit-learn` y verificación con `scipy.optimize.curve_fit`; interpretación de los parámetros en términos de tasa de crecimiento diaria y tiempo de duplicación; conclusión de negocio sobre necesidades de infraestructura y soporte; y limitaciones del supuesto de crecimiento exponencial sostenido.

### Parte 2 — Riesgo de incumplimiento en microcréditos (Regresión Logística)

Planteamiento del problema de estimar la probabilidad de incumplimiento de un crédito; análisis exploratorio comparando las variables predictoras según el resultado del crédito; ajuste del modelo con `statsmodels` (para interpretación de coeficientes) y con `scikit-learn` (entrenamiento, predicción y evaluación con exactitud, matriz de confusión y curva ROC); interpretación de los coeficientes mediante odds ratios traducidos a magnitudes de negocio; conclusión de negocio evaluando distintos perfiles de solicitantes; y limitaciones relacionadas con el horizonte de los datos y el umbral de decisión.

------------------------------------------------------------------------

## 📁 Estructura del Proyecto

    📦 Sesion_6_Otros_Modelos_De_Regresion
     ├── README.md
     ├── Sanchez_Jeisson_y_Bogota_Juan_CasoEstudio_sesion6.ipynb
     ├── Sesion6_Regresion_Exponencial_Logistica_MiBolsillo.docx.pdf
     └── Sesión_6_Regresión_Exponencial_y_Logística_AgroHuila.ipynb

### 📖 Contenido

- **Desarrollo del taller** en Jupyter Notebook (Google Colab / VS Code):
  `Sanchez_Jeisson_y_Bogota_Juan_CasoEstudio_sesion6.ipynb`
- **Enunciado del taller** (caso de estudio MiBolsillo):
  `Sesion6_Regresion_Exponencial_Logistica_MiBolsillo.docx.pdf`
- **Recurso de la Sesión 6** (ejemplo guía del profesor, caso AgroHuila):
  `Sesión_6_Regresión_Exponencial_y_Logística_AgroHuila.ipynb`

------------------------------------------------------------------------

## 🛠 Tecnologías

- Python
- Pandas / NumPy
- SciPy (`curve_fit`, `stats`)
- statsmodels (interpretación de coeficientes)
- scikit-learn (entrenamiento y evaluación de modelos)
- Matplotlib / Seaborn (visualización)
- Jupyter Notebook / Google Colab / VS Code
- Git y GitHub

------------------------------------------------------------------------

## 📈 Aprendizajes Obtenidos

A través de este taller se desarrollaron las siguientes competencias:

- Reconocimiento del tipo de modelo adecuado (lineal, exponencial o logístico) según la naturaleza de la variable respuesta.
- Ajuste de un modelo de regresión exponencial mediante linearización y mediante optimización no lineal directa, y comparación de ambos métodos.
- Ajuste e interpretación de un modelo de regresión logística, incluyendo la traducción de odds ratios a magnitudes de negocio.
- Evaluación de modelos de clasificación mediante exactitud, matriz de confusión, AUC y curva ROC, y análisis del costo relativo de falsos positivos y falsos negativos.
- Identificación de las limitaciones y supuestos que deben comunicarse antes de tomar decisiones de negocio con base en un modelo estadístico.
- Redacción de conclusiones orientadas a un público de negocio, no técnico.
- Trabajo colaborativo mediante Git y GitHub.

------------------------------------------------------------------------

## 👨‍💻 Autores

[![GitHub](https://img.shields.io/badge/GitHub-JeissonS02-181717?style=for-the-badge&logo=github)](https://github.com/JeissonS02)
[![GitHub](https://img.shields.io/badge/GitHub-JuanBogota-181717?style=for-the-badge&logo=github)](https://github.com/JuanBogota)