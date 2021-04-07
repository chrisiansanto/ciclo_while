# ciclo_while
print("Ejercicio 1")
n=1
while n<5:
    print(n)
    n=n+1
#-----------------
print("ejercicio 2")
anio = 2010  
while anio <= 2012:  
         print ("Informes del Año", str(anio))  
         anio += 1
#-----------------------
print ("ejercicio 3")
print ("Introduzca la nota de un estudiante (-1 para salir): ")
total = 0
contar = 0
grado = int(input())
while grado != -1:
    total = total + grado
    contar = contar + 1
    print ("Introduzca la nota de un estudiante (-1 para salir): ")
    grado = int(input())
promedio = total / contar
print ("Promedio de notas del grado escolar es: " + str(promedio))
#------------------------------------
print("Ejercicio 4")
while True:
    opcion =(input("""ELige una fruta para tu desayuno: 
                   1-mazana
                   2-bananas
                   3-nada
                  """))
    if opcion == "1":
        print("Has seleccionado manzana")
        break
    elif opcion == "2":
        print("Has seleccionado bananas")
        break
    elif opcion == "3":
        print("Has seleccionado nada")
        break
    else:
        print ("debes seleccionar una opcion entre (1 , 2 o 3)")
print("Programa terminado, que disfrute tu desayuno :D")
#-------------------------------------------------------
print("Ejercicio 5)
while True:
        x = int(input("Ingrese un numero (0 para terminar): "))
        if x == 0:
            print("termino el proceso. ")
            break
        elif x > 0:
            print ("Numero positivo")
        else:
            print ("Numero negativo")

