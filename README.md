def a(): #chifre de 1 à10 , première fonction
    i = 0
    while i < 10:
        i = i + 1
        print(i)

a()

print("\t") #espace

def b(): #carré de chaque chiffre, deuxième fonction
    i = 0
    while i < 10:
        i = i + 1
        carré = i * i
        print(carré)

b()

print("\t") #espace, troisième fonction

def c():
    i = 1
    som = 0
    while i <= 10:
        som += i ** 2
        print(som)
        i += 1

c()
print("\t") #espace
c()
