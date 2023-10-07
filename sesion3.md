<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 
Genera un nuevo cuaderno en Google Colab y añade cuatro bloques de código, asignándoles títulos respectivos: "Listas", "Tuplas", "Conjuntos" y "Diccionarios". A continuación, comparte el cuaderno empleando la configuración de "Acceso general - Cualquier persona con el enlace - Editor". A continuación, resuelve los ejercicios que se presentan a continuación:

Listas
Crea una lista que contenga los números del 1 al 10.
Imprime la lista en el orden en que fue creada.
Ordena la lista en orden ascendente.
Ordena la lista en orden descendente.
Encuentra el número más pequeño en la lista.
Encuentra el número más grande en la lista.
Cuenta el número de veces que aparece el número 5 en la lista.
Elimina el número 5 de la lista.
Agrega el número 11 a la lista.
Imprime la lista nuevamente.
Tuplas
Crea una tupla que contenga las palabras "Hola", "mundo" y "Python".
Imprime la tupla en el orden en que fue creada.
Ordena la tupla en orden alfabético.
Encuentra la primera palabra en la tupla.
Encuentra la última palabra en la tupla.
Cuenta el número de palabras en la tupla.
Elimina la palabra "mundo" de la tupla.
Agrega la palabra "Hola" a la tupla.
Imprime la tupla nuevamente.
Conjuntos
Crea un conjunto que contenga los números del 1 al 10.
Imprime el conjunto.
Agrega el número 11 al conjunto.
Elimina el número 5 del conjunto.
Cuenta el número de elementos en el conjunto.
Comprueba si el número 5 está en el conjunto.
Comprueba si el número 11 está en el conjunto.
Crea un conjunto que contenga las palabras "Hola", "mundo" y "Python".
Imprime el conjunto.
Comprueba si la palabra "Hola" está en el conjunto.
Comprueba si la palabra "mundo" está en el conjunto.
Diccionarios
Crea un diccionario que asigne los nombres de los días de la semana a sus números correspondientes.
Imprime el diccionario.
Obtén el número del día de la semana "Lunes".
Obtén el día de la semana del número 2.
Elimina el día de la semana "Lunes" del diccionario.
Imprime el diccionario nuevamente.

Listas


numeros=[1,2,3,4,5,6,7,8,9,10]
print(numeros)

numeros.sort()
print(numeros)

numeros.reverse()
print(numeros)


print(min(numeros))

print(max(numeros))

print(numeros.count(5))

numeros.pop(5)
print(numeros)

numeros.sort()
print(numeros)

TUPLAS


palabras = ("HOLA","mundo","python")

print(palabras)


print(sorted(palabras))

Este punto no es posible las tuplas no tiene ese metodo.

Este punto no es posible las tuplas no tiene ese metodo.

Este punto no es posible las tuplas no tiene ese metodo.

Este punto no es posible las tuplas no tiene ese metodo.

Este punto no es posible las tuplas no tiene ese metodo.

palabras = ("HOLA","mundo","python")
print(palabras)

CONJUNTOS

 numeros={1,2,3,4,5,6,7,8,9,1}
 print(numeros)

print(numeros)

numeros.add(11)

print(numeros)

los conjuntos no son indexada.

print(5 in numeros)

print(11 in numeros)

palabras={"Hola","mundo","Python"}

print(palabras)

print("Hola" in palabras)

print("mundo" in palabras)

**DICCIONARIOS**

semana={
    'lunes':1,
    'martes':2,
    'miercoles':3,
    'jueves':4,
    'viernes':5,
    'sabado':6,
    'domingo':7
}

print(semana)

print(semana['lunes'])


print(semana.keys(2))


print(semana.pop(1))

<!-- Su documentación aquí -->






