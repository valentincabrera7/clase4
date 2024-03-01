nombre = input("Ingrese su nombre: ")
edad = int(input("Ingrese su edad: "))

# Puedo ejecutar en print sino puedo hacer una variable
validacion_1 = nombre != "****"
validacion_2 = edad > 5 and edad < 20
validacion_3 =  len(nombre) >=4 and len(nombre) < 8
validacion_4 =  edad * 3 > 35

respuesta = validacion_1 and validacion_2 and validacion_3 and validacion_4 
# Se usa el and para que me tire solamente un bool, true or false
print(respuesta)

# Otra forma de ejecutar, solo usando print y haciendo la funcion dentro
print(nombre != "****") 
print(edad > 5 and edad < 20)
print(len(nombre) >= 4 and len(nombre) < 8)
print(edad *3 > 35)

# En el AND solo es True si todas las condiciones son VERDADERAS, si hay una Falsa, da False
# True and True = True
# True and False = False
# False and True = False
# False and False = False 

# En el Or solo es False si todas las condiciones son Falsas, si hay una Verdadera, da True
# True or True = True
# True or False = True
# False or True = True
#False or False = True
