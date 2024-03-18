
# print("hello,wordl")
 

# 1º


# name = input("Qual é o seu nome?")
# input(f"hello {name}, nice to meet you!")


# 2º


# name_employee = input("qual é o seu nome:")
# salary = float(input("what is your salary?:"))
# print(input(f"the employee {name_employee} has a salary ${salary} "))


# 3º (1º)


# n1 = int(input("digite um valor de N1 ->"))
# n2 = int(input("digite um valor de N2 ->"))
# s = n1 + n2
# print(f"O valor da soma de {n1} + {n2} é igual a -> {s}")


# 04º (2º)

# nota_1 = float(input("Adicione a 1º nota"))
# nota_2 = float(input("Adicione a 2º nota"))

# resultato = nota_1 + nota_2 / 2 

# n = float(input("digite um valor:"))
# print(n)


# 05º (3º)                   "As partes 


# finais em "azul" são chamados de "metodo"
# programa = input("digite Algo:")
# print("O tipo primitivo desse valor é ", type(programa))
# print("só tem espaçõs?", programa.isspace())
# print("é um número?", programa.isnumeric())
# print("é alfabetico", programa.isalpha())
# print("é alfanumerico?", programa.isalnum())
# print("está em maiúscula ?", programa.isupper())
# print("está em minuscula?", programa.islower())
# print("está capitalizada?", programa.istitle())


# 06º (4º)


# n1 = int(input("DIGITE UM NÚMERO:"))
# a  = n1 - 1
# s  = n1 + 1

# resultado = (f"Os valores resultantes {a},{n1},{s}")
# print(resultado)


# 07º (5º)


# n1 = int(input("digite um númenro:"))
# dobro = n1 * 2 
# triplo = n1 * 3 
# raiz = n1 ** (1/2)

# print(f"Os valores correspondentes são: \n{dobro} \n{triplo}\n{raiz}")


# 08º (6º)


# n1 = float(input("digite a nota N1:"))
# n2 = float(input("digite a nota N2:"))
# notas = n1,n2
# media = sum(notas) / len(notas)


# print(f"A média desse aluno é: {media}")


# 09º (7º)


# m =int(input("escrava um valor em metros :"))

# cm = m * 100
# mm = m * 1000


# print(f"Os valores convertidos são {cm}cm, e {mm}mm. ")


# 10º (8º)


# n = int(input("digite um número:"))

    
# print(f"{n} x 1 = {n*1} \n{n} x 2 = {n*2} \n{n} x 3 = {n*3} \n{n} x 4 = {n*4} \n{n} x 5 = {n*5} \n{n} x 6 = {n*6} \n{n} x 7 = {n*7} \n{n} x 8 = {n*8} \n{n} x 9 = {n*9} \n{n} x 10 = {n*10} ")
# print("_"*15)


# 11º (9º)


# nome = input("digite seu NOME:")
# reais = float(input("quanto você tem na sua CARTEIRA? "))
# dollar = float(4.87)
# compra = reais / dollar


# print(f"{nome}, você poderia comprar {compra} dolares")



# 12º (10º)


# largura = float(input("digite a largura da parede :"))
# altura  = float(input("digite a altura da parede :"))

# area    = altura * largura
# tinta   = 2
# total_litros = area / tinta

# print(f"O valor total de litros de tinta é --> {total_litros}")


# 13º (11º)


# preço = float(input("digite o PREÇO R$:"))
# valor_do_desconto = float(input("digite o valor da porcentagem para o  desconto:"))

# porcentagem = (valor_do_desconto *  preço) /100

# novo_preço = preço - porcentagem

# print(f"O valor com o desconto fica ---> {novo_preço:.2f}")

# 14º (12º)


# nome = input("Qual é o seu nome?")
# salario = float(input("Qual o valor o seu salário atual?"))
# aumento = float(input("Digite o valor do AUMENTO:"))

# porcentagem = (aumento * salario)/100


# novo = salario + porcentagem

# print(f"{nome}, seu novo salário é de R$: {novo:.2f}")


# 15º (13º)


# celsius = float(input(f"Digite qual a temperatura em Celsius:"))

# # formula pronta encontrada no google.

# f = (celsius * 9/5) + 32
# print(f"A temperatura equivalente em fahrenheit é: \n{f}ºF")
# print("_"*12)


# 16º (14º)


# km      =   float (input ("Qual an de KM percorridos?"))
# dias    =   int   (input ("Quantos dias aluga naluguel_diario = dias  *  60
# km_percorrido  = km    *  0.15 

# preço_total    = aluguel_diario + km_percorrido

# print(f"O valor total é de : {preço_total:.2f}")


#  17º (15º)


# import math
# num = int(input("digite um número :"))
# raiz = math.sqrt(num)

# print(f"A raiz de um {num} é igual a {raiz}")
# print(f"A raiz de um {num} é igual a {math.trunc(raiz):.2f}")
# print(f"A raiz de um {num} é igual a {math.ceil(raiz):.2f}")
# print(f"A raiz de um {num} é igual a {math.floor(raiz):.2f}")


# 18º (16º)


# from math import trunc 
# num = float(input("digite um número REAL:"))
# print(f"O número {num} tem a parte inteira de: {trunc(num)}")


# 19º (17º)


# faça um programa que leia o comprimeito do cateto oposto e do cateto adjacente /  calcule e mostre o comprimento da hipotenusa.

# import math
# oposto = float(input("Digite o valor do CATETO OPOSTO :"))
# adjacente = float(input("Digite o valor do ADJACENTE:"))

# hipotenusa = math.hypot(oposto,adjacente)

# print(f"o valor da hipotenusa é igual a {hipotenusa:.2f}")

# A hipotenusa e o print logo abaixo foi minha forma de encontrar a hipotenusa.

# hipotenusa = (oposto ** 2) + (adjacente ** 2) 

# print(f"o valor da hipotenusa é igual a {math.sqrt(hipotenusa):.2f}")


# 20º (18º)


# ler um angulo qualquer e mostre na tela os valores de sen, cos e tan.

# from math import sin,cos,tan,radians
# ângulo = float(input("Digite o valor do ÂNGULO:"))

# seno   = sin(radians(ângulo))
# cosseno = cos(radians(ângulo))
# tangente =tan(radians(ângulo))

# print(f"o valor do seno é igual a {seno:.2f},\ndo cosseno {cosseno:.2f}\ne o da tangente {tangente:.2f}. ")



# 21º(19º)


# from random import choice

# aluno1 = input("digite o nome do 1º aluno:")
# aluno2 = input("digite o nome do 2º aluno:")
# aluno3 = input("digite o nome do 3º aluno:")
# aluno4 = input("digite o nome do 4º aluno:")


# lista = [aluno1,aluno2,aluno3,aluno4]

# nome_sorteado = choice(lista)

# print(f"O aluno sorteado para limpar o quadro foi: \"{nome_sorteado}\"")


# 22º (20º)


# import random

# aluno1 = input("digite o nome do 1º aluno:")
# aluno2 = input("digite o nome do 2º aluno:")
# aluno3 = input("digite o nome do 3º aluno:")
# aluno4 = input("digite o nome do 4º aluno:")

# lista = [aluno1, aluno2, aluno3, aluno4]

# lista_embaralhada = random.sample(lista, len(lista))
# print("A ordem escolhida é :",lista_embaralhada)


# 23º (21º)


# abra uma arquivo em mp3

# import pygame
# pygame.init()
# pygame.mixer.music.load("TO VOANDO ALTO.mp3")
# pygame.mixer.music.play()
# pygame.event.wait()


# 24º (22º)


# nome = str(input("Digite seu nome completo:")).strip()
# print("Analisando...")
# print("seu nome completo com todas as letras MAIÚSCULAS \"{}\"".format(nome.upper()))
# print("seu nome completo com todas as letras MINÚSCULAS \"{}\"".format(nome.lower()))

# nome_sem_espaço  =  nome.replace(" ","")  ##retirei os espaços entre as strings
# contagem         =  len(nome_sem_espaço)  #contei a quantidade de caracteres sem os espaços
# nome_bloco       =  nome.split()          #transformei os espaços entre as strings em blocos
# first_name       =  nome_bloco[0]         #pedi para o pc me retornar a strg digitando seu número
# num_contagem     =  len(first_name)       ##pedi para o pc me retornar o valor do termo - first_name


# print(f"QUANTAS LETRAS sem considerar os ESPAÇOS \"{contagem}\"")
# print(f"A quantidade de letras do primeiro nome é : \"{num_contagem}\"")
 
# forma do professor abaixo:
# print("A QUANTIDADE LETRAS sem considerar os ESPAÇOS \"{}\"".format(len(nome) - nome.count(" ")))
# print("A quantidade de letras do FIRST NAME é \"{}".format(nome.find("")))


# #25º (23º)


# num      = input("digite um numero de \"0 \" a \"9999\":")
# digitos  = [int(digitos) for digitos in str(num)]
# digito1  = num[0]
# digito2  = num[1]
# digito3  = num[2]
# digito4  = num[3]


# print("milhar:{}\ncentena:{}\ndezena:{}\nunidade:{}".format(digito1,digito2,digito3,digito4))


# 26º (24º)


# nome_cidade = input("digite o nome da cidade:" )
# sem_espaços = nome_cidade.strip()
# começa_com_santos = sem_espaços.lower().startswith("santos")

# if começa_com_santos:
#     print("A palavra 'santos'  está presente nesta cidade ")

# else:
#     print("A palavra 'santos' não se encontra no COMEÇO deste nome.")


# 27º (25º)


# nome = str(input("Digite o seu NOME:")).strip()
# tem_silva = "silva" in nome.lower()

# if tem_silva:
#     print("este nome CONTEM  silva")

# else:
#     print("este nome NÃO tem SILVA.")


# 28º(26º)


# frase = str(input("digite uma frase :")).strip()
# mini = frase.upper()
# sem_espaço = mini.replace(" ","") #retirei os espaços entre as strings.
# letra      = mini.count("A")       #Quantas vezes a letra A aparece na frase ?
# posição_a = sem_espaço.find("A")   #Qual foi a primeira letra A que apareceu na frase ?
# posição_a2 = sem_espaço.rfind("A") #Qual foi última vez que a letra A apareceu?

# print("Quantas vezes a letra A aparece na frase?:{}\nQual foi a primeira letra A que apareceu na frase ?:{}\nQual foi última vez que a letra A apareceu?:{}".format(letra,posição_a,posição_a2))

