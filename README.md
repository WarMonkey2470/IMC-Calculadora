# IMC-Calculadora
Calculadora de índice de masa corporal (IMC)
# Le pedimos nombre
n = input("Su nombre por favor: ")
# El apellido paterno y materno
l = input("Sus apellidos paterno y materno por favor: ") 
# Edad
e = int(input("Su edad en años por favor: "))
# Altura 
a = float (input ("Su altura en metros por favor: "))
est = a
# Peso
m = float (input("Su masa en kilogramos por favor: "))

# Calculo de IMC, masa (En kilogramos) entre la estatura (en metros) elevada al cuadrado
IMC = m / est**2
# Le decimos si es mator o menor de edad, si es menor a 18 es menor y si no es mayor edad
#Solo ruegue porque a nadie se le ocurra meter numeros negativos, le va a decir que es menor de edad
if(e < 18): 
    print("Usted es menor de edad")
else:
    print("Usted es mayoe de edad")
#Le imprimos el IMC para que ponga sad
print("IMC: " + str(IMC) ) 

if IMC >= 0 and IMC <= 15.99:
    print ("Delgadez severa")
elif IMC >= 16.00 and IMC <= 16.99:
    print ("Delgadez moderada")
elif IMC >= 17.00 and IMC <= 18.49:
    print ("Delgadez leve")
elif IMC >= 18.50 and IMC <= 24.99:
    print ("Normal")
elif IMC >= 25.00 and IMC <= 29.99:
    print("sobre peso")
elif IMC >= 30.00 and IMC <= 34.99:
    print ("Obesidas leve")
elif IMC >= 35.00 and IMC <= 39.00:
    print ("Obesidad Media")
elif IMC >= 40.00:
    print ("Obesidad morbida")  
    #######################################
    Esto lo hice basandome en un codigo que vi en nuestra tarea, solo espero haberlo echo bien y me seguire esforzando
    lo probe conmigo primero y tengo peso normal: 21.00
