# Analisis-Supervivencia-Melanoma
Este proyecto realiza un análisis de supervivencia utilizando el conjunto de datos **Melanoma**. El objetivo es calcular la incidencia acumulada y aplicar métodos de regresión de Fine-Gray para examinar la mortalidad por melanoma, diferenciando según la presencia o ausencia de úlceras.

## Objetivo

El análisis tiene como objetivo estudiar la relación entre varios factores (como el sexo, la edad y la presencia de úlceras) y la supervivencia en pacientes con melanoma. El análisis se realiza mediante un análisis de supervivencia y la estimación de la incidencia acumulada para riesgos competitivos.

## Estructura del Proyecto

- `Analisis/`: Contiene los archivos del análisis.
  - `Código guente`: Código fuente utilizado en este trabajo.
  - `Supervivencia_Melanoma.Rmd`: Documento en R Markdown que incluye el código y la interpretación de los resultados.

- `Data/`: Contiene los datasets necesarios para el análisis.
  - `Melanoma_data.csv`: Dataset de melanoma.
  
- `Resultados/`: Guarda los resultados del análisis, como gráficos y explicaciones en texto.
  - `Incidencia_Acumulada_Melanoma/`: Gráfico de la incidencia acumulada del melanoma.
  - `Incidencia_acumulada_segun_ulceras/`: Gráfico de la incidencia acumulada del melanoma teniendo en cuenta las úlceras.
  - `README`: Resumen de los resultados del análisis.
  - `p-valor incidencia acumulada segun ulceras/`: Estadísticos para la incidencia acumulada según úlceras.
  - `p-valor/`: Estadísticos para el test de Fine-Gray

- `README.md`: Este archivo con información sobre el proyecto, instrucciones para reproducir el análisis, y descripción del contenido.

## Requisitos

Para ejecutar el análisis, es necesario tener instaladas las siguientes librerías de R:

```r
install.packages(c(
  "caret", "ConfusionTableR", "DataExplorer", "dplyr", "ggplot2", "ggthemes",
  "kableExtra", "ModelMetrics", "openxlsx", "plotly", "probably", "pROC",
  "psych", "purrr", "randomForest", "reshape2", "skimr", "stringr", "tidymodels",
  "WRS2", "tidyverse", "univariateML", "vip", "xgboost", "readr", "vcd",
  "corrplot", "MASS", "gtools", "gplots", "cmprsk", "glue"
))