# forma do professor :
# frase_completa = str(input("digite uma frase :")).upper().strip()
# frase          = frase_completa.replace(" ",""),
# print("A letra A aparece {} vezes na frase.".format(frase_completa.count("A")))
# print("A primeira letra A apareceu na posição {}".format(frase_completa.find("A")+1))
# print("A última posição que a letra A apareceu foi {}".format(frase_completa.rfind("A")+1))


# 29º (27º)


# nome_completo = str(input("Digite seu nome COMPLETO:")).upper().strip()
# sem_espaço    = nome_completo.replace(" ","")
# nome_bloco    = nome_completo.split()
# first_name    = nome_bloco[0]
# last_name     = nome_bloco[len(nome_bloco)-1] 

# print("nice to meet you {},\nyour fist name is \"{}\"\nand your last name is \"{}\".".format(nome_completo,first_name.upper(), last_name.upper()))


# 30º (28º)


# from random import choice
# from time import sleep

# lista = [0,1,2,3,4,5]
# num_sorteado = choice(lista)
# print("-=-"*20)
# print("vou pensar em um número entre 0 e 5. Tente adivinhar...")
# print("-=-"*20)

# jogador = int(input("Digite um número de 0 - 5:"))

# print("PROCESSANDO...")
# sleep(3)

# if num_sorteado == jogador:
#     print("-=-"*20)
#     print("parabéns!!! você conseguiu me vencer!!!")
#     print("-=-"*20)

# else:
#     print("-=-"*20)
#     print("Você errou e o computador venceu. O número sorteado foi: {}\n Tente novamente".format(num_sorteado))
#     print("-=-"*20)
    

# 31º (29º)


# velocidade = float(input("Qual a VELOCIDADE do carro ?"))
# calculo = (velocidade - 80) * 7
# if velocidade > 80:
#     print("você acabou de ser multado por excesso de velocidade.")
#     print("Sua multa vai custar R$7,00 por cada km acima do limite.\n total de R${:.2f}.".format(calculo))
# else:
#     print("muito bem!!! Prossiga sua viagem com segurança.")


# 32º (30º)


# num = int(input("please, digite um número:"))

# if num % 2 == 0:
#   print("Este número é par")
# else:
#   print("Este número é ímpar")


# 33º (31º)


# distância = float(input("Quantos KM foram percorridos?"))
# # se for até 200km
# preço_1   = distância * 0.50
# # se for mais que 200, mas menos ou igual a 0.45
# preço_2   = distância * 0.45

# if distância <= 200:
#     print("Sua passagem fica no valor de R${:.2f}".format(preço_1))
# else:
#     print("Sua passagem fica no valor de R${:.2f}".format(preço_2))


# 34° (32°)


# ano = int(input("digite qualquer ano:"))

# if ano % 4 == 0  and ano % 100 != 0 or ano % 400 ==0:
#     ano = True
#     print("este ano é bissexto")

# else:
# #     print("Este ano não é bissexto")
# from datetime import date
# ano = int(input("Que ano quer analizar? Coloque 0 para analizar o ano atual :"))
# if  ano == 0:
#     ano = date.today().year # esse comando mostra o ano registrado na máquina.

# if ano % 4 == 0  and ano % 100 != 0 or ano % 400 ==0:
#      print("O {} é um ano bissexto!".format(ano))
# else:
#      print("o ano {} NÃO é bissexto")

# 35º (33º)


# numero1 = int(input("Digite o primeiro número:"))
# numero2 = int(input("Digite o segundo número:"))
# numero3 = int(input("Digite o terceiro número:"))

# if numero1 > numero2 and numero1 > numero3:
#     print("o maior número é:{}".format(numero1))
# elif numero2 > numero1 and numero2 > numero3:
#     print("O maior númweo é:{}".format(numero2))
# elif numero3 > numero1 and numero3 > numero2:
#     print("O maior número é: {}".format(numero3))

# if numero1 < numero2 and numero1 < numero3:
#     print("o menor número é:{}".format(numero1))

# elif numero2 < numero1 and numero2 < numero3:
#     print("O menor  número é:{}".format(numero2))
# elif numero3 < numero1 and numero3 < numero2:
#     print("O menor número é: {}".format(numero3))

# 36° (34°)


# salário = float(input("Qual o seu salário? "))

# porcentagem1 = salário * (10/100) 
# porcentagem2 = salário * (15/100)
# salario1     = salário + porcentagem1
# salario2     = salário + porcentagem2
# if salário >= 1250:
#     print("Seu novo salário é de R${:.2f}".format(salario1))
# else :
#     print("Seu novo salário é de R${:.2f}".format(salario2))


#37º (35º)


# r1 = float(input("Digite o comprimento da 1º linha:"))
# r2 = float(input("Digite o comprimento da 2º linha:"))
# r3 = float(input("Digite o comprimento da 3º linha:"))

# if r1 + r2 > r3:
#     print("\033[4;1;31;45mTriangulo deu certo, mano\033]m")
# elif r1 + r3 > r2:
#      print("triangulo deu certo, mano")
# elif r2 + r3 > r1:
#       print("triangulo deu certo, mano")
# else:
#      print("infelizmente não formou o triângulo")


# 38° (36°)


# valor = float(input("Qual o VALOR da casa ?"))
# salário = float(input("Quanto que você recebe de SALÁRIO por mês ?"))
# ano = int(input("Em quantos anos você deseja pagar ?"))

# anos = ano * 12 # anos em meses 360
# parcela = valor / anos # 833.33...
# porcentagem = salário * (30/100)


# if parcela <= porcentagem:
#     print("\033[1;4;32mempréstimo aprovado\033[m")
# else:
#     print("\033[1;4;31memprestimo negado\033[m")


#39º  (37º)


# num = int(input("Digite um número INTEIRO:"))
# base = int(input("Digite qual a base de conversão você deseja. \n 1 - para BINÁRIO. \n 2 - para OCTAL. \n 3 - para hexadecimal \n reponda:"))


# binário = bin(num)[2:]
# octal  = oct(num)[2:]
# hexadecimal = hex(num)[2:]


# if base == 1:
#     print("O valor BINÁRIO deste numero é {}".format(binário))

# elif base == 2:
#     print("O valor OCTAL deste número é {}".format(octal))

# elif base == 3:
#     print("O valor HEXADECIMAL deste número é {}".format(hexadecimal))


#40º (38º)


# num1 = int(input("Digite o PRIMEIRO NÚMERO:"))
# num2 = int(input("Dgite o SEGUNDO NÚMERO:"))

# if num1 >  num2:
#     print("O primeiro valor:  \033[1;4;34m{}\033[m é maior do que o segundo valor: \033[1;4;31m{}\033[m".format(num1,num2))
# elif num1 < num2:
#     print("O primeiro número:  \033[1;4;34m{}\033[m é menor do que o segundo valor:  \033[1;4;31m{}\033[m".format(num1,num2))
# else:
#     print("nâo existe valor maior, os dois são \033[1;4;34mIGUAIS\033[m.")


#41º (39º)


# from datetime import datetime
# genero = input("Qual o seu GÊNERO? \n digite M para MASCULINO ou F para FEMININO.")
# nascimento = int(input("Qual o ANO que você nasceu ?"))
# ano_atual = datetime.now().year
# idade = ano_atual - nascimento


# if idade ==  18 : 
#    print("Você deve se alistar.")

# elif idade >= 18 and idade <= 45:
#    print("você ainda pode se alistar.") 
# elif idade < 18:
#    print("Você não pode se alistar ainda.")
# else:
#    print("Seu tempo para se alistar expirou")


#42º (40º)


# n1 = float(input("Digite a primeira nota:"))
# n2 = float(input("Digite a segunda nota:"))
# notas = (n1,n2)
# media = sum(notas) / len(notas)

# if media <= 5:
#     print("\033[1;4;31mReprovado\033[m")
# elif media >= 5 and media <= 6.9:
#     print("\033[1;4;34mRecuperação\033[m")
# else:
#     print("\033[1;4;32mAprovado\033[m")


#43º (41º)


# from datetime import datetime

# ano = int(input("Digite o seu ano de nascimento:"))
# ano_Atual = datetime.now().year
# idade = ano_Atual - ano

# if idade <= 9:
#     print("Categoria MIRIM")
# elif idade > 9 and idade <= 14:
#     print("Categoria INFANTIL")
# elif idade > 14 and idade <= 19:
#     print("CATEGORIA JUNIOR")
# elif idade > 19 and idade <= 20:
#     print("CATEGORIA SENIOR")
# else:
#     print("CATEGORIA MASTER")


# 44º (42º)


# r1 = float(input("Digite o comprimento da 1º linha:"))
# r2 = float(input("Digite o comprimento da 2º linha:"))
# r3 = float(input("Digite o comprimento da 3º linha:"))

# if r1 == r2 == r3:
#     print("\033[4;1;32mtriangulo deu certo, mano\033[m")
#     print("Este é um triângulo  forma um\033[4;1;31;45m EQUILATERO\033[m")

# elif r1 == r3 != r2 or r1 == r2 != r3 or r2 == r3 != r1 and r1 + r2 > r3 and r1 + r3 > r2 and r2 + r3 > r1:
#      print("\033[4;1;32mtriangulo deu certo, mano\033[m")
#      print("Este é um triângulo forma um \033[1;4;32;45mISÓSCELES\033[m")

# elif r1 != r2 != r3 and r1 + r2 > r3 and r1 + r3 > r2 and r2 + r3 > r1:
#      print("\033[4;1;32mtriangulo deu certo, mano\033[m")
#      print("Este é um triângulo forma um\033[1;4;35;45m ESCALENO \033[m")


#45º (43º)


# peso = float(input("Por favor, digite o seu PESO (KG):"))
# altura = float(input("Por favor, digite sua ALTURA (M):"))



# imc = peso / (altura ** 2)


# if imc < 18.5:
#     print("Seu índice de gordura corporal está \033[1;4;31mABAIXO\033[m da média.")
# elif imc >= 18.5 and imc < 25:
#     print("Seu índice de gordura corporal está\033[1;4;32mIDEAL\033[m")
# elif imc >= 25 and imc < 30:
#     print("Você está com \033[1;4;31mSOBREPESO\033[m") 
# elif imc >= 30 and imc < 40:
#     print("Você está \033[1;4;31mACIMA DO PESO\033[m")
# else:
#     print("Você está com \033[1;4;31mOBESIDADE MÓRBIDA\033[m")


#46º (44º)


