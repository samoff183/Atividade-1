# Atividade-1
Faça um Programa que mostre a mensagem "Alunos - PLP Unifavip 2022.2" na tela.


[ ]
print("Alunos - PLP Unifavip 2022.2")

Alunos - PLP Unifavip 2022.2
Faça um Programa que peça um número e então mostre a mensagem O número informado foi [número].


[ ]
numero = input("digite um numero:")
print(f"o numero que você escolheu foi: {numero}")
digite um numero:8
o numero que você escolheu foi: 8
Faça um Programa que peça dois números e mostre como resultado a soma.


[ ]
x = int(input("digite um numero:"))
y = int(input("digite mais um numero:"))
print(f"a soma dos numeros {x} e {y} é = {x + y}")
digite um numero:8
digite mais um numero:0
a soma dos numeros 8 e 0 é = 8
Faça um Programa que peça as 4 notas bimestrais e mostre a média.


[ ]
n = input("digite o nome do aluno: ")
x = float(input("digite a nota do primeiro bimestre:"))
y = float(input("digite a nota do segundo bimestre:"))
z = float(input("digite a nota do terceiro bimestre:"))
w = float(input("digite a nota do quarto bimestre:"))
print(f"o aluno {n} teve a media de {(x + y + z + w)/4}")
Faça um Programa que converta metros para centímetros.


[ ]
metros = float(input("Digite o valor em metros: "))
centimetros = metros * 100

print(f"{metros} metros equivalem a {centimetros} centímetros.")

Digite o valor em metros: 0
0.0 metros equivalem a 0.0 centímetros.
Faça um Programa que peça o raio de um círculo, calcule e mostre sua área.


[ ]
import math
raio = float(input("Digite o raio do círculo: "))
area = math.pi * (raio ** 2)
print(f"A área do círculo com raio {raio} é {area:.2f}")

Digite o raio do círculo: 7
A área do círculo com raio 7.0 é 153.94
Faça um Programa que calcule a área de um quadrado, em seguida mostre o dobro desta área para o usuário.


[ ]
x = float(input("digite o lado do quadrado: "))
print(f"a area do quadrado é = {x**2} e seu dobro é {x**2 * 2}")

digite o lado do quadrado: 9
a area do quadrado é = 81.0 e seu dobro é 162.0
Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês.


[ ]
x = float(input("quanto você ganha por hora? "))
y = float(input("quantas horas você trabalha por mês "))
print(f"você ganha R$ {x * y} por mês")
quanto você ganha por hora? 0
quantas horas você trabalha por mês 7
você ganha R$ 0.0 por mês
Faça um Programa que peça a temperatura em graus Fahrenheit, transforme e mostre a temperatura em graus Celsius.


[ ]
fahrenheit = float(input('escolha uma temperatura em fahrenheit: '))
celsius = 5 * ((fahrenheit-32) / 9)
print(f'{fahrenheit} fahrenheit em celsius é = {celsius}')

escolha uma temperatura em fahrenheit: 5
5.0 fahrenheit em celsius é = -15.0
Faça um Programa que peça a temperatura em graus Celsius, transforme e mostre em graus Fahrenheit


[ ]
celsius = float(input("Digite a temperatura em graus Celsius: "))
fahrenheit = (celsius * 9/5) + 32
print(f"A temperatura em Fahrenheit é: {fahrenheit:.2f}°F")

Faça um Programa que peça 2 números inteiros e um número real. Calcule e mostre: o produto do dobro do primeiro com metade do segundo. a soma do triplo do primeiro com o terceiro. o terceiro elevado ao cubo.


[ ]
x = int(input('digite um numero inteiro: '))
y = int(input('digite outro numero inteiro: '))
z = float(input('digite um numero real: '))
print(f'questão a = {(x * 2) * (y / 2)}')
print(f'questão b = {(x * 3) + (z)}')
print(f'questão c = {(z ** 3)}')
digite um numero inteiro: 9
digite outro numero inteiro: 4
digite um numero real: 5
questão a = 36.0
questão b = 32.0
questão c = 125.0
Tendo como dados de entrada a altura de uma pessoa, construa um programa que calcule seu peso ideal, usando a seguinte fórmula: (72.7*altura) - 58


