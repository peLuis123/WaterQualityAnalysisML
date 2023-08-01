
# Análisis de Calidad del Agua

Este proyecto realiza un análisis de calidad del agua utilizando técnicas de análisis de datos y aprendizaje automático. Se utiliza un conjunto de datos sobre la calidad del agua y se aplican diversas técnicas para explorar, visualizar y predecir características de la calidad del agua.

## Requisitos

Antes de ejecutar el código, asegúrate de tener instaladas las siguientes bibliotecas:

- pandas
- numpy
- matplotlib
- seaborn
- sklearn

Para instalar estas bibliotecas, puedes utilizar el siguiente comando en tu entorno de Python:

pip install pandas numpy matplotlib seaborn scikit-learn

## Descripción de archivos

- calidad_agua.csv\`: Es el conjunto de datos original que contiene información sobre la calidad del agua.
- datos_entrenamiento.csv\`: Es el conjunto de datos preparado para el entrenamiento de modelos de aprendizaje automático.
- agua_potable_test.csv\`: Es el conjunto de datos sin etiquetas utilizado para hacer predicciones con los modelos entrenados.
- datos_prueba_con_predicciones.csv\`: Es el conjunto de datos con las predicciones realizadas por los modelos en el conjunto de prueba.

## Cómo ejecutar el código

1. Descarga los archivos \`calidad_agua.csv\` y \`agua_potable_test.csv\` y colócalos en la misma carpeta que el código fuente.

2. Asegúrate de tener todas las bibliotecas requeridas instaladas (pandas, numpy, matplotlib, seaborn, sklearn).

3. Ejecuta el código para realizar análisis exploratorios, entrenar y evaluar los modelos de aprendizaje automático.

## Funcionalidades del código

El código contiene las siguientes funciones:

- checks_null_values(df)\`: Verifica y muestra si hay valores nulos en el DataFrame proporcionado.
- check_df(df)\`: Verifica si el DataFrame no está vacío y no tiene columnas duplicadas.
- most_common_value(df)\`: Muestra la moda (valor más frecuente) y la cantidad de veces que aparece para cada columna en el DataFrame.
- histogram_plot(df, numerical_columns)\`: Muestra histogramas para las columnas numéricas del DataFrame.
- heatmap_plot(df, dependent_variable)\`: Muestra un heatmap que muestra las correlaciones entre las variables independientes y la variable dependiente.
- box_plot(df, col_name, title=None, xlabel=None)\`: Muestra un boxplot para la columna específica del DataFrame.
- bar_plot(df, col_name, title=None, xlabel=None, ylabel='Count')\`: Muestra un gráfico de barras para la columna específica del DataFrame.
- Modelos de Aprendizaje Automático:
  - Regresión Lineal
  - Regresión Logística
  - Random Forest
  - Árboles de Decisión
  - Máquinas de Soporte Vectorial (SVM)
  - Redes Neuronales
  - Gradient Boosting Machines
  - K-Nearest Neighbors

## Contribuir

Si deseas contribuir a este proyecto, puedes abrir un issue o enviar una solicitud de extracción (pull request) con tus sugerencias o mejoras.