# preço = float(input("Qual o preço do produto R$?"))
# print("Qual a forma de pagamento?")
# forma_de_pagamento = int(input(" DIGITE \033[1;4;32m[ 1 ]\033[m: \033[1;4;32mÀ vista DINHEIRO/CHEQUE\033[m; \n Digite \033[1;4;33m[ 2 ]\033[m:\033[1;4;33m À vista/Cartão\033[m; \n Digite \033[1;4;34m[ 3 ]\033[m:\033[1;4;34m Até 2x no cartão\033[m; \n Digite \033[1;4;35m[ 4 ]\033[m: \033[1;4;35m3x ou mais\033[m; \n -->" ))



# porcentagem_dinheiro_cheque = preço * (10/100)
# porcentagem_cartão_ávista =   preço * (5/100)
# porcentagem_2x_cartão = preço
# porcentagem_3x_cartão =  preço * (20/100)

# valor1 = preço - porcentagem_dinheiro_cheque
# valor2 = preço - porcentagem_cartão_ávista

# valor4 = preço + porcentagem_3x_cartão

# if forma_de_pagamento == 1:
#     print("O valor total é de \033[1;4;32mR$ {:.2f} \033[m".format(valor1))
# elif forma_de_pagamento == 2:
#      print("O valor total é de \033[1;4;33mR$ {:.2f} \033[m".format(valor2))
# elif forma_de_pagamento == 3:
#      parcelas = int(input("Em quatas parcelas voçê deseja pagar ?"))
#      print("O valor total é de \033[1;4;34mR$ {:.2f}, em {}x \033[m \033[1;4;31mSEM JÚROS\033[m".format(preço,parcelas))
# elif forma_de_pagamento == 4:
#       parcelas = int(input("Em quatas parcelas voçê deseja pagar ?"))
#       print('''O valor total é de 
#     \033[1;4;35mR$ {:.2f}, em {}x \033[m'''.format(valor4,parcelas))
# else:
#      print("Erro. Digite novamente.")


#47º (45º)


# from random import choice
# from time  import sleep
# # aqui o computador vai escolher algum desses objetos

# lista = ["pedra","papel","tesoura"]
# pc = choice(lista)

# # Agora vamos desenvolver uma forma para a pessoa escolhar uma das opções
# print("-=-"*25)
# jogador = str(input("Digite o seu objeto -=--=- (PEDRA,PAPEL,TESOURA) -=--=- para eu ganhar de você:")).lower().strip()

# print("-=-"*20)
# print("JO")
# sleep(1)
# print("KEN")
# sleep(1)
# print("PO")
# sleep(1)
# print("-=-"*20)

# # agora vamos tentar unir as duas respostas e unilas para ver o resultado

# if pc == jogador:
#     print("-=-"*20)
#     print("\033[1;4;36mEMPATE!\033[m eu escolhi {} e você {}.".format(pc,jogador))
#     print("-=-"*20)

# elif pc == "pedra" and jogador == "papel" or pc == "papel" and jogador == "tesoura" or pc == "tesoura" and jogador == "pedra":
#    print("-=-"*20)
#    print("voçê \033[1;4;36mVENCEU!\033[m!!! eu escolhi {} e você {}.".format(pc,jogador))
#    print("-=-"*20)

# else:
#    print("-=-"*20)
#    print("Desta vez \033[1;4;36mEU VENCI!!!\033[m !!! eu escolhi {} e você {}.".format(pc,jogador))
#    print("-=-"*20)


#48º (46º)

# from time import sleep
# import emoji

# for c in range (10,-1,-1):
#     print(c)
#     sleep(1)
 
# print(emoji.emojize(":🍾🎆*****FELIZ ANO NOVO*****:🍾🎆"))


#49º (47º)


# for n in  range(2,51,2):
#     print( n )
# print("ACABOU")


#50º (48º)


# soma = 0
# cont = 0

# i = int(input("INÍCIO:"))
# f = int(input("fim:"))
# p = int(input("passo:"))


# for c in range(i,f,p):
#    if c % 3 == 0:
#       soma += c
#       cont += 1


# print("A SOMA DOS VALORES É: \033[1;4;31m{}\033[m valores solicitados são \033[1;4;31m{}\033[m ".format(soma,cont))


#51º (49º)

  
# num = int(input("Digite um valor:"))


# for c in range(1,11):
#     tabuada = num * c
#     print("{} x {} = {}".format(num,c,tabuada))


#52º (50º)


# soma_pares = 0
# cont = 0
# for c in range(0,6):
#     n = int(input("Digite um número intereiro:"))
#     if n % 2 == 0:
#         soma_pares += n
#         cont += 1

# print("A soma dos valores pares é:{} e a quantidade de números é :{}".format(soma_pares,cont))


#53º (51º) assistir a aula sobre esse exercício.


# p = int(input("Digite o primeiro valor da uma PA:"))
# r = int(input("Digite a razão da PA:"))
# décimo = p + (10-1) * r

# for pa in range (p,décimo +1 ,r):
#     print(pa, end = "->")
# print("ACABOU")


#54º (52º)
   

# num = int(input("Digite um número inteiro:"))
# tot = 0
# for c in range(1,num + 1):
#     if num % c == 0:
#         print("\033[32m", end =" ")
#         tot += 1
#     else:
#         print("\033[31m", end = " ")
#     print("{}".format(c), end = " ")

# print("\no número {} foi divisível {} vezes".format(num,tot))
# if tot == 2:
#     print("E por isso é primo!")
# else:
#     print("E por isso NÃO É PRIMO!")

#55º (53º) assistir a aula sobre esse exercício.


# frase = str(input("Digite uma FRASE:")).strip().upper()
# junto = frase.replace(" ","")
# palavras = frase.split()
# inverso = ""
# for letra in range(len(junto) - 1, -1 , -1 ):
#     inverso += junto[letra]
# print("O inverso de {} é {}.".format(junto,inverso))
# if inverso == junto:
#     print("Temos um palídromo!")
# else:
#     print("A frase digitada não é um palídromo")


#56º (54º)

# from datetime import datetime
# ano_atual = datetime.now().year
# totmaior = 0 
# totmenor = 0
# for pess in range(1,4):
#     nasc = int(input("Digite o seu ano de nascimento {}?".format(pess)))
#     idade = ano_atual - nasc
#     if idade >= 18:
#         totmaior += 1
#     else:
#         totmenor += 1
# print("Ao todo tivemos {} pessoas maiores de idade.".format(totmaior))
# print("e também tivemos {} pessoas menores de idade.".format(totmenor))


# #57º (55º)


# totmaior = 0 
# totmenor = 0
# for pessoa in range(1,6):
#     peso = float(input("{},qual é o seu peso?".format(pessoa)))
#     if pessoa == 1:
#         totmaior = peso
#         totmenor = peso
#     else:
#         if peso > totmaior:
#            totmaior  = peso
#         if peso < totmenor:
#             totmenor = peso

# print("o maior peso foi {:.1f}KG".format(totmaior))
# print("O peso menor é {:.1f}KG".format(totmenor))



#58º (56º)

# somaidade = 0      
# maioridadehomem = 0
# nomevelho = 0
# médiaidade = 0
# totmulher20 = 0

# for pessoa in range(1,5):
#     nome = str(input("Qual o seu nome ?")).capitalize()
#     idade = int(input("Qual a sua idade {} ?".format(nome)))
#     sexo = str(input("Qual o seu sexo,M/F {} ?".format(nome))).upper()
#     somaidade += idade
    
#     if pessoa == 1 and sexo in "M":
#         maioridadehomem = idade
#         nomevelho = nome
    
#     if sexo in "M" and idade > maioridadehomem:
#         maioridadehomem = idade
#         nomevelho = nome
    
#     if sexo in "F" and idade < 20:
#         totmulher20 += 1 

# médiaidanomevelho = somaidade  / 4

# print("A média de idade do grupo é de {} anos". format(médiaidanomevelho))
# print("O homem maus velho tem {} anos e se chama {}.".foramt(maioridadehomem,nomevelho))
# print("Ao todo são {} mulheres com menos de 20 anos". format(totmulher20))


#59º (57º)


# sexo = str(input("Qual é o seu sexo ? \nM/F:")).upper().strip()[0]


# while  sexo not in "MF":
#     sexo = str(input("Erro. Tente novamente :")).upper().strip()[0]

# if sexo == "M":
#         sexo = "masculino"
# elif sexo == "F":
#         sexo = "Feminino"
    
# print("Sexo {} registrado com sucesso.".format(sexo))


# #60º (58º)


# import random


# computador = random.randint(0,10)

# print("Vou pensar em número, tente adivinhar...")

# jogador = int(input("Qual o seu palpite ? ==>"))

# acertou = False
# palpite = 0
# while not acertou:
#    palpite += 1
#    if jogador == computador:
#         acertou = True
#         print("\n\nParabéns! Você conseguiu me vencer")
#    else:
#         if jogador < computador:
#             print("mais...")
#         elif jogador > computador:
#             print("Menos...")
            
#         jogador = int(input("Tente novamente :"))
    
# print("Você me venceu depois de {} palpite(s).!!!".format(palpite))



#61º (59º)


# num_1 = int(input("Digite o 1º número:"))
# num_2 = int(input("Dgite o 2º número:"))
# opção = 0


# while opção != 5:
    
#     print('''    [ 1 ] somar
#     [ 2 ] multiplicar
#     [ 3 ] maior
#     [ 4 ] novos números
#     [ 5 ] sair do programa ''')                                         
#     opção = int(input("Qual é a sua opção?"))
    
#     if opção == 1:
#         soma = num_1 + num_2
#         print(f"A soma de {num_1} e {num_2} é {soma}.")

#     elif opção == 2:
#         multiplicação = num_1 * num_2
#         print ("A multiplicação de {} x {} ==>{}".format(num_1, num_2, multiplicação))

#     elif opção == 3:
#         if num_1 > num_2:
#             maior = num_1
    
#         else:
#             maior = num_2
#         print("Entre {} e {} aopção maior é {}".format(num_1,num_2,maior))
    
#     elif opção == 4:
#         print("informe os números novamente:")   
#         num_1 = int(input("Primeiro valor:"))
#         num_2 = int(input("Segundo valor:"))

#     elif opção == 5:
#         print("Finalizando...")
#     else:
#         print("Opção inválida. Tente novamente.")
# print("fim do programa! Volte sempre!")


#62º (60º)

#1º forma


# # from math import factorial

# # num = int(input("digite um nuemro para calcular:"))

# # f = factorial(num)
# # print(f)


#2º forma


# num = int(input("digite um nuemro para calcular:"))
# c = num
# f =  1
# print("Calculando {}! = ".format(c), end = "")
# while c > 0:
#     print("{}".format(c), end ="")
#     print(" X " if c > 1 else " = ", end = "")
#     f *= c
#     c -= 1
# print("{}".format(f))


