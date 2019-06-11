# titanicCleaningData

Limpieza y validación de un dataset de Supervivencia de pasajeros en el [Titanic](https://www.kaggle.com/c/titanic).

## Software
Para realizar este proyecto se ha utilizado R 3.6+ , RStudio y R markdown.
Las librerías empleadas en este trabajo son:

library(knitr)

library(stringr)
library(dplyr)

library(psych)

library(VIM)

library(gridExtra)

library(Rmisc)

library("car")

library(ggpubr)

library(corrplot)

library(caret)

library(MLmetrics)

library(GGally)

library(psych)

library(stats)

library(kableExtra) # Tables

library(nortest)

library('mice') # imputation

library('randomForest') # classification algorithm

library(graphics)

library('ggplot2') # visualization

library('ggthemes') # visualization

library('scales') # visualization


## Descripción de los ficheros
| Nombre del Fichero | Decripción |
|--------------------|------------|
| README.md	| Fichero que contiene información del proyecto y de los ficheros|
| muzo_limpieza.Rmd  | Fichero RMarkdown con código R y en el informe del trabajo |
| references.bib	   | Fichero de Referencias |
| muzo_limpieza.html	| Informe del trabajo en formato HTML |
| muzo_limpieza.pdf	| Informe del trabajo en formato PFD |
| input <ul><li>train.csv</il><li>test.csv</il><li>gender_submission.csv</il></ul>| Directorio con los dataset originales <ul><li>Fichero de datos de entrenamiento</il><li>Fichero de test</il><li>Fichero de Predicciones</il></ul>|
| output <ul><li>cleaning_train.csv</il><li>cleaning_test.csv</il><li>cleaning_full.csv</il></ul> | Directorio con los dataset limpios <ul><li>Ficherpo de datos de entrenamiento limpios</il><li>Fichero de test limpios</il><li>Fichero de datos de entrenamiento y test</il></ul>||

## Contribuyentes

| Contribuciones              | Firma                      |
|-----------------------------|----------------------------|
| Investigaciones previas     | Edison Muzo                |
| Redacción de las respuestas | Edison Muzo                |
| Desarrollo código           | Edison Muzo                |
<p align="center">
   <b>Tabla 2.</b> Grupo de Práctica.
</p>
