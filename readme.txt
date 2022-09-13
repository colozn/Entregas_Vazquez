"""""""""
letra=(input("Palabra: "))

if letra [0] == letra [0].upper():
    print("Es correcto")
else:
    print("Incorrecto")

## ej

numero= int(input("ingrese un numero entero: "))
if numero == 0:
    print("positivo")
elif numero > 0:
    print("positivoo")
else:
    print("negativo")

if numero % 2 == 0:
   print("entero")
else:
    print("inpar")

## ej

hora= int(input("dime los minutos mami: "))
print("Tus minutos en horas son: ")
print((hora)/ 60)

#ej


sueldobase=int(input("Escirba su sueldo base: "))

venta1=int(input("dinero de la venta 1: "))
venta2=int(input("dinero de la venta 2: "))
venta3=int(input("dinero de la venta 3: "))
venta4=int(input("dinero de la venta 4: "))

comision= venta1 * 0.10 + venta2 * 0.10 + venta3 * 0.10 + venta4 * 0.10
print(comision + sueldobase)

#ej


respuesta=str(input("Pregunta 1: "))
respuesta2=str(input("Pregunta 2: "))
respuesta3=str(input("Pregunta 3: "))
respuesta4=str(input("Pregunta 4: "))

if respuesta == "correcto":
    print("4")
elif respuesta == "incorrecto":
    print("-1")
elif respuesta == "no responde":
    print("0")

if respuesta2 == "correcto":
    print("4")
elif respuesta2 == "incorrecto":
    print("-1")
elif respuesta2 == "no responde":
    print("0")

if respuesta3 == "correcto":
    print("4")
elif respuesta3 == "incorrecto":
    print("-1")
elif respuesta3 == "no responde":
    print("0")

if respuesta4 == "correcto":
    print("4")
elif respuesta4 == "incorrecto":
    print("-1")
elif respuesta4 == "no responde":
    print("0")


NotaFinal=respuesta + respuesta2 + respuesta3 + respuesta4

print("Tu nota final es: " + NotaFinal)
"""""""""



"""
numero=int(input("NUMERO:  "))
if numero == 
"""
"""
#ej3
dado=int(input("decime un numero: "))
if dado == 1:
    print("6")
elif dado == 2:
    print("5")
elif dado == 3:
    print("4")
elif dado == 4:
    print("3")
elif dado == 5:
    print("2")
elif dado == 6:
    print("1")
else:
    print("INCORRECTO")

"""
#ej5
semana=int(input("decime un numero de la semana: "))
if semana == 1:
    print("lunes")
elif semana == 2:
    print("martes")
elif semana == 3:
    print("miercoles")
elif semana == 4:
    print("jueves")
elif semana == 5:
    print("viernes")
elif semana == 6:
    print("sabado")
elif semana == 7:
    print("domingo")
else:
    print("INCORRECTO")

