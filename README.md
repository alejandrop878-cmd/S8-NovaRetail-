# Análisis NovaRetail+ - Sprint 8

Este repositorio contiene el análisis realizado durante el Sprint 8 del caso NovaRetail+.

NovaRetail+ es una plataforma de comercio electrónico líder en Latinoamérica. El objetivo estratégico de este análisis correlacional es identificar y cuantificar los factores del comportamiento del cliente que están más fuertemente asociados con el **ingreso anual generado**, proveyendo al equipo de Crecimiento y Retención accionables basados en datos para el cierre del año operativo 2024.

## 🧠 Pregunta del Negocio

- ¿Qué factores del comportamiento del cliente están más fuertemente asociados con el ingreso anual generado?

## 📋 Flujo General del Proyecto.

1. Cargar y explorar el dataset
2. Preparar datos y documentar supuestos
3. Visualizar relaciones iniciales
4. Calcular correlaciones adecuadas
5. Interpretar resultados
6. Limitaciones y próximos pasos

## 🛠️ Tecnologías Utilizadas

* **Python** 🐍 
* **Pandas:** Limpieza de registros y manipulación estructural del DataFrame.
* **NumPy:** Soporte para operaciones vectorizadas y transformaciones matemáticas de las variables numéricas continuas.
* **SciPy:** Submódulo estadístico (`scipy.stats`) empleado para el cálculo computacional de los coeficientes de correlación:
    * `pearsonr`: Correlación lineal para datos continuos crudos.
    * `spearmanr`: Correlación de rangos monótonos robusta a outliers.
    * `pointbiserialr`: Correlación punto-biserial para cruces binario-continuo.
* **Seaborn:** Se utilizó para generar gráficos de dispersión (`scatterplot`) con diagnóstico de heterocedasticidad.
* **Matplotlib:** Empleado para la personalización de entornos, grids, etiquetas de ejes, títulos y renderizado final de las figuras del reporte.

## ▶️ Abrir el Notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TU_USUARIO_GITHUB/TU_REPOSITORIO/blob/main/TU_NOTEBOOK.ipynb)
