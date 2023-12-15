# Titanic Survival Prediction

## Descripción
Este proyecto se centra en predecir la supervivencia de los pasajeros del Titanic utilizando modelos de clasificación. Se realiza un análisis exploratorio de datos (EDA) y se implementan varios modelos de machine learning para lograr este objetivo.

## Instrucciones de Uso
- Clona este repositorio: `git clone https://github.com/victoryema/titanic-survival-prediction.git`
- Instala las dependencias: `pip install -r requirements.txt`
- Ejecuta el notebook principal: `jupyter notebook Titanic_Survival_Prediction.ipynb`

## Dependencias
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Estructura del Proyecto
- `data/`: Contiene los conjuntos de datos (train_titanic.csv, test_titanic.csv, gender_submission.csv).
- `notebooks/`: Archivos Jupyter Notebook para el análisis exploratorio y la implementación de modelos.
- `README.md`: Documentación principal del proyecto.
- `requirements.txt`: Lista de dependencias del proyecto.

## Conjunto de Datos
Se utiliza el conjunto de datos del Titanic, que incluye información sobre pasajeros como nombre, sexo, edad, clase, tarifa, etc.

## Análisis Exploratorio de Datos (EDA)
- Se exploran las relaciones entre diferentes atributos y la variable objetivo (Survived).
- Se presenta un resumen de estadísticas descriptivas y visualizaciones clave.

## Modelos Utilizados
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors
- Gaussian NB

## Resultados
Los modelos Decision Tree y Random Forest destacan con una precisión del 89% y 92%, respectivamente.

## Autor
Víctor Urra

## Agradecimientos
Agradezco a la comunidad de machine learning y a las bibliotecas como scikit-learn por su invaluable contribución.
