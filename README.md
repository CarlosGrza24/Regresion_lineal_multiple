# Regresión Lineal Múltiple

Este proyecto tiene como objetivo aplicar un modelo de regresión lineal múltiple. En este trabajo utilizaremos una base de datos de la NASA, con la que trabajaron para tratar de determinar perfiles aerodinámicos 
ideales ante distintas condiciones, como: la velocidad delviento y ángulo de ataque del mismo.

Utilizaremos el archivo de nombre [“NASA”](NASA.csv), donde podresmos encontrar información para 1,053 observaciones distintas, con 6 mediciones para cada una de ellas. Los datos se descargaron del [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/291/airfoil+self+noise)
, y originalmente se publicaron en el [NASA Reference Publication 1218](https://ntrs.nasa.gov/api/citations/19890016302/downloads/19890016302.pdf).

## Datos utilizados
En el archivo antes mencionado se cuenta con los siguientes datos:

- **Frecuencia**: Frecuencia (Hz)  
- **Ángulo**: Ángulo de ataque (°)  
- **Longitud**: Longitud de cuerda geométrica (m)  
- **Velocidad**: Velocidad de flujo libre (m/s)  
- **Espesor**: Espesor del desplazamiento en el lado de succión (m)  
- **PresiÓn**: Nivel escalado de presión sonora (dB, variable objetivo)

## Pasos del análisis

### 1. Carga y exploración  
- Importar el archivo NASA.csv, revisar dimensiones, variables e imprimir primeras filas.  

### 2. División de datos  
- Separar 70% train / 30% test, confirmar tamaños.  

### 3. Entrenamiento  
- Ajustar regresión múltiple con 5 variables para predecir (presion).  

### 4. Significancia  
- Revisar p-values para identificar las variables significativas.
- Identificar la variable con mayor significancia.  

### 5. Evaluación  
- RSE y R² en train y en test para ver el desempeño de nuestro modelo. 

### 6. Visualización  
- Gráfica dispersión Y real vs Ŷ con una de línea 45°.  
- Observación de conclusiones a partir de la gráfica.

## Archivos del proyecto
- [Reporte en ipynb](A1.3_648241.ipynb)
- [Reporte en html](A1.3_648241.html)
- [NASA](NASA.csv)
