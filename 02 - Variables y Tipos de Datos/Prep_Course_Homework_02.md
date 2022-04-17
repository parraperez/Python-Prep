## Variables

1) Crear una variable que contenga un elemento del conjunto de números enteros y luego imprimir por pantalla

Numero = 20
print (Numero)

2) Imprimir el tipo de dato de la constante 8.5
type (8.5)

3) Imprimir el tipo de dato de la variable creada en el punto 1
type (Numero)

4) Crear una variable que contenga tu nombre
nombre = "Jorge Enrique Parra Perez"

5) Crear una variable que contenga un número complejo
complejo = 10 + 2j


6) Mostrar el tipo de dato de la variable crada en el punto 5
type (complejo)

7) Crear una variable que contenga el valor del número Pi redondeado a 4 decimales

PI = 3.1416


8) Crear una variable que contenga el valor 'True' y otra que contenga el valor True. ¿Se trata de lo mismo?

primero = "True"
segundo = True

9) Imprimir el tipo de dato correspondientes a las variables creadas en el punto 9

type (Primero)
type (Segundo)

10) Asignar a una variable, la suma de un número entero y otro decimal

Suma = 5 + 5.5
print (Suma)

11) Realizar una operación de suma de números complejos

sumauno= 4 + 5j 
sumados= 3 + 4j
print (sumaunos + sumados)

12) Realizar una operación de suma de un número real y otro complejo
real = 7
imaginario = 8 + 9j
sumatres = real + imaaginario
print (sumatres)

13) Realizar una operación de multiplicación
a = 4
b = 5
multip = a * b
print (multip) 

14) Mostrar el resultado de elevar 2 a la octava potencia
potencia = 2 ** 8
print (potencia)

15) Obtener el cociente de la división de 27 entre 4 en una variable y luego mostrarla
cociente = 27 / 4 
print (cociente)

16) De la división anterior solamente mostrar la parte entera
cocienteen = 27 // 4
print (cocienteen)

17) De la división de 27 entre 4 mostrar solamente el resto
cocienteres = 27 % 4
print (cocienteres)


18) Utilizando como operandos el número 4 y los resultados obtenidos en los puntos 16 y 17. Obtener 27 como resultado

operacion = 4 * cocienteen + cocienteres 


19) Utilizar el operador "+" en una operación donde intervengan solo variables alfanuméricas

print ("hola " + "2154" )

20) Evaluar si "2" es igual a 2. ¿Por qué ocurre eso?

"2"== 2


21) Utilizar las funciones de cambio de tipo de dato, para que la validación del punto 20 resulte verdadera

int ("2") == 2


22) ¿Por qué arroja error el siguiente cambio de tipo de datos? a = float('3,8')
coma en lugar de punto
a = float('3.8')

23) Crear una variable con el valor 3, y utilizar el operador '-=' para modificar su contenido
c = 3
c -= 8
print (c)


24) Realizar la operacion 1 << 2 ¿Por qué da ese resultado? ¿Qué es el sistema de numeración binario?
1 << 2

25) Realizar la operación 2 + '2' ¿Por qué no está permitido? ¿Si los dos operandos serían del mismo tipo, siempre arrojaría el mismo resultado?
2 + "2"
porque son es un string y un entero en suma

26) Realizar una operación válida entre valores de tipo entero y string

d = "Hola"
e = 4

print (d * 4)