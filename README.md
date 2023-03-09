# Reto_5
### Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
´´´
x= int (input("inserte un numero:"))
if x>=97 and x<=122: 
    print ("el numero presentado pertenece a una letra o vocal minuscula en el codigo ASCII")
elif x< 97 and x>122:
    print ("el numero presentado no pertenece a una letra o vocal minuscula del codigo ASCII")
´´´
    
### Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
´´´
a = input("Ingrese una longitud por favor: ")
y = ord(a[0])

if y % 2 == 0:
    print("El código ASCII de la primera letra es par.")
else:
    print("El código ASCII de la primera letra es impar.")
´´´
### Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
´´´
x=input("Escriba en el siguiente espacio por favor:")
if x>= '0' and x<='9':
    print("es un digito")
else:
    print ("no es un digito")
´´´
### Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:
Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma"
´´´
x= float (input("escriba un numero por favor:"))
if x>0:
    print ("El número x es positivo")
elif x==0:
    print ("El número x es el neutro para la suma")
elif x<0:
    print("El número x es negativo")
´´´
### Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.

´´´
x=float
y=float
r=float
r=float(input("Escriba el radio deseado: "))
x=float(input("Escriba el punto x: "))
y=float(input("Escriba el punto y: "))
if (x*x + y*y <= r**2):
  print("El punto marcado esta dentro del area del circulo ")
else:
  print("El punto marcado esta fuera del area del circulo")  
  
´´´
### Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.

´´´
a: float
b: float
c: float
a= float(input("Escriba la medida del lado 1:"))
b= float(input("Escriba la medida del lado 2:"))
c= float(input("Escriba la medida del lado 3:"))
if a+b>c and a+c>c and b+c>a and a==b==c:
    print("se puede hacer el triangulo")
else:
    print("no se puede hace el triangulo")
´´´

#Fin




