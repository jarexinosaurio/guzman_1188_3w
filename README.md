# guzman_1188_3w
#examen de guzman guzman jared uziel 3w

#aqui asignamos los valores corresspondientes 
g = ("guzman")#le asignamos un valor a la variable g
j = ("jared")#le asignamos un valor a la variable j
u = ("uziel")#le asignamos un valor a la variable u
print(" ")#espacio
print("cuales son tus apeidos?")#pregunta introductiva a la variable g
print(g,g)#imprime la variable g 
print(" ")#espacio
print("y tus nombres?")#pregunta introductiva a las variables j,u
print(j,u)#imprime las variables j,u
print("")#espacio
print("entonses tu nombre completo es:")
print(g,g,j,u)#imprime la variable 
print (g.upper(),g.upper(),j.upper(),u.upper())

![image](https://github.com/user-attachments/assets/f15ddff5-0c84-47b7-855f-ad276c6da4e9)
![image](https://github.com/user-attachments/assets/a6b28b6d-1750-4519-b3b3-b8c6ea4d7458)
![image](https://github.com/user-attachments/assets/b40adaf7-3b7a-4102-a79e-37f6ded8674f)

#practica 2

#practica echa por guzman guzman
# capturar los tres valores solicitados
A = float(input("Ingresa el valor A: "))
B = float(input("Ingresa el valor B: "))
C = float(input("Ingresa el valor C: "))

# Verificar si los valores son distintos
if A == B or A == C or B == C:
    print("ojo: Los valores introducidos no se deben repetir.")#ojo alerata de numero repetido
else:
    # verificar cual es el mayor y el menor
    mayor = max(A, B, C)#mayor
    menor = min(A, B, C)#menor

    # Imprimir el resultado
    print(f"El valor mayor es: {mayor}")# Imprimir el resultado
    print(f"El valor menor es: {menor}")# Imprimir el resultado


![image](https://github.com/user-attachments/assets/8c1c8f1c-69db-41ac-aac8-5edb850f5702)
![image](https://github.com/user-attachments/assets/fba98407-5037-44c8-b14f-d63882fafbac)
![image](https://github.com/user-attachments/assets/f205d2f9-a803-4f78-86f2-5f959ff4c7f2)


#practica3


#programaa de guzman guzman
# Función para determinar el menor de dos números
def encontrar_menor(num1, num2):
    if num1 < num2:
        return num1
    else:
        return num2

# Solicitar dos valores al usuario
valor1 = float(input("Ingresa el primer número: "))
valor2 = float(input("Ingresa el segundo número: "))

# Determinar y mostrar el menor de los dos valores
menor = encontrar_menor(valor1, valor2)
print(f"El menor de los dos valores es: {menor}")

# Solicitar dos números para sumar
numero1 = float(input("Ingresa el primer número para sumar: "))
numero2 = float(input("Ingresa el segundo número para sumar: "))

# Sumar los dos números
suma = numero1 + numero2

# Mostrar el resultado de la suma
print(f"La suma de {numero1} y {numero2} es: {suma}")


![image](https://github.com/user-attachments/assets/09b7d72c-80b9-40f9-87ea-617a15b27c6c)
![image](https://github.com/user-attachments/assets/eaa60df9-7070-4ee1-af51-d6ec98223203)
![image](https://github.com/user-attachments/assets/cea20794-3b9f-406c-947d-969090df6300)
![image](https://github.com/user-attachments/assets/6160b619-d620-4f51-9cd0-0d6147c5ed47)

#practica 4

#progama de guzman guzman
# Solicitar la base y la altura del rectángulo al usuario
base = float(input("Ingresa la base del rectángulo: "))#solicita ingresar el valor de la base
altura = float(input("Ingresa la altura del rectángulo: "))#solicita ingresar el valor de la altura

# Calcular el área y el perímetro
area = base * altura
perimetro = 2 * (base + altura)

# Muestra el re
print(f"El área del rectángulo es: {area}")#imprime el resultado del area
print(f"El perímetro del rectángulo es: {perimetro}")#imprime el resultado del perimetro

![image](https://github.com/user-attachments/assets/604b32c1-02dd-4c7f-a2bb-ea8baef0c4d3)
![image](https://github.com/user-attachments/assets/d13f3bd3-ae3e-4c59-a81f-ca5f6dbbd2d3)

#practica 5

#favor de ingresar un numero
#practica de menor a la primera docena 1-12
numero=int(input("ingrese un numero:"))#instruccion if,else para determinar
#proseso if else pqara verificar que es correcto
if numero == 12:#numero limite #if
    print("el numero es igual a cero")
elif numero < 12:
    print("esta bien ")#si el numero es menor a 12 esta bien

else:#else
    print("pasa el limite establecido")#sale si el numero indicado es mayor a 12

    ![image](https://github.com/user-attachments/assets/3bbf828e-e0a2-4006-8c30-1d4965848d26)
    ![image](https://github.com/user-attachments/assets/109b4a21-a09f-456a-9993-3ba9940bbe76)


practica 6

#guzman guzman jared uziel 3w
#programa de par e impar
#solicitar al usuario que ingrese un numero
numero=int(input("ingrese un numero:"))

#verificar si el numero es 0
if numero == 0:
    print("el mumero es cero.")
#verficar si el numero es par
elif numero % 2 == 0:
    print("el numero es par")
#si este numero es par,sera impar
else:
    print("el numero es impar")

![image](https://github.com/user-attachments/assets/2842a5d0-db64-4f50-80bf-58c202ad1be2)
![image](https://github.com/user-attachments/assets/31ee63b8-3995-40d4-8e07-7b1a3aa4203a)


practica 7

#practica guzman guzman
# Solicitar un número entero al usuario
numero = int(input("Ingresar un número entero porfavor: "))

# Verificar si el número es divisible por 7 y mayor a 40
#proceso if else
if numero > 40 and numero % 7 == 0:
    print(f"este número {numero} es divisible por 7 y es mayor a 40.")
else:
    print(f"este número {numero} no cumple con las condiciones.")

![image](https://github.com/user-attachments/assets/f520dffd-270d-4376-a02e-079fd6771a97)
![image](https://github.com/user-attachments/assets/fbc6b227-fd9a-4e42-9ab0-a5b0a549681d)

practica 8

#practica de guzman guzman
# Función para calcular el factorial de un número
def factorial(n):
    if n < 0:
        return None  # El factorial no está definido para números negativos
    elif n == 0 or n == 1:
        return 1  # 0! y 1! son 1
    else:
        resultado = 1
        for i in range(2, n + 1):
            resultado *= i
        return resultado

# Solicitar un número entero al usuario
numero = int(input("Ingresa un número entero: "))

# Calcular el factorial
resultado_factorial = factorial(numero)

# Mostrar el resultado
if resultado_factorial is not None:
    print(f"El factorial de {numero} es: {resultado_factorial}")
else:
    print("El factorial no está definido para números negativos.")

![image](https://github.com/user-attachments/assets/96d48506-9279-4bf6-96ab-3a0f8cb36226)
![image](https://github.com/user-attachments/assets/078f0580-341f-4e6c-b627-a5ea860a8de0)
![image](https://github.com/user-attachments/assets/4a29f038-aabf-49db-815e-778524ecfebc)


