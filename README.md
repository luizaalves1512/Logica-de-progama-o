# Lista-01



for i in range(1, 11):
    print(i)

i = 10
while i >= 1:
    print(i)
    i -= 1

nome = input("Digite seu nome: ")
for _ in range(5):
    print(nome)

for i in range(0, 21, 2):
    print(i)

senha = ""
while senha != "1234":
    senha = input("Digite a senha: ")
print("Senha correta!")

soma = 0
for _ in range(5):
    numero = int(input("Digite um número: "))
    soma += numero
print("Soma total:", soma)

for i in range(1, 11):
    if i % 2 != 0:
        continue
    print(i)

contador = 0
while True:
    numero = int(input("Digite um número (0 para sair): "))
    if numero == 0:
        break
    contador += 1
print("Quantidade de números digitados:", contador)

numero = int(input("Digite um número para ver a tabuada: "))
for i in range(1, 11):
    print(f"{numero} x {i} = {numero * i}")
