# Proyecto 3 telemática

Aplicación de un sistema de analítica sobre datasets de covid-19 a nivel mundial y a nivel nacional, para comaraciones de estadísticas entre los datasets, compuesto principalmente por el archivo:

[Visualización](Visualización.ipynb) 

donde se realizó los siguientes procedimientos:

### Iniciación del entorno e importe de librerías

para está parte se preparó el uso de pyspark para la lectura y tratamiento de datos y se importaron las librerías necesarias para la ejecución de la parte gráfica

### Lectura de los datos

La lectura de los datasets en formato csv se realizó desde spark, con archivos en Google Drive

### Exploración de datos

En esta parte se exploraron los principales datasets a analizar, donde se visualizó:

- las columnas de los datasets
- la cantidad de registros de los datasets
- el esquema de los dataframes

### Analítica

Se realizaron porcesos para comparar los valores de casos confirmados a nivel mundial y a nivel nacional

### Visualización

Se generaron gráficas para revisar la situación a nivel mundial, la situación a nivel nacional y la comparación gráfica de ambos

## Ejecución

La ejecución del script se realizó en notebook de Google Colab:

https://colab.research.google.com/drive/1XlaMWZIsYkKIwrQPwlilXCxkp8knKUdI?usp=sharing


Obteniendo los siguientes resultados:


- Gráfica confirmados a nivel mundial vs Tiempo

![Mundial](https://github.com/eafit-201710143010/proyecto-3-Telem-tica/blob/master/descarga.png)


- Gráfica confirmados en Colombia vs Tiempo


![Mundial](https://github.com/eafit-201710143010/proyecto-3-Telem-tica/blob/master/descarga%20(1).png)


- Gráfica de comparación casos mundiales y colombianos


![Mundial](https://github.com/eafit-201710143010/proyecto-3-Telem-tica/blob/master/descarga%20(2).png)


