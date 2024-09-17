# Predicción de precios de portátiles

Este proyecto utiliza un modelo de Random Forest para predecir el precio de portátiles en base a sus características. El modelo se entrena con un conjunto de datos de precios de portátiles y luego se utiliza para predecir el precio de nuevos portátiles.

## Características

* Codificación one-hot para variables categóricas.
* División de datos en conjuntos de entrenamiento y prueba.
* Modelo de Random Forest con ajuste de hiperparámetros.
* Función para predecir el precio de un portátil dado su número de dato.

## Requerimientos

* Python 3.x
* pandas
* numpy
* scikit-learn

## Instalación

1. Clona este repositorio.
2. Crea un entorno virtual e instala las bibliotecas requeridas:
``pip install requirements.txt``
<br></br>
5. ## Uso

1. Carga el archivo `laptop_prices.csv` en tu entorno.
2. Ejecuta el código del notebook para entrenar el modelo de Random Forest.
3. Utiliza la función `predecir_precio()` para obtener predicciones de precios.

## Datos

El conjunto de datos utilizado en este proyecto contiene información sobre diferentes portátiles, incluyendo marca, modelo, tipo, sistema operativo, pantalla, procesador, memoria, almacenamiento, tarjeta gráfica y precio.

## Evaluación

El modelo se evalúa utilizando el error cuadrático medio (RMSE) y la puntuación R².

## Contribuciones

Las contribuciones son bienvenidas. Por favor, crea un pull request con tus cambios.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT.