[ ]
altura = float(input("Digite sua altura em metros: "))
x = (72.7 * altura) - 58
print(f"Seu peso ideal é: {x:.2f} kg")

Digite sua altura em metros: 6
Seu peso ideal é: 378.20 kg
tendo como dado de entrada a altura (h) de uma pessoa, construa um algoritmo que calcule seu peso ideal, utilizando as seguintes fórmulas: Para homens: (72.7h) - 58 Para mulheres: (62.1h) - 44.7


[ ]
altura = float(input("Digite sua altura em metros: "))
x = (72.7 * altura) - 58
y = (62.1 * altura) - 44.7
print(f"se você for homem seu peso ideal é: {x} kg")
print(f"se você for mulher seu peso ideal é: {y} kg")

Digite sua altura em metros: 7
se você for homem seu peso ideal é: 450.90000000000003 kg
se você for mulher seu peso ideal é: 390.0 kg
João Papo-de-Pescador, homem de bem, comprou um computador para controlar o rendimento diário de seu trabalho. Toda vez que ele traz um peso de peixes maior que o estabelecido pelo regulamento de pesca do estado de São Paulo (50 quilos) deve pagar uma multa de R$ 4,00 por quilo excedente. João precisa que você faça um programa que leia a variável peso (peso de peixes) e calcule o excesso. Gravar na variável excesso a quantidade de quilos além do limite e na variável multa o valor da multa que João deverá pagar. Imprima os dados do programa com as mensagens adequadas.


[ ]
peso = float(input("Digite o peso total dos peixes (em kg): "))
limite = 50.0
valor_multa_por_kg = 4.0
if peso > limite:
    excesso = peso - limite
    multa = excesso * valor_multa_por_kg
else:
    excesso = 0.0
    multa = 0.0
print("RELATÓRIO DE PESCA")
print(f"Peso informado: {peso} kg"})
print(f"Excesso de peso: {excesso kg}")
print(f"Multa a pagar: R$ {multa}")


Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês, sabendo-se que são descontados 11% para o Imposto de Renda, 8% para o INSS e 5% para o sindicato, faça um programa que nos dê: salário bruto. quanto pagou ao INSS. quanto pagou ao sindicato. o salário líquido. calcule os descontos e o salário líquido, conforme a tabela abaixo


[ ]

x = float(input("quanto você ganha por hora "))
y = float(input("quantas horas você trabalha por mês "))
z = (x * y)
print(f"o salário sem desconto é R${x * y}")
print(f"o salário com desconto do INSS é R${z - z * 0.01}")
print(f"o salário com desconto do Imposto de Renda é R${z - z * 0.11}")
print(f"o salário com desconto do sindicato é R${z - z * 0.05}")
print(f"o salário liquido é R${z - z * 0.17}")
quanto você ganha por hora 20
quantas horas você trabalha por mês 120
o salário sem desconto é R$2400.0
o salário com desconto do INSS é R$2376.0
o salário com desconto do Imposto de Renda é R$2136.0
o salário com desconto do sindicato é R$2280.0
o salário liquido é R$1992.0
Faça um programa para uma loja de tintas. O programa deverá pedir o tamanho em metros quadrados da área a ser pintada. Considere que a cobertura da tinta é de 1 litro para cada 3 metros quadrados e que a tinta é vendida em latas de 18 litros, que custam R$ 80,00. Informe ao usuário a quantidades de latas de tinta a serem compradas e o preço total.


