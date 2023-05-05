def suma(a, b, c):
    resultado = a + b + c
    return resultado


# Llamando a la función y asignando valores
valor1 = 2
valor2 = 5
valor3 = 7

resultado_suma = suma(valor1, valor2, valor3)
print(resultado_suma)


class Coche:
    def __init__(self, puertas):
        self.puertas = puertas

    def agregar_puerta(self):
        self.puertas += 1


# Creando un objeto Coche
miCoche = Coche(3)

# Agregando una puerta al objeto Coche
miCoche.agregar_puerta()

# Mostrando el número de puertas
print(miCoche.puertas)

