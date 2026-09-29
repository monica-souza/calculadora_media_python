# ***Calculadora de Média do Aluno***
---
### Este código consiste em uma calculadora, onde o aluno digita duas notas e o programa calcula a média, nos dizendo se ele está APROVADO ou REPROVADO.
***
## **Tecnologias utilizadas: Python 3.13**
---
## Como instalar e Executar: 
#### IDR de sua preferência ou compilador online 
***
### CÓDIGO:
````
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2

print("=== Sistema de Notas do Aluno ===")
n1 = float(input("Digite a primeira nota: "))
n2 = float(input("Digite a segunda nota: "))
media = calcular_media(n1, n2)
print(f"A média final é: {media:.2f}")

if media >= 7.0:
    print("Status: APROVADO!")
else:
    print("Status: REPROVADO.")
````
### EXECUÇÃO:
````
Digite a primeira nota: 10
Digite a segunda nota: 10
A média final é: 10.00
Status: APROVADO!
````
### Contato: 
Mônica de Souza Lima: [LinkedIn](https://www.linkedin.com/in/monica-souza-lima/)