[ ]
x = float(input("quantos metros quadrados serão pintados "))
ln = (x / 3)
l = (ln / 18)
print(f"a quantidade de latas será {l}")
print(f"o valor total será R${l * 80}")
Faça um Programa para uma loja de tintas. O programa deverá pedir o tamanho em metros quadrados da área a ser pintada. Considere que a cobertura da tinta é de 1 litro para cada 6 metros quadrados e que a tinta é vendida em latas de 18 litros, que custam R80,00ouemgalõesde3,6litros,quecustamR 25,00. Informe ao usuário as quantidades de tinta a serem compradas e os respectivos preços em 3 situações: comprar apenas latas de 18 litros; comprar apenas galões de 3,6 litros; misturar latas e galões, de forma que o desperdício de tinta seja menor. Acrescente 10% de folga e sempre arredonde os valores para cima, isto é, considere latas cheias.


[ ]
import math


area = float(input("Digite o tamanho da área a ser pintada (em m²): "))


ln = area / 6
ln *= 1.10


latas = math.ceil(ln / 18)
pl = latas * 80


galoes = math.ceil(ln / 3.6)
preco_galoes = galoes * 25


lm = math.floor(ln / 18)
restante = ln - (lm * 18)
gl = math.ceil(restante / 3.6)
pm = (lm * 80) + (gl * 25)

print("\nSituação 1: Apenas latas de 18L")
print(f"{latas} latas de 18L - Preço total: R$ {pl:.2f}")

print("\nSituação 2: Apenas galões de 3.6L")
print(f"{galoes} galões de 3.6L - Preço total: R$ {preco_galoes:.2f}")

print("\nSituação 3: Mistura de latas e galões")
print(f"{lm} latas de 18L e {gl} galões de 3.6L - Preço total: R$ {pm:.2f}")

Faça um programa que peça o tamanho de um arquivo para download (em MB) e a velocidade de um link de Internet (em Mbps), calcule e informe o tempo aproximado de download do arquivo usando este link (em minutos)


[ ]

tamanho = float(input("Digite o tamanho do arquivo (em MB): "))
velocidade = float(input("Digite a velocidade do link (em Mbps): "))


vm = velocidade / 8


ts = tamanho / vm
ts = ts / 60


print(f"O tempo aproximado de download é de {tempo_minutos:.2f} minutos.")

Crie um programa para preencher um vetor (lista) com números inteiros e solicitar um número do teclado. Pesquisar se esse número existe no vetor. Se existir, imprimir em qual posição do vetor (lista) foi digitado. Se não existir, imprimir mensagem que não existe.


[ ]

vetor = []

quantidade = int(input("Quantos números inteiros você quer inserir na lista? "))

for i in range(quantidade):
    num = int(input(f"Digite o {i+1}º número: "))
    vetor.append(num)


pesquisa = int(input("Digite um número para pesquisar na lista: "))


if pesquisa in vetor:

    posicao = vetor.index(pesquisa)
    print(f"O número {pesquisa} está na posição {posicao} da lista.")
else:
    print(f"O número {pesquisa} não existe na lista.")

Faça um programa que exiba na tela a quantidade de acertos de cada aluno em uma prova, e caso a nota seja igual ou maior que 60% da quantidade de questões exiba “Classificado”, se não “Desclassificado”. Para isso crie uma TUPLA que receba o cartão gabarito com as 20 questões, cada uma com cinco alternativas identificadas por A, B, C, D e E., Depois crie uma lista para cada Aluno e receba as 20 questões da prova dele e diga se o aluno está Classificado ou Desclassificado. Ao final, pergunte se o usuário deseja cadastrar outro aluno ou finalizar o programa.


[ ]
gabarito = (
    'A', 'B', 'C', 'D', 'E',
    'A', 'B', 'C', 'D', 'E',
    'A', 'B', 'C', 'D', 'E',
    'A', 'B', 'C', 'D', 'E'
)