#3º forma


# n = int(input("Digite o número que você deseja fatoriar:"))

# resultado = 1

# print("Calculando {}! = ".format(n), end = "")



# for fatorial in range (n, 0, -1):
#     print("{}".format(fatorial), end = "")
#     print( " X " if n  > 1 else " = ", end = "")
#     resultado *= fatorial
# print("\nO resultado de {}! fatorial é {}".format(n,resultado))



#63º (61º) \ #64ª (62º)




# p = int(input("Digite o 1º termo: "))
# r = int(input("Digite a RAZÃO: "))

# termo = p
# cont =  1 
# total = 0 
# mais = 10

# print("-="*20)

# while mais != 0:
#     total = total + mais
#     while  cont <= total: 
#         print("{} => ".format(termo), end = " ")
#         termo += r
#         cont += 1  # prestar atenção que o cont serve para contar quantas vezes vai fazer laços olhar o while "10"
#     print("PAUSA")
#     mais = int(input("Quantos termos você quer mostrar a mais ?"))
     
# print("FIM")


#65º (63º)


# n = int(input("Quantos termos voçê deseja mostrar ?:"))

# t1 = 0
# t2 = 1
# cont = 3
# print("{} -> {}".format(t1,t2),end = "")

# while cont <= n:

#     t3 = t1 + t2
#     print(" -> {}".format(t3), end = '')
#     t1 = t2
#     t2 = t3
#     cont += 1
# print(" -> fIM")


#66º (64º)


# num = int(input("Digite um número INTEIRO:"))
# print("Para sair, basta digitar o número 999.")
# cont = 0
# soma = 0

# while True:
#     if num == 999:
#         break
#     cont += 1 
#     soma =  soma + num
#     num = int(input("Digite novamente:"))
# print("A quantidade de números digitados foram -> {} e a soma dos mesmos ->{}".format(cont,soma))


#67º (65º)


# num = int(input("Digite um número:"))


# cont = 0
# soma = 0
# resposta = 0
# maior = num 
# menor = num 


# while resposta != "N":
#     cont += 1 
#     soma += num
#     if num > maior:
#         maior = num
#     if num < menor:
#         menor = num
#     resposta = str(input("Deseja continuar adicionando valores ? [S/N] \n:")).upper().strip()[0]
#     if resposta =="N":
#         break
#     num = int(input("Digite um número:"))


# média = soma / cont


# print('''      voçê digitou {:.0f} números, a  média  ficou  -> {:.1f}; 
#       O maior número é -> {:.1f};
#       E o menor número é ->{:.1f}.'''.format(cont,média,maior,menor))


#68º (66º)


# n = int(input("Digite um número:"))

# cont = 0
# soma = 0


# while n != 999:
#     soma += n
#     cont += 1
#     print("Quando quiser parar digite : \033[1;;31m999\033[m")
#     if n == 999:
#         break
#     n = int(input("Digite um número:"))

# print(f'''A quantidade de números digitados foram de {cont},
#       e a soma deles é igual a {soma}.''')



#69º (67º) # Tabuada com while e for in


# num = int(input("digite um valor:"))


# while True:
#     num = int(input("quer ver qual valor:"))
#     if num < 0:
#         break  
#     for cont in range(1,11):
#         tabuada = num * cont
#         print(f"{num} x {cont} = {tabuada}") # ou --> print(f"{num} X {cont} = {num * cont}" ) 
# print("Programa encerrado, volte sempre.")


#70º (68º) PAR OU ÍMPAR


# from random import randint
# v = 0
# while True:
#     jogador = int(input("Digite um valor -->"))
#     computador = randint (0, 10)
#     total = jogador + computador
#     tipo = " "
#     while tipo not in  "PI":
    
#         tipo = str(input("Par ou Ímpar? P/I:")).upper().strip()[0]
#     if tipo == "P":
#         if total % 2 == 0:
#             print("voçê VENCEU!")
#             v += 1 
        
#         else:
#             print("Vocçê PERDEU!")
#             break
    
#     elif tipo == "I":
#         if total % 2 == 1:
#             print("Voçê VENCEU!")
#             v += 1        
#         else:
#             print("Você PERDEU!")
#             break
#     print(f"Deu PAR" if total % 2 == 0 else "Deu ÍMPAR")
#     print("Vamos jogar novamente !!!")
# print(f"Deu PAR" if total % 2 == 0 else "Deu ÍMPAR")
# print(f"GAME OVER !!! voçê VENCEU {v} vezes.")
# print(f"Voçê jogou {jogador} e o computador {computador}. Total de {total}")



#71º (69º) 

'''*Crie um programa que leia a idade e o sexo de várias pessoas.
 A cada pessoa cadastrada, o programa deverá perguntar 
 se o usuário quer ou não continuar. No final, mostre:*

A) quantas pessoas tem mais de 18 anos.

B) quantos homens foram cadastrados.

C) quantas mulheres tem menos de 20 anos. '''

# mensagem = 0 
# cont_idade = 0 
# cont_idade_f = 0
# maior = 0
# cont_h = 0 
# homem = 0 

# while mensagem != "N":
#     idade = int(input("Digite sua idade :"))
#     cont_idade += 1
#     if idade >= 18:
#         maior += 1

#     gênero = str(input("Digite seu GÊNERO --> M/F:")).upper().strip()[0]
#     cont_h += 1 
#     if gênero == "M":
#         homem += 1 
    
#     elif gênero == "F" and idade < 20:
#         cont_idade_f +=1

#     mensagem = str(input("você deseja CONTINUAR ? S/N?")).upper().strip()[0]

# print(f"Pessoas +18 -> {maior} -> homens cadastrados -> {homem} -> Mulheres -20 -> {cont_idade_f}")    


#72º (70º)


'''*Crie um programa que leia o nome e o preço de vários produtos. 
O programa deverá perguntar se o usuário vai continuar ou não.
 No final, mostre:*


 *A) qual é o total gasto na compra.
total += preço
B) quantos produtos custam mais de R$1000.

C) qual é o nome do produto mais barato.'''

# total = 0
# tot_mil = 0 
# lista = []
# cont = 0
# menor = 0 
# maior = 0 
# barato = ""


# while True:
    
#     produto = str(input("Digite o produto do produto :")).strip().title()
#     preço = float(input("Digite o valor do produto: R$ "))
#     pergunta = str(input("Voçê deseja continuar ? S/N \n:")).strip().upper()[0]
#     cont += 1 
#     total += preço
#     lista.append((produto,preço)) 
   
#     if preço > 1000:
#         tot_mil += 1

#     if  cont == 1: 
#         menor = preço
#         barato = produto
    
#     else:
#         if preço < menor:
#             menor = preço
#             barato = produto

#     if pergunta == "N":
#         print("Programa finalizado")
#         break   
    
# print("\nProdutos:")

# for item in lista:
#     print(f"{item[0]} --> R${item[1]}")

# print(f"Existe(m) {tot_mil} produto(s) com o valor maior que R$1.000,00 ")
# print(f"O {barato} é o mais barato custando R${menor}")
# print(f"\nTotal ---> R${total}")


#73º (71º)


'''Crie um programa que simule o funcionamento de um caixa eletrônico.
 No início, pergunte ao usuário qual será o valor a ser sacado (número inteiro)
e o programa vai informar quantas cédulas de cada valor serão entregues. OBS:

considere que o caixa possui cédulas de R$50, R$20, R$10 e R$1.'''


# print("="*30)
# print("{:^30}".format ("BANCO CEV"))
# print("="*30)

# valor = int(input("Qual o valor a ser SACADO ?R$ "))

# total = valor
# céd = 50
# totcéd = 0

# while True:
#     if total >= céd:
#         total -= céd
#         totcéd += 1
#     else:
#         if totcéd > 0:
#             print(f"Total de {totcéd} cédulas de R$ {céd}")
#         if céd == 50:
#             céd = 20
#         elif céd == 20:
#             céd = 10
#         elif céd == 10:
#             céd = 1
#         totcéd = 0
#         if total == 0 :
#             break
# print("="*30)
# print("voltw sempre ao BANCO CEV! Tenha um bom dia!")


#74º (72º)
'''Crie um programa que tenha uma tupla totalmente preenchida 
com uma contagem por extenso, de zero até vinte.
Seu programa deverá ler um número pelo 
teclado (entre 0 e 20) e mostrá-lo por extenso.'''



# numeros_por_extenso = (
#     "zero", "um", "dois", "três", "quatro", "cinco",
#     "seis", "sete", "oito", "nove", "dez", "onze",
#     "doze", "treze", "catorze", "quinze", "dezesseis",
#     "dezessete", "dezoito", "dezenove", "vinte"
# )



# numero = int(input("Digite um numero entre 0 e 20:"))
# while numero < 0 or numero > 20:
#     numero = int(input("Tente novamente. Digite um numero entre 0 e 20:"))
# print(f"O numero {numeros_por_extenso[numero]} por extenso.")


#75º (73º)


'''Crie uma tupla preenchida com os 20 primeiros colocados da Tabela do Campeonato Brasileiro de Futebol,
 na ordem de colocação. Depois mostre:

a) Os 5 primeiros times.

b) Os últimos 4 colocados.

c) Times em ordem alfabética.

d) Em que posição está o time da Corinthias.'''


# colocação = ("Palmeiras", "Grêmio", "Atlético-MG", "Flamengo",
#  "Botafogo", "Bragantino", "Fluminense",
#  "Athletico-PR", "Internacional",
#  "Fortaleza", "São Paulo", "Cuiabá", 
#  "Corinthians", "Cruzeiro", "Vasco", 
#  "Bahia", "Santos", "Goiás", "Coritiba", 
#  "América-MG")

# print("-="*80)
# print(f"A colocação dos 5 primeiros times é --> {colocação [0:5]}")
# print("-="*80)
# print(f"Os 4 últimos colocados são --> {colocação[-4:]}")
# print("-="*80)
# print(f"A tabala em ordem alfabética --> {sorted(colocação)}")
# print("-="*80)
# time_procurado = "Corinthians"
# posição = colocação.index(time_procurado)
# print(f" O Corinthians está na posição {posição + 1}º")



#76º (74º)


'''
Crie um programa que vai gerar cinco números aleatórios e 
colocar em uma tupla. Depois disso, mostre a listagem de números gerados
e também indique o menor e o maior valor que estão na tupla.
'''


# from random import  randint


# n = (randint(1,20), randint(1,20), randint(1,20), randint(1,20),
#     randint(1,20))

# print(f"eu sorteei o valor {n}")

