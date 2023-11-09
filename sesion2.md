<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2
```python
Actividad: Repositorio local de ejercicios de estructuras de control iterativas. (Trabajo individual)
Crea un repositorio local y resuelve los siguientes ejercicios para practicar bucles while y for:

Ejercicios con bucle while:

Solicita al usuario que ingrese una lista de números y encuentra el número mayor y el menor.
Solicita al usuario un número e imprime la suma de los números pares entre 1 y ese número.
Solicita al usuario una cadena e imprime cuántas vocales contiene.
Solicita al usuario un número y muestra su tabla de potencias desde 1 hasta 10.
Solicita al usuario una lista de números y calcula la media aritmética.


Ejercicios con bucle for:

Solicita al usuario una lista de números y calcula la suma de sus elementos.
Solicita al usuario una lista de números e imprime cuántos de ellos son pares.
Solicita al usuario un número y muestra su tabla de multiplicar usando range().
Solicita al usuario un número e imprime los números pares desde 2 hasta ese número.
Solicita al usuario un número y muestra la secuencia de números pares desde 2 hasta ese número.

ejercicio1
numeros = input("Ingresa una lista de números separados por espacios: ")
lista_numeros = [float(numero) for numero in numeros.split()]

numero_mayor = max(lista_numeros)
numero_menor = min(lista_numeros)

print("El número mayor es:", numero_mayor)
print("El número menor es:", numero_menor)




ejercicio 2
limite_superior = int(input("Ingresa un número: "))
numero_actual = 1
suma_pares = 0

while numero_actual <= limite_superior:
    if numero_actual % 2 == 0:
        suma_pares += numero_actual
    numero_actual += 1
print("La suma de los números pares hasta", limite_superior, "es:", suma_pares)




ejercicio 3
cadena = input("Ingresa una cadena: ")

indice = 0
contador_vocales = 0

cadena = cadena.lower()

while indice < len(cadena):
    if cadena[indice] in "aeiou":
        contador_vocales += 1
    indice += 1

print("La cadena tiene", contador_vocales, "vocales.")




ejercicio 4
numero = int(input("Ingresa un número: "))

exponente = 1

while exponente <= 10:
    resultado = numero ** exponente
    print(f"{numero} elevado a la {exponente} es igual a {resultado}")
    exponente += 1



ejercicio 5
entrada_usuario = input("Ingresa una lista de números separados por espacios: ")

numeros = [float(numero) for numero in entrada_usuario.split()]

suma_numeros = 0
cantidad_numeros = 0

indice = 0
while indice < len(numeros):
    suma_numeros += numeros[indice]
    cantidad_numeros += 1
    indice += 1

if cantidad_numeros > 0:
    media_aritmetica = suma_numeros / cantidad_numeros
    print("La media aritmética de los números ingresados es:", media_aritmetica)
else:
    print("No has ingresado ningún número.")


Ejercicios con bucle for:

ejercicio 1

entrada_usuario = input("Ingresa una lista de números separados por espacios: ")

numeros = [float(numero) for numero in entrada_usuario.split()]

suma_numeros = 0

for numero in numeros:
    suma_numeros += numero

print("La suma de los números ingresados es:", suma_numeros)


ejercicio 2

entrada_usuario = input("Ingresa una lista de números separados por espacios: ")

numeros = [int(numero) for numero in entrada_usuario.split()]

contador_pares = 0

for numero in numeros:
    if numero % 2 == 0:
        contador_pares += 1

print("La cantidad de números pares en la lista es:", contador_pares)


ejercicio 3

numero = int(input("Ingresa un número para ver su tabla de multiplicar: "))

print(f"Tabla de multiplicar del {numero}:")
for i in range(1, 11):
    resultado = numero * i
    print(f"{numero} x {i} = {resultado}")

ejercicio 4

limite_superior = int(input("Ingresa un número: "))

print(f"Números pares hasta {limite_superior}:")
for numero in range(2, limite_superior + 1, 2):
    print(numero)


ejercicio 5

limite_superior = int(input("Ingresa un número: "))

print(f"Secuencia de números pares hasta {limite_superior}:")
for numero in range(2, limite_superior + 1, 2):
    print(numero)

```

<!-- Su documentación aquí -->