while True:
    print("\n=== Cadastro de Aluno ===")
    nome = input("Nome do aluno: ")


    ra = []
    for i in range(20):
        resp = input(f"Digite a resposta da questão {i+1} (A, B, C, D ou E): ").strip().upper()
        while resp not in ['A','B','C','D','E']:
            resp = input(f"Resposta inválida! Digite novamente a questão {i+1} (A, B, C, D ou E): ").strip().upper()
        ra.append(resp)


    acertos = 0
    for i in range(20):
        if ra[i] == gabarito[i]:
            acertos += 1


    if acertos >= 0.6 * 20:
        status = "Classificado"
    else:
        status = "Desclassificado"

    print(f"\nAluno: {nome}")
    print(f"Acertos: {acertos} de 20")
    print(f"Situação: {status}")


    continuar = input("\nDeseja cadastrar outro aluno? (S/N): ").strip().upper()
    if continuar != 'S':
        print("\nPrograma finalizado.")
        break

Faça um programa que peça do usuário o nome de 6 cidades, depois de inseridas verifique se há nomes iguais e havendo peça para que sejam inseridos novamente, e também crie a opção do usuário concatenar dados ao nome da cidade. E por fim, exiba qual o nome de cidade mais extenso.


[ ]
cidades = []

i = 1
while len(cidades) < 6:
    cidade = input(f"Digite o nome da {i}ª cidade: ").strip()

    # verifica duplicado (sem considerar maiúsculas/minúsculas)
    while cidade.lower() in [c.lower() for c in cidades]:
        print("Cidade já inserida! Digite outra.")
        cidade = input(f"Digite o nome da {i}ª cidade: ").strip()

    # Pergunta se quer concatenar algo
    opcao = input("Deseja concatenar algum dado ao nome da cidade? (S/N): ").strip().upper()
    if opcao == 'S':
        concat = input("Digite o texto para concatenar: ").strip()
        cidade = cidade + concat  # concatenação

    cidades.append(cidade)
    i += 1

print("\n=== Lista Final de Cidades ===")
for idx, c in enumerate(cidades, start=1):
    print(f"{idx} - {c}")

# Encontrar a cidade mais extensa
ce = max(cidades, key=len)

print(f"\nA cidade com o nome mais extenso é: {ce} ({len(ce)} caracteres)")

Faça um Programa que verifique se uma letra digitada é vogal ou consoante. 23) Faça um programa para a leitura de duas notas parciais de um aluno. O programa deve calcular a média alcançada por aluno e apresentar: A mensagem "Aprovado", se a média alcançada for maior ou igual a sete; A mensagem "Reprovado", se a média for menor do que sete; A mensagem "Aprovado com Distinção", se a média for igual a dez.


[ ]
nota1 = float(input("Digite a 1ª nota: "))
nota2 = float(input("Digite a 2ª nota: "))

media = (nota1 + nota2) / 2

if media == 10:
    print("Aprovado com Distinção")
elif media >= 7:
    print("Aprovado")
else:
    print("Reprovado")

Faça um Programa que leia três palavras e mostre a maior palavra entre eles, além de apresentar quantos caracteres tem na palavra.


[ ]

p1 = input("Digite a 1ª palavra: ")
p2 = input("Digite a 2ª palavra: ")
p3 = input("Digite a 3ª palavra: ")

palavras = [p1, p2, p3]


maior = max(palavras, key=len)

print(f"\nA maior palavra é: {maior}")
print(f"Ela tem {len(maior)} caracteres.")

Faça um Programa que leia três números e mostre o maior e o menor deles.


[ ]

n1 = float(input("Digite o 1º número: "))
n2 = float(input("Digite o 2º número: "))
n3 = float(input("Digite o 3º número: "))

maior = max(n1, n2, n3)
menor = min(n1, n2, n3)

print(f"O maior número é: {maior}")
print(f"O menor número é: {menor}")

Faça um programa que pergunte o preço de três produtos e informe qual produto você deve comprar, sabendo que a decisão é sempre pelo mais barato.


[ ]

p1 = float(input("Digite o preço do 1º produto: R$ "))
p2 = float(input("Digite o preço do 2º produto: R$ "))
p3 = float(input("Digite o preço do 3º produto: R$ "))


