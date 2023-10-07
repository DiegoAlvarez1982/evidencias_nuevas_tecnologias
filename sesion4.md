<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4
Calculadora Básica: Crea una función llamada calculadora que tome tres argumentos: dos números y un operador (+, -, *, /). La función debe realizar la operación indicada en los dos números y devolver el resultado.
Ejemplo de uso:

resultado = calculadora(5, 3, '+')  # Debe devolver 8

Conteo de Vocales: Crea una función llamada contar_vocales que tome una cadena como argumento y devuelva el número de vocales (a, e, i, o, u) que contiene la cadena.
Ejemplo de uso:

num_vocales = contar_vocales("Hola, mundo!")  # Debe devolver 4

Primo o No Primo: Escribe una función llamada es_primo que tome un número entero positivo como argumento y determine si es un número primo (es decir, solo es divisible por 1 y por sí mismo). La función debe devolver True si es primo y False si no lo es.
Ejemplo de uso:

resultado = es_primo(17)  # Debe devolver True

Contador de Palabras: Escribe una función llamada contar_palabras que tome una cadena como argumento y devuelva el número de palabras en esa cadena. Supón que las palabras están separadas por espacios.
Ejemplo de uso:

num_palabras = contar_palabras("Hola, este es un ejemplo.")  # Debe devolver 5

Cálculo de Potencia: Escribe una función llamada potencia que tome dos números enteros como argumentos, uno como base y otro como exponente, y devuelva el resultado de elevar la base al exponente.
Ejemplo de uso:

resultado = potencia(2, 3)  # Debe devolver 8 (2^3 = 2 * 2 * 2)

1def calculadora(n1,n2,op):
    resultado=0
    if op=='+':
        resultado = n1 + n2
    elif op=='-':
        resultado = n1 - n2
    elif op=='*':
        resultado = n1 * n2
    elif op=='/':
        resultado = n1 / n2 
        
    return resultado 

n1=int(input("ingresse un numero"))                  
n2=int(input("ingresse un segundo numero"))                  
op=input("ingresse un operador")                 
x=calculadora(n1,n2,op)  
print(x)

2 def contar_vocales(cadena):
    contador = 0
    cadena = cadena.lower()
    for letra in cadena:
        if letra in "aeiou":
            contador += 1
    
    return contador

cadena = "diego"
resultado = contar_vocales(cadena)
print(f"El número de vocales en la cadena es: {resultado}")


3def es_primo(numero):
    if numero <= 1:
        return False
    
    for i in range(2, int(numero**0.5) + 1):
        if numero % i == 0:
            return False
    
    return True

numero = 12  
resultado = es_primo(numero)

if resultado:
    print(f"{numero} True.")
else:
    print(f"{numero} False.")


4 def contar_palabras(cadena):
    palabras = cadena.split()
    numero_de_palabras = len(palabras)
    return numero_de_palabras

cadena = "Esto es una cadena de ejemplo"
resultado = contar_palabras(cadena)
print(resultado)


<!-- Su documentación aquí -->