# print(f"O maior número sorteado foi {max(n)}")
# print(f"O menor número sorteado foi {min(n)}")
# print(f"Os numeros em ordem: {sorted(n)}")


#77ª (75º)


'''
Desenvolva um programa que leia quatro valores pelo teclado e 
guarde-os em uma tupla. No final, mostre:

A) Quantas vezes apareceu o valor 9.

B) Em que posição foi digitado o primeiro valor 3.

C) Quais foram os números pares.
'''


# valores = () 
# par = 0
# for i in range(4):
#     valor = int(input(f"Digite o {i + 1}º  número: "))
#     valores += (valor,)

#     if valor % 2 == 0:
     
#         par += 1 

# número_procurado = 3
# posição = valores.index(número_procurado)

# print(f"O valor \033[1;;31m9\033[m apareceu \033[1;;32m{valores.count(9)}\033[m vez(es)")
# print(f"O número \033[1;;31m3\033[m apareceu na \033[1;;32m{posição + 1}º\033[m posição. ")
# print(f"A quantidade de números \033[1;;31mpares\033[m foram \033[1;;32m{par}\033[m")


#78º  (76º)


# listagem = (
#           'Lapís', 1.75,
#           "Borracha", 2,
#           "Caderono", 2,
#           "Estojo", 25,
#           "Transferidor", 4.20,
#           "Compasso", 9.99,
#           "Mochila", 120.32,
#           "Canetas", 22.3,
#           "Livro", 34.9
#             )
 
# print("-"*40) 
# print(f"{"LISTAGEM DE PREÇOS":^40}")
# print("-"*40) 

# for pos in range(0,len(listagem)):
#     if pos % 2 == 0:
#         print(f"{listagem[pos]:.<30}", end = '')
#     elif pos % 2 == 1:
#         print(f"R$ {listagem[pos]:.2f}")



# palavras = ("APRENDER", "PROGRAMAR", "LINGUAGEM", "PYTHON", "CURSO", "GRATIS",
#            "ESTUDAR", "PRATICAR", "TRABALHAR", "MERCADO", "PROGRAMADOR", "FUTURO" )


# for p in palavras:
#     print(f"\nNa palavra {p} temos:", end = ' ')
#     for letra in p:
#         if letra.lower() in "aeiou":
#             print(letra,end = ' ' ) 



#79º (77º)


'''Faça um programa que leia 5 valores numéricos e guarde-os em uma lista.
   No final, mostre qual foi o maior e o menor valor digitado
   e as suas respectivas posições na lista'''



# num = [int(input("Digite um valor :")), int(input("Digite um valor :")),
#       int(input("Digite um valor :")), int(input("Digite um valor :")),
#       int(input("Digite um valor :"))]

# maior = max(num) 
# menor = min(num) 
# posição_maior = num.index(maior)
# posição_menor = num.index(menor)

# print(f"O \033[1;32mMAIOR\033[m número desta lista foi \033[1;32m{maior}\033[m e sua COLOCAÇÃO foi \033[1;32m{posição_maior +1}º\033[m ")
# print(f"O \033[1;31mMENOR\033[m número desta lista foi o \033[1;31m{menor}\033[m e sua COLOCAÇÃO foi \033[1;31m{posição_menor +1}º\033[m")


#                                ou

# lista = []
# maior = 0 
# menor = 0 
# for c in range(0,5):
#     lista.append(int(input(f"Digite o {c +1}º número:")))
#     if c == 0:
#         maior = menor = lista[c]
#     else:
#         if lista[c] > maior:
#             maior = lista[c]
#         if lista[c] < menor:
#             menor = lista[c] 

# for i, v  in enumerate(lista):
#     if v == maior:
#         print(f"O \033[1;32mMAIOR\033[m número desta lista foi \033[1;32m{maior}\033[m e sua COLOCAÇÃO foi \033[1;32m{i +1}º\033[m ")

# for i, v in enumerate(lista):
#     if v == menor:
#         print(f"O \033[1;31mMENOR\033[m número desta lista foi o \033[1;31m{menor}\033[m e sua COLOCAÇÃO foi \033[1;31m{i +1}º\033[m")



#80º (78º)


'''Crie um programa onde o usuário possa digitar vários valores numéricos
   e cadastre-os em uma lista. Caso o número já exista lá dentro, ele não será adicionado.
   No final, serão exibidos todos os valores únicos digitados, em ordem crescente.'''

# lista = []
# pergunta = 0 
# cont = 0
# valor = 0

# while pergunta != "S":
        
#         valor = int(input(f"Digite o {cont +1}º valor:"))
#         cont +=1
        
#         if valor  not in lista:
#                 lista.append(valor)
#                 print("Número adicionado com \033[1;32mSUCESSO\033[m")
#         else:
#             print("Esse valor \033[1;31mJÁ EXISTE\033[m. Tente novamente...")

#         pergunta  = str(input("Deseja sair ? SIM / NÃO:")).upper().strip()[0]

# print(f"Os valores\033[1;31m{lista}\033[m ficaram desta forma na ordem ascendente --> \033[1;32m{sorted(lista)}\033[m") 



#81º (79º)


'''Crie um programa onde o usuário possa digitar cinco valores numéricos e cadastre-os em uma lista,
 já na posição correta de inserção (sem usar o sort()). No final, mostre a lista ordenada na tela.'''


# lista =  []


# for c in range(5):
#     n = int(input(f"Digite o {c +1}º:"))
   
#     if c == 0 or n > lista[-1]:
#        lista.append(n)
#     else:
#         pos = 0

#         while pos < len(lista):
#             if n <= lista[pos]:
#                 lista.insert(pos,n)
#                 break
#             pos += 1 

# print("-="*30)
# print(f"Os valores digitados em ordem foram {lista}")


#82º (80º)


'''Crie um programa que vai ler vários números e colocar em uma lista.
Depois disso, mostre:                                                                                                                                                A) Quantos números foram digitados. ok
B) A lista de valores, ordenada de forma decrescente.
C) Se o valor 5 foi digitado e está ou não na lista.'''


# lista = []
# cont = 0 
# numeral = 0
# p = 0



# while  p  != "N":
     
     
#      n = int(input(f"Digite o \033[1;35m{numeral + 1 }º valor\033[m :"))
#      cont += 1 
#      numeral += 1
#      lista.append(n)
#      p = str(input("Deseja continuar ? \033[1;31mSIM\033[m/\033[1;32mNÃO\033[m --> ")).upper().strip()[0]    
    

# if 5 in lista:
#     print("O número \033[1;35m5\033[m \033[1;32mESTÁ\033[m na lista")
# else:
#     print("O número \033[1;34m5\033[m \033[1;31mNÃO ESTÁ\033[m na lista")


# print(f"A quantidade números digitados foi/foram --> \033[1;32m{cont}\033[m ")
# print(f"A lista de forma \033[1;31mDECRESCENTE\033[m --> \033[1;32m{sorted(lista,reverse = True)}\033[m")



#83º (81º)


'''Crie um programa que vai ler vários números e colocar em uma lista.
   Depois disso, crie duas listas extras que vão conter apenas os valores pares e os valores ímpares digitados, respectivamente.
   Ao final, mostre o conteúdo das três listas geradas.'''


# lista_par = []
# lista_impar = [] 

# c = 0
# cont = 0 
# while c != "n" :

    
#     n = int(input(f"Digite o {cont + 1}º valor:"))
#     cont += 1 
     


#     if n % 2 == 0:
#         lista_par.append(n)
#     else:
#         lista_impar.append(n)

    
#     c = str(input("Voçê deseha continuar ? S/N")).lower().strip()[0]


# print(sorted(lista_par))
# print(sorted(lista_impar))


#84º (82º)


'''Crie um programa onde o usuário digite uma expressão qualquer que use parênteses.
   Seu aplicativo deverá analisar se a expressão passada está com os parênteses abertos e fechados na ordem correta.'''


# expr = str(input("Digite a EXPRESSÃO:"))

# pilha = []

# for simb in expr:

#    if simb == "(":
#       pilha.append("(")

#    elif simb == ")":
#       if len(pilha) > 0:
#          pilha.pop()
#       else:
#          pilha.append(")")
#          break
# if len(pilha) == 0:
#    print("Sua expressão está válida!")
# else:
#    print("Sua expressão está INVALIDA!")

#(a+b)(a(4+3)*2)(C)


#85º (83º)


'''
Faça um programa que leia nome e peso de várias pessoas,
guardando tudo em uma lista. No final, mostre:  

A) Quantas pessoas foram cadastradas:ok
B) Uma listagem com as pessoas mais pesadas.ok 
C) Uma listagem com as pessoas mais leves.ok 
'''


# temp = []
# princ = []
# cont_p = 0  
# r = 0 
# maior = menor = 0 
# while r != "N":
#    temp.append(str(input(f'Digite o nome  da {cont_p +1}º pessoa: ')).strip().title().capitalize())
#    cont_p += 1 
   
#    temp.append(float(input(f"Digite o peso da {cont_p}º: ")))

#    if len (princ) == 0:
#       maior = menor = temp[1]
#    else:
#     if temp [1] > maior:
#          maior = temp[1]
#     if temp [1] < menor:
#          menor = temp[1]
   
#    princ.append(temp[:])
#    temp.clear()

#    r = str(input("Voçê deseja continuar ? S/N:")).strip().upper()[0]
    

# print(f"A quantidade pessoa(s) cadastradas foi de --> {len(princ)} pessoa(s)")

# print(f"o maior peso foi de --> {maior}Kg de --> ", end = '')
# for p in princ:
#    if p[1] == maior:
#       print(f"{p[0]}")

# print(f"O menor peso foi de --> {menor}Kg de --> ", end = '')
# for p in princ:
#    if p[1] == menor:
#       print(f"{p[0]}")

# print("-="*10)
# print("         FIM")
# print("-="*10)



#86º (84°)


'''
Crie um programa onde o usuário possa digitar sete valores numéricos
e cadastre-os em uma lista única que mantenha separados os valores pares e ímpares.
No final, mostre os valores pares e ímpares em ordem crescente.
'''

# p = []
# i =  []
# lista = [p,i]


# for c in range(8):
#     n = int(input('Digite um valor: '))
      
#     if n % 2 == 0:
#         p.append(n)
#     else:
#         i.append(n)



# print(f'Os valores  pares  foram --> {sorted(p)}')
# print(f'Os valores ímpares foram --> {sorted(i)}')


# #                             ou


# lista = [ [], [] ]
# n = 0 

# for c in range(8):
#     n = int(input('Digite um valor: '))
      