if p1 <= p2 and p1 <= p3:
    mais_barato = "1º produto"
    preco = p1
elif p2 <= p1 and p2 <= p3:
    mais_barato = "2º produto"
    preco = p2
else:
    mais_barato = "3º produto"
    preco = p3


print(f"\nVocê deve comprar o {mais_barato}, que custa R$ {preco:.2f}.")

Faça um Programa que leia três números e mostre-os em ordem decrescente.


[ ]

n1 = float(input("Digite o 1º número: "))
n2 = float(input("Digite o 2º número: "))
n3 = float(input("Digite o 3º número: "))

numeros = [n1, n2, n3]

numeros.sort(reverse=True)

print("Números em ordem decrescente:", numeros)

Faça um Programa que pergunte em que turno você estuda. Peça para digitar M-matutino ou V-Vespertino ou N- Noturno. Imprima a mensagem "Bom Dia!", "Boa Tarde!" ou "Boa Noite!" ou "Valor Inválido!", conforme o caso.


[ ]

turno = input("Digite o turno que você estuda (M-matutino, V-vespertino, N-noturno): ").strip().upper()

if turno == 'M':
    print("Bom Dia!")
elif turno == 'V':
    print("Boa Tarde!")
elif turno == 'N':
    print("Boa Noite!")
else:
    print("Valor Inválido!")

As Organizações PLP LTDAresolveram dar um aumento de salário aos seus colaboradores e lhe contraram para desenvolver o programa que calculará os reajustes. O reajuste acontecerá segundo o seguinte critério, baseado no salário atual: salários até R280,00(incluindo):aumentode20saláriosentreR 280,00 e R700,00:aumentode15saláriosentreR 700,00 e R1500,00:aumentode10saláriosdeR 1500,00 em diante : aumento de 5% Após o aumento ser realizado, informe na tela: o salário antes do reajuste; o percentual de aumento aplicado; o valor do aumento; o novo salário, após o aumento.


[ ]

salario = float(input("Digite o salário atual: R$ "))

if salario <= 280:
    percentual = 20
elif salario <= 700:
    percentual = 15
elif salario <= 1500:
    percentual = 10
else:
    percentual = 5

valor_aumento = salario * (percentual / 100)
novo_salario = salario + valor_aumento

print("\n=== Reajuste Salarial ===")
print(f"Salário antes do reajuste: R$ {salario:.2f}")
print(f"Percentual de aumento aplicado: {percentual}%")
print(f"Valor do aumento: R$ {valor_aumento:.2f}")
print(f"Novo salário após o aumento: R$ {novo_salario:.2f}")

Faça um programa para o cálculo de uma folha de pagamento, sabendo que os descontos são do Imposto de Renda, que depende do salário bruto (conforme tabela abaixo) e 3% para o Sindicato e que o FGTS corresponde a 11% do Salário Bruto, mas não é descontado (é a empresa que deposita). O Salário Líquido corresponde ao Salário Bruto menos os descontos. O programa deverá pedir ao usuário o valor da sua hora e a quantidade de horas trabalhadas no mês. Desconto do IR: Salário Bruto até 900 (inclusive) - isento Salário Bruto até 1500 (inclusive) - desconto de 5% Salário Bruto até 2500 (inclusive) - desconto de 10% Salário Bruto acima de 2500 - desconto de 20% Imprima na tela as informações, dispostas conforme o exemplo abaixo. No exemplo o valor da hora é 5 e a quantidade de hora é 220.


[ ]
vh = float(input("Digite o valor da sua hora: R$ "))
ht = float(input("Digite a quantidade de horas trabalhadas no mês: "))

sb = vh * ht

if sb <= 900:
    ir = 0
elif sb <= 1500:
    ir = sb * 0.05
elif sb <= 2500:
    ir = sb * 0.10
else:
    ir = sb * 0.20

sindicato = sb * 0.03

fgts = sb * 0.11

td = ir + sindicato

sl = sb - td

