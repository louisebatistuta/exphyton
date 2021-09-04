# exphyton
class Pessoa:
    def __init__(self, nome, idade, peso, altura):
        self.nome = nome
        self.idade = idade
        self.peso = peso
        self.altura = altura
    def envelhecer(self):
        self.idade += 1
    def engordar(self):
        self.peso += 1
    def emagrecer(self):
        self.peso -= 1
    def crescer(self):
        if self.idade < 21:
            self.altura += 0.5

Rafaella = Pessoa(nome = 'Louise', idade = 28, peso = 60.0, altura = 1.65)
print(f'Nome: {Louise.nome}, Idade: {Louise.idade}, Peso: {Louise.peso}, Altura: {Louise.altura}')
while Louise.idade < 80:
    Louise.envelhecer()
    Louise.engordar()
    Louise.emagrecer()
    Louise.crescer()
    print(f'Nome: {Louise.nome}, Idade: {Louise.idade}, Peso: {Louise.peso}, Altura: {round(Louise.altura,2)}')