#     if n % 2 == 0:
#        lista[0].append(n)
#     else:
#         lista[1].append(n)
# lista[0].sorted()
# lista[1].sorted()

# print(f'Os valores  pares  foram --> {lista(0)}')
# print(f'Os valores ímpares foram --> {lista(1)}')


#87° (86°)


'''
Crie um programa que declare uma matriz de dimensão 3x3 
e preencha com valores lidos pelo teclado. 
No final, mostre a matriz na tela, com a formatação correta
'''

# l0 = []
# l1 = []
# l2 = []
# matriz_vazia = [l0,l1,l2 ]
                

# for c in range (3):
#     n = int(input(f'Digite o {c+1}º número da linha 1: '))
#     l0.append(n)
    
# for c in range (3):
#     n = int(input(f'Digite o {c+1}º número da linha 2: '))
#     l1.append(n)

# for c in range (3):
#     n = int(input(f'Digite o {c+1}º número da linha 2: '))
#     l2.append(n)


# print(matriz_vazia[0])
# print(matriz_vazia[1])
# print(matriz_vazia[2])


#88° (86°)


'''
Aprimore o desafio anterior, mostrando no final:
A) A soma de todos os valores pares digitados. ok
B) A soma dos valores da terceira coluna.ok
C) O maior valor da segunda linha. ok  '''


# l0 = []
# l1 = []
# l2 = []
# matriz_vazia = [l0,l1,l2 ]

# pares = 0 
# impares =  0                 
# soma2 = 0 


# for c in range (3):
#     n = int(input(f'Digite o {c+1}º número da linha 1: '))
#     l0.append(n)
        
#     if n % 2 == 0:
#         pares += n 
#     else:
#         impares += n
        
# for c in range (3):
#     n = int(input(f'Digite o {c+1}º número da linha 2: '))
#     l1.append(n)
    
#     if n % 2 == 0:
#         pares += n 
#     else:
#         impares += n
        
# for c in range (3):
#     n = int(input(f'Digite o {c+1}º número da linha 2: '))
#     l2.append(n)
    
#     soma2 += n
    
#     if n % 2 == 0:
#         pares += n 
#     else:
#         impares += n  


# print("-="*5)    
# print(matriz_vazia[0])
# print(matriz_vazia[1])
# print(matriz_vazia[2])
# print("-="*5)    
# print(f"A soma  dos  números pares --> {pares}")
# print(f"A soma dos números ímpares --> {impares}")
# print(f"A soma da 3° linha apenas  --> {soma2}")
# print(f"O valor máximo da 2° linha  --> {max(matriz_vazia[1])}")



#89° (86°)


'''
Faça um programa que ajude um jogador da MEGA SENA a criar palpites.
O programa vai perguntar quantos jogos serão gerados e vai sortear 6 números entre 1 e 60 para cada jogo, cadastrando tudo em uma lista composta.
'''


# from random import randint
# from time import sleep

# print("-"*30)
# print("       JOGOS DA MEGASENA")
# print("-"*30)

# lista = []
# jogos = []
# quant = int(input("Digite a quantidade de jogos:"))
# tot = 1 



# while tot <= quant :
#    cont = 0 
#    while True:
#       num = randint (1,60) 
#       if num not in lista:
#          lista.append(num)
#          cont += 1 
#       if cont >=6:
#          break     
#    jogos.append(lista[:])
#    lista.clear()
#    tot += 1 
  
# print("-="*4,f"SORTEANDO {quant} JOGO(s)","=-"*4)

# sleep(2)

# for i, l in enumerate(jogos):
#    print(f"O {i+1}° jogo :{l}")
#    sleep(2)

# print('''
#       Gênesis 3:19 ARC:
#       Do suor do teu rosto, comerás o teu pão, até que te tornes à terra; 
#       porque dela foste tomado, porquanto és pó e em pó te tornarás.
#       ''')


#90° (88º)


'''
   Crie um programa que leia nome e duas notas de vários alunos e guarde tudo em uma lista composta. 
   No final, mostre um boletim tendo a média de cada um e permita que o usuário possa mostrar 
   as notas de cada aluno individualmente.
'''


# ficha = []
# cont = 0 

# while True:
#    nome = str(input(f"Digite o nome do {cont + 1}ª aluno:")).capitalize().strip()
#    cont += 1 
   
#    nota1 = float(input(f"Digite a 1º nota:"))
#    while nota1 < 0 or nota1 > 10:
#       print(f'''ERRO! A nota {nota1} é inválida. A nota deve ser MAIOR IGUAL À 0 ou 
#             MENOR IGUAL À 10"\n Tente novamente:''')
#       nota1 = float(input("nota1:"))
   
#    nota2 = float(input("Digite a 2ª nota:"))
#    while  nota2 < 0 or nota2 > 10:
#       print(f'''ERRO! A nota {nota2} é inválida. A nota deve ser MAIOR IGUAL À 0 ou 
#             MENOR IGUAL À 10"\n Tente novamente:''')
#       nota2 = float(input("nota2:"))

#    media = nota1 + nota2/ 2

#    ficha.append([nome, [nota1, nota2], media])
   
#    p = str(input("Deseja continuar ? S/N:")).upper().strip()[0]
#    if p  == "N":
#     break



# print('-'*15,'BOLETIM','-'*15)



# print('  Aluno:          Média:       1ª Nota:    2ª Nota:')
# for aluno in ficha:
#    print(f'{aluno[0]:>8} {aluno[2]:>13.1f} {aluno[1][0]:>14} {aluno[1][1]:>14}')

  


#91º (89º)


'''
Faça um programa que leia nome e média de um aluno, guardando também a situação em um dicionário. 
No final, mostre o conteúdo da estrutura na tela.
'''


# aluno = dict()
# lista = []
# l = 0

# while l != "N":
#    aluno['Nome'] = str(input(f"Digite o nome do {l + 1}º aluno: ")).capitalize().strip()
#    aluno['Média'] = float(input(f"Digite a  media de {l + 1 }º:").strip())
#    l += 1 
  
#    if aluno['Média'] >= 7:
#       aluno['Situação'] = 'APROVADO(a)'
#    elif 5 <= aluno ['Média'] < 7:
#       aluno['Situação'] = 'Recuperação'
#    else:
#       aluno['Situação'] = 'Reprovado(a)'

#    lista.append(aluno.copy())
   
#    p = str(input("Deseja continuar ? S/N:")).strip().upper()[0]
#    if p == 'N':
#       break

# print("-"*15, 'BOLETIM', '-'*15)

# primeira_linha = True

# for e in lista:
#    if primeira_linha:  
#       for k in e.keys():
#          print(f'{k:<28}', end = '')
#       print()   
#       primeira_linha = False
#       print()
#    for v in e.values():  
#        print(f'{v:<28}', end = '')
#    print()    



#92° (90°)


'''
Crie um programa onde 4 jogadores joguem um dado e tenham resultados aleatórios. 
Guarde esses resultados em um dicionário em Python. 
No final, coloque esse dicionário em ordem, sabendo que o vencedor tirou o maior número no dado.
'''


# from random import randint
# from time import sleep
# from operator import itemgetter

# jogo =  {'1º jogador': randint(1,6),
#          '2º jogador': randint(1,6),
#          '3º jogador': randint(1,6),
#          '4º jogador': randint(1,6)}

# ranking = dict()


# print('Valores sorteados:') 
# print('-='*13)
# print() 

# for k, v in jogo.items():
#     print(f'{k} tirou {v} no dado.')
#     sleep(1)

# ranking = sorted(jogo.items(), key = itemgetter(1),reverse = True)
# print('-='*13)
# print()
# print(' ==RANKING DOS JOGADORES== ')
# print()

# for i, v in enumerate(ranking):
#     print(f'{i+1}º lugar: {v[0]} com {v[1]}')
#     sleep(1) 

# print('-='*13)



#93° (91°)


'''
Crie um programa que leia nome, ano de nascimento e carteira de trabalho e cadastre-o (com idade) em um dicionário. 
Se por acaso a CTPS for diferente de ZERO, o dicionário receberá também o ano de contratação e o salário. 
Calcule e acrescente, além da idade, com quantos anos a pessoa vai se aposentar.
'''

# from datetime import datetime

# c = 0


# while True:
#     ct = {}
#     ct['NOME'] = str(input(f"Qual o nome do {c + 1 }º funcionário:")).capitalize().strip()
#     ct['ANO DE NASCIMENTO'] = int(input(f"Digite o ano de nascimento do(a) {ct['NOME']}:"))
#     ct['CTPS'] = int(input(f"Digite Nº da carteira de trabalho do(a) {ct['NOME']}:"))
#     c += 1
   
#     ano_atual = datetime.now().year
#     idade_atual = ano_atual - ct['ANO DE NASCIMENTO']
#     ct['IDADE ATUAL'] = idade_atual
    
#     if ct != 0:
#         ct['ANO DE CONTRATAÇÃO'] = int(input(f"Digite o ano de contratação do(a) {ct['NOME']}:"))
#         ct['SALÁRIO'] = float(input('Digite quanto voçê recebe de salário R$:'))
    
#     idade_aposentadoria = 65 - idade_atual
#     ct['ANOS RESTANTES PARA SE APOSENTAR'] = idade_aposentadoria    
     

#     p = str(input("Voçê deseja continuar ? S/N:")).upper().strip()[0]
#     if p == 'N':
#         break
   


# print('-='*15,'LISTA','=-'*15)

# for k, v in ct.items():
#     print(f' - {k} tem o valor  - {v}')



#94° (92°)



'''
Crie um programa que gerencie o aproveitamento de um jogador de futebol. 
O programa vai ler o nome do jogador e quantas partidas ele jogou. 
Depois vai ler a quantidade de gols feitos em cada partida. 
No final, tudo isso será guardado em um dicionário, incluindo o total de gols feitos durante o campeonato.'''


# jogador = dict()
# partidas = []


# jogador['nome'] = str(input('Qual o nome do jogador?:')).capitalize().strip()
# tot = int(input(f'Quantas partidas o jogador {jogador['nome']} jogou?:'))


# for c in range(0,tot):
#    partidas.append(int(input(f"Quantos gols {jogador['nome']} na {c + 1 }° partida:")))
#    c += 1 

# jogador['gols'] = partidas[:]

# jogador ['total'] = sum(partidas)

# print('-='*25)
# print(jogador)
# print('-='*25)

# for k, v in jogador.items():
#    print(f'O campo {k} tem o valor --> {v}')
# print('-='*25)


# print(f'O jogador {jogador['nome']} jogou {len(jogador['gols'])} partidas.')

