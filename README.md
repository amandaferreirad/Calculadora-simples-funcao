def soma(num1,num2):
    return num1+num2

def subtracao(num1,num2):
    return num1-num2

def multiplicacao(num1,num2):
    return num1*num2

def divisao(num1,num2):
    if num2==0:
        return "Não tem como dividir por 0"
    return num1/num2

num1=float(input("Digite o primeiro número:"))
num2=float(input("Digite o segundo número:"))
operacao=(input("Escolha uma operação:+,-,*,/"))

if operacao == "+":
    resultado=soma(num1,num2)

elif operacao== "-":
    resultado=subtracao(num1,num2)

elif operacao=="*":
    resultado=multiplicacao(num1,num2)

elif operacao=="/":
    resultado=divisao(num1,num2)