print("\n=== Folha de Pagamento ===")
print(f"Salário Bruto: ({vh:.2f} * {ht}) : R$ {sb:.2f}")
print(f"(-) IR: R$ {ir:.2f}")
print(f"(-) Sindicato: R$ {sindicato:.2f}")
print(f"FGTS (11%): R$ {fgts:.2f}")
print(f"Total de descontos: R$ {td:.2f}")
print(f"Salário Líquido: R$ {sl:.2f}")

Faça um programa que faça 5 perguntas para uma pessoa sobre um crime. As perguntas são: "Telefonou para a vítima?" "Esteve no local do crime?" "Mora perto da vítima?" "Devia para a vítima?" "Já trabalhou com a vítima?" O programa deve no final emitir uma classificação sobre a participação da pessoa no crime. Se a pessoa responder positivamente a 2 questões ela deve ser classificada como "Suspeita", entre 3 e 4 como "Cúmplice" e 5 como "Assassino". Caso contrário, ele será classificado como "Inocente".


[ ]
perguntas = [
    "Telefonou para a vítima? (S/N): ",
    "Esteve no local do crime? (S/N): ",
    "Mora perto da vítima? (S/N): ",
    "Devia para a vítima? (S/N): ",
    "Já trabalhou com a vítima? (S/N): "
]

respostas_positivas = 0

for pergunta in perguntas:
    resposta = input(pergunta).strip().upper()
    while resposta not in ['S', 'N']:
        resposta = input("Resposta inválida! Digite S para Sim ou N para Não: ").strip().upper()
    if resposta == 'S':
        respostas_positivas += 1

if respostas_positivas == 2:
    classificacao = "Suspeita"
elif 3 <= respostas_positivas <= 4:
    classificacao = "Cúmplice"
elif respostas_positivas == 5:
    classificacao = "Assassino"
else:
    classificacao = "Inocente"

print(f"\nClassificação da pessoa: {classificacao}")

Faça um programa que cadastre o nome, a matrícula e duas notas de 13 alunos. Em seguida imprima a matrícula, o nome e a média de cada um deles.


[ ]

alunos = []

for i in range(1, 14):
    print(f"\n=== Cadastro do {i}º aluno ===")
    matricula = input("Digite a matrícula: ")
    nome = input("Digite o nome: ")
    nota1 = float(input("Digite a 1ª nota: "))
    nota2 = float(input("Digite a 2ª nota: "))
    media = (nota1 + nota2) / 2
    alunos.append({"matricula": matricula, "nome": nome, "media": media})

print("\n=== Médias dos Alunos ===")
for aluno in alunos:
    print(f"Matrícula: {aluno['matricula']}, Nome: {aluno['nome']}, Média: {aluno['media']:.2f}")

Faça um programa que cadastre o nome, a altura, o peso, o cpf e sexo de algumas pessoas. Com os dados cadastrados, em seguida localizar uma pessoas através do seu CPF e imprimir o seu IMC.


[ ]
pessoas = []

qtd = int(input("Quantas pessoas deseja cadastrar? "))

for i in range(1, qtd + 1):
    print(f"\n=== Cadastro da {i}ª pessoa ===")
    nome = input("Digite o nome: ")
    altura = float(input("Digite a altura (em metros): "))
    peso = float(input("Digite o peso (em kg): "))
    cpf = input("Digite o CPF: ")
    sexo = input("Digite o sexo (M/F): ").strip().upper()
    pessoas.append({"nome": nome, "altura": altura, "peso": peso, "cpf": cpf, "sexo": sexo})

cpf_busca = input("\nDigite o CPF da pessoa que deseja localizar: ")

encontrado = False
for pessoa in pessoas:
    if pessoa["cpf"] == cpf_busca:
        encontrado = True
        imc = pessoa["peso"] / (pessoa["altura"] ** 2)
        print(f"\nPessoa encontrada: {pessoa['nome']}")
        print(f"IMC: {imc:.2f}")
        break

if not encontrado:
    print("CPF não encontrado.")

