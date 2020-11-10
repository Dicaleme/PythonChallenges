# PythonChallenges

This repo will guide you through some exercises how to develop basic Python skills.

#Escribe el código para leer dos números enteros(x, y) de dos dígitos y determina a cuánto es igual la suma de todos los dígitos. Imprime el resultado.

def reto4(x,y):
    if(num == 0):
        return num
    else:
        return (num * (num + 1) / 2)
    
number = int(input("Please Enter any Number: "))

total_value = reto4(number)

print("Sum of Natural Numbers from 1 to {0} =  {1}".format(number, total_value))
  reto4(3,4) 

#Escribe el código para leer un número entero x e imprime el número de dígitos de x. Por ejemplo, 345 tiene 3 dígitos y 4000 tiene 4 dígitos.

def reto2(x):
 


reto2(1234)

a = int(input("ingrese numero: "))
c4 = a % 10 
c3 = int((a % 100) / 10)
c2 = int((a % 1000) / 100)
c1 = int((a - (a % 1000)) / 1000)

print (str(c4)+str(c3)+str(c2)+str(c1))
