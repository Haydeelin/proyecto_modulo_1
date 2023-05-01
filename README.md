# Proyecto_ mòdulo_1
## Calculadora IMC

#Solicitar al usuario nombre

#Solicitar al usuario apellido 1

#Solicitar al usuario apellido 2

#Solicitar al usuario edad

#Solicitar al usuario peso

#Solicitar al usuario estatura



#El programa no puede permitir que ningùn dato quede vacìo

1.- nombre = input ("Introduza su nombre: ")

if nombre == "": 

    print ("El nombre no puede estar vacìo")
    any.exit(-1)
    
2.- apellido_1 = input ("Introduzca su apellido paterno: ")

if apellido_1 == "":

    print ("El apellido paterno no puede estar vacìo")
    any.exit(-1)
    
3.- apellido_2 = input ("introduzca su apellido materno: ")

if apellido_2 == "":

    print("El apellido materno no puede estar vacìo")
    any.exit(-1)

#Los campos de edad, peso y estatura deberàn ser cifras

4.- edad= input ("Introduce tu edad: ")

edad= int (edad)

if edad == "":

    print ("La edad no puede quedar vacìo")
    any.exit(-1)

5.- peso= input ("Introduce tu peso: ")

peso= float (peso)

if peso == "": 

    print ("El peso no puede estar vacìo")
    any.exit(-1)

6.- estatura= input ("Introduce tu estatura: ")

estatura= float (estatura)

if estatura == "":

    print ("La estatura no puede estar vacìo")
    any.exit(-1)

#Imprimo nombre

#Imprimo apellido 1

#Imprimo apellido 2

#Imprimo edad

#Imprimo peso

#Imprimo estatura

#Imprimo IMC= peso / estatura * estatura

x= peso

y= estatura

print( "Tu IMC es igual a: ")

print  (x/(y * y)) 





