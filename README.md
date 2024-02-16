# SFA_PY_A02.py
SFA_PY_ACT2_A02
1.programa de phyton que lea dos numeros enteros, usar una condicion y analizar cual de los dos numeros es el mayor
num1= int(input("ingresar primer numero: "))
num2= int(input("ingresar segundo numero: "))
if num1 == num2:
print("los numeros son iguales")
else:
if num1 > num2:
print("el numero mayor es:",num1)
else:
print("el numero mayor es:",num2)
ingresar primer numero: 3
ingresar segundo numero: 5
el numero mayor es: 5
SFA_PY_ACT2_A02

2.Programa de phyton algoritmo que lea 4 calificaciones de un alumno, calcular y desplegar su promedio acompañado de la leyenda
"APROBADO" o "REPROBADO"
cali1=int(input("Ingresar primera calificacion:"))
cali2=int(input("Ingresar segunda calificacion:"))
cali3=int(input("Ingresar tercera calificacion:"))
cali4=int(input("Ingresar cuarta calificacion:"))
pro= (cali1+cali2+cali3+cali4)/4
if pro >100:
print("calificacion no valida")
else:
if pro>=60:
print("HAS APROBADO TU CALIFICACION ES:",pro)
else:
print("HAS REPROBADO TU CALIFICACION ES:",pro)
Ingresar primera calificacion:30
Ingresar segunda calificacion:60
Ingresar tercera calificacion:70
Ingresar cuarta calificacion:50
HAS REPROBADO TU CALIFICACION ES: 52.5
SFA_PY_ACT2_A02

3.Programa de phyton algoritmo que a traves de opciones (1.-HOMBRE 2.-MUJER) preguntar al usuario cual es su sexo y desplegar la leyenda
"HOMBRE" o "MUJER"
print("ingrese el numero que corresponde a tu sexo: \n1. HOMBRE \n2. MUJER")
sexo= int(input(""))
if sexo== 1:
print("HOMBRE")
else:
if sexo== 2:
print ("MUJER")
else:
print ("ESTA OPCION NO ES VALIDA")
ingrese el numero que corresponde a tu sexo:
1. HOMBRE
2. MUJER
1
HOMBRE


SFA_PY_ACT2_A02
4.Programa en phyton que lea un numero entero, y desplegar si el numero "PAR" o "IMPAR"
int(input("ingrese un numero"))
r= num%
2
if
r==0:
print("EL NUMERO",num,"ES NUMERO PAR")
else:
print("EL NUMERO",num,"ES NUMERO IMPAR")

ingrese un numero3EL NUMERO 3 ES NUMERO IMPAR

SFA_PY_ACT2_A02
5.Programa de pythom que lea 2 numeros enteros, usar una condicion y analizar los 2 numeros y desplegar cual de los numeros es el mayor
num1=int(input("Ingrese el primer numero: "))
num2=int(input("Ingrese el segundo numero:"))
ifnum1==num2:
print("son iguales los numeros")
elifnum1>num2:
print("Numero",num1,
"ES EL MAYOR")
else:
print("Numero",num2,"ES EL MAYOR")
Ingrese el primer numero:5Ingrese el segundo numero:7Numero 7 ES EL MAYOR


SFA_PY_ACT2_A02
6.Programa de pythom que lea 4 califi caciones de un alumno, calcular y desplegar el promedio acompañado de la leyenda APROBADO oREPROBADO
cali1=int(input("ingrese la primera calificacion:"))
cali2=int(input("ingrese la segunda calificacion:"))
cali3=int(input("ingrese la tercera calificacion:"))
cali4=int(input("ingrese la segunda calificacion:"))
pro=(cali1+cali2+cali3+cali4)/4
ifpro>100:
print("CALIFICACION NO VALIDA")
elifpro>=60:
print("TU PROMEDIO ES:",pro,"HAS APROBADO")
else:
print("TU PROMEDIO ES:",pro,"HAS REPROBADO")
ingrese la primera calificacion:70
ingrese la segunda calificacion:80
ingrese la tercera calificacion:0
ingrese la segunda calificacion:50
TU PROMEDIO ES: 50.0 HAS REPROBADO

SFA_PY_ACT2_A02
7.Programa en python que atraves de opciones (1.-HOMBRE 2.-MUJER) preguntar al usuario cual es su sexo y desplegar la leyenda "HOMBRE"o "MUJER"
print("INGRESA EL NUMERO QUE CORRESPONDE A TU SEXO: \n5. HOMBRE \n2 MUJER")
SEXO= int(input(""))
if SEXO ==5:
print("HOMBRE")
elif SEXO==2:
print("MUJER")
else:
print("ESTA OPCION NO ES VALIDA")
INGRESA EL NUMERO QUE CORRESPONDE A TU SEXO: 5. HOMBRE 2 MUJER2
MUJER

SFA_PY_ACT2_A02
8.programa de phyton que lea un numero entero, y desplegar si el numero es "PAR" o "impar"
num= int(input("INGRESE UN NUMERO:"))
o=num%2
if o==0:
print("NUMERO",o,"ES PAR")
elif o!=0:
print("NUMERO",o,"ES IMPAR")
INGRESE UN NUMERO:8NUMERO 0 ES PAR


