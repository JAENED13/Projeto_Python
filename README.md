# Projeto_Python
 Utilizando as Ferramentas do Github para Solucionar Algoritmos em Python
## Vamos receber dois dados diferentes do usuario e contactena-los #
info1 = input("Digite a primeira informação: ")
<br>
info2 = input("Digite a segunda informação: ")
<br>
info_concatenada = info1 + " " + info2
<br>
print ("As informações contactenadas são: "info_concatenada)

<b>

## Agora vamos solicitar uma string e um numero inteiro como entrada.Depois teremos que retornar a string repetida o numero de vezes informado. #
#### string = input("Digite uma string: ") ####
<b>
numero = int(input("Digite um número inteiro: ")) 
 
<b>
 
resultado = string * numero

<b>
 
print("A string repetida é:", resultado)

## Operação Matemática Simples. Vamos solicitar como entrada dois numeros e depois vamos realizar uma operacao simples entre eles.

num1 = int(input("Digite o primeiro número: "))

num2 = int(input("Digite o segundo número: "))

operacao = input("Digite a operação desejada (+, -, *, /): ")

if operacao == "+": <br>
    resultado_soma = num1 + num2 <br>
    print("O resultado da soma é:", resultado_soma) <br>
    
elif operacao == "-": <br>
    resultado_subtracao = num1 - num2 <br>
    print("O resultado da subtração é:", resultado_subtracao) <br>
    
elif operacao == "*": <br>
    resultado_multiplicacao = num1 * num2 <br>
    print("O resultado da multiplicação é:", resultado_multiplicacao) <br>
    
elif operacao == "/": <br>
    resultado_divisao = num1 / num <br>
    print("O resultado da divisão é:", resultado_divisao) <br>
else: <br>
    print("Operação inválida") <br>
