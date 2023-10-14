<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 
[Actividad 11](https://colab.research.google.com/drive/1QYXe4k4EZHkqviBhMM4d6yIMD9D4nyy9?usp=sharing)
<!-- Su documentación aquí -->
```python	
Actividad: Filtros en pandas (loc-iloc)
import pandas as pd
import numpy as np

# Crear datos de ejemplo
marcas = ['Toyota', 'Honda', 'Ford', 'Chevrolet', 'Nissan', 'BMW', 'Mercedes-Benz', 'Audi', 'Volkswagen', 'Hyundai']
modelos = ['Camry', 'Civic', 'F-150', 'Silverado', 'Altima', 'X5', 'C-Class', 'A4', 'Jetta', 'Elantra']
anios = [2018, 2020, 2019, 2017, 2016, 2021, 2018, 2020, 2019, 2017]
precios = np.random.randint(15000, 50000, 10)

# Crear DataFrame con los datos
df_autos = pd.DataFrame({'marca': marcas, 'modelo': modelos, 'anio': anios, 'precio': precios})

# Mostrar el DataFrame
print(df_autos)


1. Ejercicios loc
Utilizando el DataFrame de autos con 20 filas y 4 columnas, realiza las siguientes consultas utilizando el método loc de Pandas:

Seleccionar todas las filas de la columna "marca".
Seleccionar las filas de los autos cuyo precio es mayor a $40,000.
Seleccionar las filas de los autos que son de la marca "BMW".
Seleccionar las filas de los autos que son de la marca "Toyota" y tienen un precio menor a $20,000.
Seleccionar las filas de los autos que son del año 2019.
Seleccionar las filas de los autos que son del año 2016 o anteriores.
Seleccionar las filas de los autos que son de la marca "Honda" y el modelo es "Civic".
Seleccionar las filas de los autos que tienen un precio entre $25,000 y $30,000.
Seleccionar las filas de los autos que tienen un precio mayor a $30,000 y el modelo es "C-Class".
Seleccionar las filas de los autos que son de la marca "Volkswagen" y el modelo no es "Jetta".
2. Ejercicios iloc
Utilizando el DataFrame de autos con 20 filas y 4 columnas, realiza las siguientes consultas utilizando el método iloc de Pandas:

Seleccionar las filas de los autos de los primeros 5 fabricantes en el DataFrame.
Seleccionar las filas de los autos de los últimos 5 fabricantes en el DataFrame.
Seleccionar la primera columna de todas las filas del DataFrame.
Seleccionar las celdas de la primera fila y primera columna del DataFrame.
Seleccionar las filas pares del DataFrame.
Seleccionar las filas impares del DataFrame que tienen un precio mayor a $25,000.
Seleccionar las filas de los autos que son de la marca "Ford" y el modelo es "F-150".
Seleccionar las filas de los autos que son del año 2018 y tienen un precio mayor a $20,000.
Seleccionar las filas de los autos que tienen un precio mayor a $30,000 y la marca es "Toyota".
Seleccionar las filas de los autos que son de la marca "Honda" y el modelo no es "Civic".

```





