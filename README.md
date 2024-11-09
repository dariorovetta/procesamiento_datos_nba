# Limpieza y Análisis de Datos de la NBA

Este repositorio contiene un Jupyter Notebook diseñado para realizar tareas de limpieza y análisis en un conjunto de datos de la NBA, el cual incluye estadísticas de los jugadores. El objetivo es preparar y explorar los datos para su posterior análisis o visualización. A continuación, se ofrece una descripción general del contenido y el propósito del código.

## Contenido

### 1. Importación de Librerías y Carga de Datos

El notebook comienza importando librerías esenciales como `pandas` y `os`. Los datos son cargados desde un archivo CSV (`nba_data_final.csv`) ubicado en la ruta de trabajo actual.

### 2. Exploración de Datos

* Se muestra una vista previa de las primeras filas del conjunto de datos.
* Se imprime el tamaño del DataFrame, que contiene **2672 filas** y  **17 columnas** .
* Se verifica la estructura del DataFrame, incluyendo los tipos de datos y los valores nulos presentes en cada columna.

### 3. Columnas Principales

El conjunto de datos incluye columnas con estadísticas como:

* `name`: Nombre del jugador.
* `games_played`, `minutes_played`: Juegos y minutos jugados.
* `points_scored`, `goals_scored`, `goals_attempted`: Puntos y tiros.
* Estadísticas de rebotes, asistencias, bloqueos y robos.

### 4. Objetivo

El notebook busca preparar el conjunto de datos para posteriores análisis mediante la verificación de tipos, tratamiento de valores nulos y posibles transformaciones necesarias para trabajar con estadísticas de la NBA.
