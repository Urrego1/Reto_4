# Reto_4

Alejandro Urrego Valencia - 1000364014
 
1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.

```python

print("Usuario, por favor ingrese un numero entero")
number = float(input("Número entero: "))
if number == 97:
    print("El número seleccionado corresponde a una vocal minúscula en el código ASCII")
elif number == 101:
    print("El número seleccionado corresponde a una vocal minúscula en el código ASCII")
elif number == 105:
    print("El número seleccionado corresponde a una vocal minúscula en el código ASCII")
elif number == 111:
    print("El número seleccionado corresponde a una vocal minúscula en el código ASCII")
elif number == 117:
    print("El número seleccionado corresponde a una vocal minúscula en el código ASCII")
else:
    print("El número seleccionado no corresponde a alguna vocal minúscula en código ASCII")


```


2. Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

```python

cadena = (input("Por favor. Ingrese un una cadena de longitud 1: "))
codigo = ord(cadena)
if codigo % 2 == 0:
    print("El código ASCII de primera letra de la cadena es par")
else:
    print("El codigo ASCII de la primera letra de la cadena es impar")


```


3. Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

```python



numero = (input("Por favor, Ingrese un carácter: "))

if numero == "0" or numero == "1" or numero == "2" or numero == "3" or numero == "4" or numero == "5" or numero == "6" or numero == "7" or numero == "8" or numero == "9":
    print("El carácter ingresado si corresponde a un dígito")
    
else:
    print("El carácter ingresado no corresponde a un dígito")


```


4. Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

  a. Positivo: "El número x es positivo"
  
  b. Negativo: "El número x es negativo"
  
  c. Cero (0): "El número x es el neutro para la suma"

```python

numero_x = float(input("Por favor, Ingresa un número real: "))

if numero_x > 0:
    print(f"El número {numero_x} es positivo")
elif numero_x < 0:
    print(f"El número {numero_x} es negativo")
else:
    print(f"El número {numero_x} es el neutro para la suma")

```

  
  
5. Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.


```python

x_c = int(input("Ingrese la coordenada en x del centro del círculo: "))
y_c = int(input("Ingrese la coordenada en x del centro del círculo: "))
r = int(input("Ingrese un valor para el radio del circulo: "))
x = int(input("Ingrese un valor en x: "))
y = int(input("Ingrese un valor en y: "))


if r**2 == (x - x_c)**2 + (y - y_c)**2:
    print("El punto R2 si pertence al circulo")
else:
    print("El punto R2 no pertenece al circulo")

```


6. Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.


```python


a = float(input("Por favor ingrese la longitud del lado 'a': "))
b = float(input("Por favor ingrese la longitud del lado 'b': "))
c = float(input("Por favor ingrese la longitud del lado 'c': "))
if a < (c +b) and b < (c + a) and c < (b +a):
    print("Es posible crear un triangulo con esas medidas")
else:
    print("es posible crear un triangulo con esas medidas")

```
