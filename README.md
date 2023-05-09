class Persona:
    def __init__(self, edad, nombre, telefono):
        self.edad = edad
        self.nombre = nombre
        self.telefono = telefono

class Cliente(Persona):
    def __init__(self, edad, nombre, telefono, credito):
        super().__init__(edad, nombre, telefono)
        self.credito = credito

cliente1 = Cliente(30, "Juan", "123456789", 5000)
print(cliente1.edad)
print(cliente1.nombre)
print(cliente1.telefono)
print(cliente1.credito)

class Trabajador(Persona):
    def __init__(self, edad, nombre, telefono, salario):
        super().__init__(edad, nombre, telefono)
        self.salario = salario

trabajador1 = Trabajador(25, "Maria", "987654321", 15000)
print(trabajador1.edad)
print(trabajador1.nombre)
print(trabajador1.telefono)
print(trabajador1.salario)