# for i, v in enumerate(jogador['gols']):
#    print(f'      => Na partida {i + 1 }, fez {v} gols')
# print(f'Foi um total de {jogador['total']} gols')



#95º (93º)


'''
Crie um programa que leia nome, sexo e idade de várias pessoas, 
guardando os dados de cada pessoa em um dicionário 
e todos os dicionários em uma lista. 
No final, mostre: 
A) Quantas pessoas foram cadastradas ok
B) A média de idade ok
C) Uma lista com as mulheres ok
D) Uma lista de pessoas com idade acima da média
'''

# pessoa = dict()
# lista_mulheres = []
# lista_acima_média = []

# contagem = 0 
# soma_das_idades = 0 


# while True:
#    pessoa.clear
#    pessoa['NOME'] = str(input(f'Digite o nome da {contagem + 1 }º pessoa --> ')).capitalize().strip()
   
#    while True:
#      pessoa['SEXO'] = str(input(f'Qual o SEXO do(a) {pessoa['NOME']} MASCULINO/FEMININO? --> ')).upper().strip()[0]
#      if pessoa['SEXO'] in 'MF':
#        break
#      print('ERRO! POR FAVOR, DIGITE APENAS M OU F.')
     
#    pessoa['IDADE'] = int(input(f'Qual a idade do(a) {pessoa['NOME']}? --> '))
    
#    contagem += 1 
    
#    if pessoa['SEXO'] == 'F':
#       lista_mulheres.append(pessoa['NOME'])

    
#    soma_das_idades += pessoa['IDADE'] 
#    média_das_idades = soma_das_idades / contagem


#    if pessoa['IDADE'] > média_das_idades:
#       lista_acima_média.append(pessoa['IDADE'])

#    while True:
#       p = str(input("Deseja continuar ? S/N --> ")).upper().strip()[0]
#       if p in 'SN':
#        break
#       print('ERRO! Responda apenas S ou N.')
#    if p == 'N':
#        break

# print(contagem)  
# print(soma_das_idades)
# print(média_das_idades)
# print(lista_mulheres)
# print(lista_acima_média)


# #                              ou
# #                          guanabara:


# pessoa = dict()
# galera = list()
# soma = média = 0 
# while True:
#     pessoa.clear()
#     pessoa['nome'] = str(input('Nome: '))

#     while True:
#         pessoa['sexo'] = str(input('sexo: [M/F] ')).upper()[0]
#         if pessoa ['sexo'] in 'MF':
#              break
#         print('ERRO! Por favor, digite apenas M ou F.')
    
#     pessoa['idade'] = int(input('Idade:'))
#     soma += pessoa['idade']
    
#     galera.append(pessoa.copy())
    
    
#     while True:
#         resp = str(input('Quer continuar? S/N:')).upper().strip()[0]
#         if resp in 'SN':
#             break
#         print("ERRO, Responda S ou N.")
#     if resp == 'N':
#         break

# print('-='*30)
# print(f'A) Ao todo temos {len(galera)} pessoas cadastradas')

# média = soma / len(galera)

# print(f'B) A média de idade é de {média:5.2f} anos. ')

# print(f'C) As mulhres cadastradas foram --> ', end = '')
# for p in galera:
#     if p['sexo'] in 'Ff':
#         print(f' {p['nome']},', end = '')

# print()

# #Essa parte de refere as idades que estão acima da média.

# print(f'D) Lista das pessoas que estão acima da média: ')
# for p in galera:
#   if p['idade'] >= média:
#     print('         ')
#     for k, v in p. items():
#         print(f'{k} = {v};', end = '')
#     print()
# print('<<ENCERRADO>>')



#96º (97º)


'''Crie um programa que gerencie o aproveitamento de um jogador de futebol. 
O programa vai ler o nome do jogador e quantas partidas ele jogou. 
Depois vai ler a quantidade de gols feitos em cada partida. 
No final, tudo isso será guardado em um dicionário, incluindo o total de gols feitos durante o campeonato. 
 
Aprimore o desafio 93 para que ele funcione com vários jogadores, 
incluindo um sistema de visualização de detalhes do aproveitamento de cada jogador.
'''


# jogador = {}
# time = []
# partidas = []

# while True:
     
#    jogador.clear()
#    jogador['nome'] = str(input('Qual o nome do jogador?:')).capitalize().strip()
#    tot = int(input(f'Quantas partidas o jogador {jogador['nome']} jogou?:'))
#    partidas.clear()


#    for c in range(0,tot):
#       partidas.append(int(input(f"Quantos gols {jogador['nome']} na {c + 1 }° partida:")))
      
  
#    jogador['gols'] = partidas[:]
#    jogador['total'] = sum(partidas)
#    time.append(jogador.copy())
   
#    while True:
#       p = str(input("Deseja continuar ? S/N:")).upper().strip()[0]
#       if p in 'SN':
#          break
#       print('ERRO! Responda apenas S ou N.')
#    if p == 'N':
#       break

# print('-='*40)
# print('cod', end ='')
# for i in jogador.keys():
#    print(f' {i:<20}',end= "")
# print()
# print('-'*60)
# for k, v in enumerate(time):
#     print(f'{k + 1:>4}º', end = '')
#     for d in v.values():
#          print(f' {str(d):<20}', end='')
#     print()
# print('-='*40)

# while True:
#    busca = int(input('Mostrar dados de qual  jogador? (999 para parar):'))
#    if busca == 999:
#       break
#    if busca >= len(time):
#       print(f'Erro! Não existe jogador com código {busca}.')
#    else:
#        print(f'-- Levantamento do jogador --> {time[busca]["nome"]}:')
#        for i, g in enumerate(time[busca]['gols']):
#           print(f'   No jogo {i+1} fez {g} gols')
#    print('_'*40)
# print('<< VOLTE SEMPRE >>')


#97º (95º)


'''
Faça um programa que tenha uma função chamada área(), 
que receba as dimensões de um terreno retangular (largura e comprimento) 
e mostre a área do terreno.
'''

#Converte a entrada do usuário em números inteiros.


#O principal, que é o programa, se encontra abaixo.
# l = int(input('Digite o valor da LARGURA DO TERRENO:'))
# c = int(input('Digite o valor do COMPRIMENTO DO TERRENO:')) 

# def d():
#    a = l * c

# #  Abaixo fica toda parte 'imprimida' do programa.    
#    print('-='*10)
#    print()
#    print('A área do terreno é de--> ', end ='')
#    print(f'{a} Metros')
#    print()
#    print('-='*10)

# d()

#                          ou
#                      guanabara


# def área(larg, comp):
#    a = larg * comp
#    print(f'A área do terreno {larg} x {comp} é de {a}m²')


# # Programa principal
# print('Controle de Terrenos.')
# print('-'*20)
# l = float(input('LARGURA (m):'))
# c = float(input('COMPRIMENTO (m):'))
# área(l, c)



#98º (96º)


'''
Faça um programa que tenha uma função chamada escreva(),
que receba um texto qualquer como parâmetro 
e mostre uma mensagem com tamanho adaptável. 
Ex:escreva(''Olá, Mundo!'') Saída: ~~~~~~~~~                 
                                 Olá, Mundo! 
'''


# def escreva(msg):
#     tam = len(msg) 
#     print('-='*tam)
#     print(f'    {msg}')
#     print('-='*tam)


# mensagem = str(input('Digite uma frase:')).capitalize().strip()
# mensagem2 = str(input('Digite uma frase:')).capitalize().strip()
# #Programa Principal
# escreva(mensagem)
# escreva(mensagem2)


#99º (97º)


'''
 Faça um programa que tenha uma função chamada contador(), 
 que receba três parâmetros: início, fim e passo. 
 Seu programa tem que realizar três contagens através da função criada:
 a) de 1 até 10, de 1 em 1 
 b) de 10 até 0, de 2 em 2
 c) uma contagem personalizada
'''


# from time import sleep


# def contador(i, f, p):
#     print('-='*20)
#     print(f'Contagem de {i} até {f} de {p} em {p}:')
#     sleep(2.5)

#     if p < 0:
#       p *= -1
#     if p == 0:
#        p = 1   

#     if i < f:
#       cont = i
#       while cont <= f:
#         print(f'{cont}', end = ' -> ', flush = True)
#         sleep(0.5)
#         cont += p
#       print('FIM!')
      
#     else:
#       cont = i
#       while  cont >= f:
#           print(f'{cont} ', end = ' -> ', flush = True)
#           sleep(0.5)
#           cont -= p
#       print('FIM') 
      


# contador(1, 10, 1)
# sleep(1)
# contador(10, 0, 2)
# print('-='*20)
# print('Agora é sua vez de personalizar a contagem!')

# ini = int(input('Início: '))
# fim = int(input('Fim:    '))
# pas = int(input('Passo:  '))

# while True:
#    if pas == 0:
#       print('ERRO. Tente novamente')
#       pas = int(input('Digite novamente o valor do "passo":'))
#    if pas != 0:
#       break

# contador(ini, fim, pas)

# i = int(input('Digite um valor inical:'))
# f = int(input('Até que número voçê deseja que esta lista pare?: '))
# p = int(input('Qual o passo que voçê deseja ?'))


#100º (98º)


'''
Faça um programa que tenha uma função chamada maior(), 
que receba vários parâmetros com valores inteiros. 
Seu programa tem que analisar todos os valores 
e dizer qual deles é o maior.'''

# from time import sleep

# def maior(* num):
#     cont = maior = 0
#     print('\nAnalisando os valores passados...')
#     for valor in num:
#         print(f'{valor}', end = ' ', flush = True)
#         sleep(0.3)
       
#         if cont == 0:
#             maior = valor 
#         else:
#             if valor > maior:
#                 maior = valor
#         cont += 1
#     print(f'Foram informados {cont} valores ao todo.')
#     print('-='*20)
#     print(f'O maior valor informado foi {maior}')    


# #Programa principal
# maior(1,3,4,5,6,7)
# maior(3,4,11,22)


#101º (99º)


'''
Faça um programa que tenha uma lista chamada números 
e duas funções chamadas sorteia() e somaPar(). 
A primeira função vai sortear 5 números e vai colocá-los dentro da lista 
e a segunda função vai mostrar a soma entre todos os valores 
pares sorteados pela função anterior.'''

# from random import randint
# from time import sleep

# def sorteia(lista):

#    print('Sorteando 5 valores da lista:', end = '')
#    for cont in range (5):
#       n = randint(1,5)
#       lista.append(n)
#       print(f'{n}', end = ' -> ', flush = True)
#       sleep(0.5)
      
      
#    print('Pronto')


