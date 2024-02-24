Variables:

Que es una variable? es un metodo de codigo que almacena diferentes tipos de datos dependiendo del tipo de Variable. 
pero cuales son esos tipos?

INT: El tipo de variable INT se basa en almacenar Numeros Enteros, Ejemplo:
```py
X = 1
Y = 9
Resultado = X + Y
print("Resultado")
#Estas son variables Tipo INT
#Se definen los numeros enteros, se suman y luego se muestra el resultado
```
FLOAT: El tipo de variable FLOAT almacena Datos de Numeros Reales, Ejemplo:
```py
X = 0.5
Y = -1
Z = 2
Resultado = Z + Y + X
print(Resultado)
#Estas son Variables Tipo FLOAT
#Se definen los numeros reales y se suman y luego se muestra el resultado
```
STRING: El tipo de variable STRING almacena datos de Texto, Ejemplo:
```py
Nombre = Daniel
Apellido = Cuesta
print(Nombre, " ", Cuesta)
#Ejemplo de Variables Float
#Aca se guarda el texto del Nombre y Apellido y luego se imprime
```
BOOL: El tipo de Variable Bool (Booleano) almacena datos de Verdadero o Falso, Ejemplo:
```py
X = True

if X is True:
  print("Es Verdadero")
else:
  print("Es Falso")
#Ejemplo de Variable Booleana
#Se define si X es verdadero o falso
#Si es verdadero se imprimira "es verdadero", del contrario dira "es falso"
```

Tambien puedes definir una variable desde la terminal y fuera del codigo usando la funcion "input"
Existen diferentes tipos de "input" dependiendo del tipo de variable:

```py
Nombre = input("Ingrese su nombre: ")
Apellido = str(input("Ingrese su apellido: "))
Edad = int(input("Ingrese su edad: "))
Numero = float(input("Ingrese un numero Real: "))

print("Su nombre: ", Nombre)
print("Su Apellido: ", Apellido)
print("Su Edad: ", Edad)
print("Su Numero: ", Numero)
```
Al usar input o str(input) puedes ingresar texto
Al usar int(input) puedes ingresar numeros enteros
Al usar float(input) puedes ingresar numeros reales

Tambien para imprimir el valor de una variable se ingresa el siguiente codigo:
```py
X = 2
print(X)
#Aca pueden ver como se imprime el valor de la variable X
#Se puede imprimir cualquier valor al hacer print sin incluir las "" en el parametro
```
