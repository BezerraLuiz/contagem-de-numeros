soma = 0
i = 0
maior = 0
menor = 1000000000000
contagem = 0

while i != -1:
    num = float(input("Digite um número qualquer, e para cancelar digite -1: "))
    if num != -1:
        soma = soma + num
        contagem += 1
        media = soma/contagem
        if num > maior:
            maior = num
        if num < menor: 
            menor = num
    else:
        i = -1
print("A média é: ", media)
print("A soma é: ", soma)
print("Maior número foi: ", maior)
print("Menor número foi: ", menor)