# def somaPar(lista):
#    soma = 0
#    for valor in lista:
#       if valor % 2 == 0:
#         soma += valor
           
#    print(f'Somando os valores pares de {lista}, temos {soma}')


      

# numeros = []

# print('-='*30)
# sorteia(numeros)
# print('-='*30)
# somaPar(numeros)


#102º (100º)


'''
Crie um programa que tenha uma função chamada voto() 
que vai receber como parâmetro o ano de nascimento de uma pessoa, 
retornando um valor literal indicando se uma pessoa tem voto NEGADO, 
OPCIONAL e OBRIGATÓRIO nas eleições.
'''


# from datetime import datetime


# def voto (ano):
#     if ano < 16:
#         print('Voto NEGADO. Idade mínima 16 anos')
#     elif ano >= 16 and ano < 18 and ano >= 70:
#         print('seu voto é OPICIONAL')
#     elif ano >= 18 and ano < 70:
#         print('seu voto é OBRIGATÓRIO.')
#     elif ano >= 70:
#         print('seu voto é OPCIONAL.')
    

# ano_nascimento = int(input('Digite o ano do seu NASCIMENTO:'))
# ano_atual = datetime.now().year
# idade_atual = ano_atual - ano_nascimento

# print(f'sua idade é de {idade_atual} anos, portanto', end = ' ')

# voto(idade_atual)


#103º (101º)

'''
Crie um programa que tenha uma função fatorial() 
que receba dois parâmetros: o primeiro que indique o número a calcular 
e outro chamado show, que será um valor lógico (opcional) indicando 
se será mostrado ou não na tela o processo de cálculo do fatorial.
'''

# def fatorial(n, show = False):
#    '''
#    -> Calcula o fatorial de um número.
#    :param n: O número a ser calculado.
#    :param show: (opcional) MOSTRAR ou NÃO a conta.
#    :return: O valor do fatorial de um número n.
#    ''' 
#    f = 1
#    for c in range(n, 0, -1):
#         if show:
#             print(c, end = '')
#             if c > 1:
#                print(' X ', end = '')
#             else:
#                print(' = ', end = '')
#         f *= c
#    return f 

         
#  # Programa principal   
# print(fatorial(5, show = False))    
# print(fatorial(5, show = True)) 
# help(fatorial)


#104º (102º)

'''
Faça um programa que tenha uma função chamada ficha(), 
que receba dois parâmetros opcionais: 
o nome de um jogador e quantos gols ele marcou. 
O programa deverá ser capaz de mostrar a ficha do jogador, 
mesmo que algum dado não tenha sido informado corretamente.'''



# def ficha(jog = '<Desconhecido>', gol = 0 ):
#     print(f'O jogador {jog} fez {gol} gol(s) no campeonato.')

# #Programa principal

# n = str(input('Nome do Jogador:'))
# g = str(input('Número de Gols:'))

# if g.isnumeric():
#     g = int(g)
# else:
#     g = 0

# if n.strip() == '':
#     ficha(gol = g)
# else:
#     ficha(n, g )


#105º (103º)

'''
Crie um programa que tenha a função leiaInt(), 
que vai funcionar de forma semelhante 'a função input() do Python, 
só que fazendo a validação para aceitar apenas um valor numérico. 
Ex: n = leiaInt('Digite um n: ')
'''


# def leiaInt(msg):
#     ok = False
#     valor = 0
#     while True:
#         n = str(input(msg))
#         if n.isnumeric():
#             valor = int(n)    
#             ok = True
#         else:
#             print('ERRO! Digite um número inteiro válido.')
#         if ok:
#             break
#     return valor
# n = leiaInt('Digite um número:')
# print(f'Voçê acabou de digitar o número {n}')


#106º (104º)


'''
Faça um programa que tenha uma função notas() 
que pode receber várias notas de alunos e 
vai retornar um dicionário com as seguintes informações:

– Quantidade de notas 
– A maior nota                                                             
– A menor nota
– A média da turma      
– A situação (opcional)
'''

#Programa principal


# def notas(*n, sit = False):
#     '''
#     -> Função para analisar notas e situações de vários alunos.
#     :param n: uma ou mais notas dos alubos (aceita várias)
#     :param sit: valor opcional, indicando se deve ou não adicionar a situação
#     :return: dicionário com várias informações sobre a situação da turma.
#     '''
#     r = dict()
#     r['total'] = len(n)
#     r['maior'] = max(n)
#     r['menor'] = min(n)
#     r['média'] = sum(n) / len(n) 
#     if sit:
#         if r['média'] >= 7:
#             r['situação'] = 'BOA'
#         elif r['média'] >=5:
#             r['situação'] = 'RAZOÁVEL'
#         else:
#             r['situação'] = 'RUIM' 
        
#     return r 

# resp = notas(9, 10, 5.5, 2.5, 9, 8.5, sit = True)
# print(resp)
# help(notas)


#107º (105º)


'''
Faça um mini-sistema que utilize o Interactive Help do Python. 
O usuário vai digitar o comando e o manual vai aparecer. 
Quando o usuário digitar a palavra ‘FIM’, o programa se encerrará. 
Importante: use cores.
'''

# def ajuda(com):
#    help(com)

# def título(msg, cor=0):
#    tamanho = len(msg) +4
#    print('~' * tamanho)
#    print(f'  {msg}')
#    print('~' * tamanho)


# #Programa principal
# comando = ''
# while True:
#     título('SISTEMA DE AJUDA PyHELP')
#     comando = str(input('Função ou Biblioteca>'))
#     if comando.upper() == 'FIM':
#       break
#     else:
#        ajuda(comando)

# título('Até logo')


#108º, 109º, 110º, 111º, 112º (106º, 107º, 108º, 109º,110º)


''' 108º (106º)
Crie um módulo chamado moeda.py que tenha as funções incorporadas 
aumentar(), 
diminuir(), 
dobro() e 
metade(). 
Faça também um programa que importe esse módulo e use algumas dessas funções.
'''

''' 109º (107º)
 Adapte o código do desafio 107, 
 criando uma função adicional chamada moeda() 
 que consiga mostrar os números como um valor monetário formatado.
'''

''' 110º (108º)
 Adicione o módulo moeda.py criado nos desafios anteriores, 
 uma função chamada resumo(), 
 que mostre na tela algumas informações geradas pelas funções que 
 já temos no módulo criado até aqui.
'''

''' 111º (109º)
 Crie um pacote chamado utilidadesCeV que tenha dois módulos internos chamados moeda e dado. 
 Transfira todas as funções utilizadas nos desafios 107, 108 e 109 para o primeiro pacote e mantenha tudo funcionando.
'''

''' 112ª (110ª)
Dentro do pacote utilidadesCeV que criamos no desafio 111, 
temos um módulo chamado dado. 
Crie uma função chamada leiaDinheiro() 
que seja capaz de funcionar como a função imputa(), 
mas com uma validação de dados para aceitar apenas 
valores que seja monetários.
'''


#---------------------------------------------------------------------------------------------------------------------

# from moeda import resumo, aumentar, diminuir, dobro, metade

#valor = float(input('Digite o valor --> R$ '))
#print(f'O valor de {valor} + 10% é --> R$ {aumentar(valor)}')
# print(f'O valor de {valor} - 10% é --> R$ {diminuir(valor)}')
# print(f'O dobro do valor {valor}, é  --> R$ {dobro(valor)}')
# print(f'A  metade do valor {valor}, é --> R$ {metade(valor)}')
# print()
# print('FIM')
# print()

# from utilidadesCeV.moeda import resumo 
# from utilidadesCeV.dado import leiaDinheiro

# valor = leiaDinheiro("\033[1;4;34mDigite o preço:\033[m ")
# # valor = int(input('Digite um valor'))
# resumo(valor)


#============================================================


# 113º (111º)
'''
Reescreva a função leiaInt() que fizemos no desafio 104, 
incluindo agora a possibilidade da digitação de um número 
de tipo inválido. 
Aproveite e crie também uma função leiaFloat() com a mesma 
funcionalidade.
'''


# def leiaInt(msg):
#     while True:
#         try:
#             n = int(input(msg))
        
#         except (ValueError, TypeError):
#             print('\033[1;31mERRO! Por favor, digite um número inteiro válido.\033[m')
#             continue
#         except (KeyboardInterrupt):
#             print('\nEntrada de dados interrompida pelo usuário.')
#             break 
#         else:
#             return n
        
# def leiaFloat(msg):
#     while True:
#         try:
#             n = float(input(msg))
        
#         except (ValueError, TypeError):
#             print('\033[1;31mERRO! Por favor, digite um número inteiro válido.\033[m')
#             continue
#         except (KeyboardInterrupt):
#             print('\nEntrada de dados interrompida pelo usuário.')
#             break 
#         else:
#             return n

# n1 = leiaInt('\033[1;32mDigite um valor INTEIRO:\033[m')
# n2 = leiaFloat('\033[1;34mDigite um valor REAL:\033[m')
# print(f'O valor \033[1;32minteiro\033[m digitado foi \033[1;32m{n1}\033[m e o valor \033[1;31mreal\033[m digitado foi \033[1;31m{n2}\033[m')


#114º (112º)
'''
 Crie um código em Python que teste se 
 o site pudim está acessível pelo computador usado.
'''

# import urllib
# import urllib.request

# try:
#     site = urllib.request.urlopen('http://www.pudim.com.br')
# except urllib.error.URLError:
#     print('O site Pudi não está funcionando')
#     print('Deu erro')
# else:
#     print('\033[1;4;32mTudo OK\033[m')
#     print(site.read())


#115º (113º)


'''
Vamos criar um menu em Python, usando modularização.
 '''
# from lib.arquivo import * 
# from lib.interface import *
# from time import sleep

# arq = 'cursoemvideo.txt'
# if not arquivoExiste(arq):
#       criarArquivo(arq)

# while True:
#    resposta = menu(['PESSOAS CADASTRADAS', 'CADASTRAR PESSOAS', 'SAIR DO SISTEMA'])

#    if resposta == 1:
#       # opção para ler conteúdos de um arquivo!
#       lerArquivo(arq)
#    elif resposta == 2:
#       cabeçalho('NOVO CADASTRO')
#       nome = str(input('Nome:')).capitalize().strip()
#       idade = leiaInt('Idade:')
#       cadastrar(arq, nome, idade)
#    elif resposta == 3:
      
#       cabeçalho('SAINDO DO SISTEMA... ATÉ LOGO')
#       break
#    else:
#       print('ERRO! Digite uma opção válida')
#    sleep(1)





