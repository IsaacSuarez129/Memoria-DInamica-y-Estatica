# Memoria-Dinamica-y-Estatica
PRACT2 - Gestion Memoria en Python

#Suarez Canche Isaac Moises 3SB Memoria Dinamica 

frutas = []
frutas.append("Mango")
frutas.append("Manzana")
frutas.append("Banana")
frutas.append("Uva")
frutas.append("Fresa")
frutas.append("Zarzamora")
frutas.append("Naranja")
frutas.append("Toronja")

print(frutas)
del frutas[0]
del frutas[2]
del frutas[4]
frutas.append("Piña")
print(frutas)

#Memoria Estatica
calificaciones = [0]*10

for i in range(10):
    calificaciones[i] = int(input("Ingresa la calificación:"))
print(calificaciones)
