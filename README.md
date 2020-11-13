# Programa-em-python---GITHUB
Atividade 17. Exer. 3 - FCC
cont = 0
num = 0
total = 0
print('Escolha dois números, será apresentada uma soma dos inteiros entre eles: ')
n1 = int(input('Digite o 1º número: '))
n2 = int(input('Digite o 2º número: '))

while n2 < n1:
     print('********************************************************\n'
            'O 2º número é menor que o 1º\n'
            'A soma só será feita se o 2º \n'
            'for maior que o 1º número digitado\n'
            '********************************************************')
     break
for num in range (n1 +1, n2):
    print(num)
    total += num
print('Sendo assim a soma deles é de {}'.format(total))
