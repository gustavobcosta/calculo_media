# Calculador de média
Um programa que calcula a média de duas notas de um aluno(a).

***

### python 3.13.2 

```
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2

print("=== Sistema de notas do aluno ===")
n1 = float(input("Digite a primeira nota:"))
n2 = float(input("Digite a segunda nota:"))
media = calcular_media(n1, n2)

print(f"A média final é: {media:.2f}")

if media >= 7.0:
    print("status: Aprovado!")
else:
    print("Status: Reprovado!")




    PS C:\Users\GUSTAVOBERNARDOCOSTA\github> & "C:/Program Files/Python313/python.exe" c:/Users/GUSTAVOBERNARDOCOSTA/github/app.py
=== Sistema de notas do aluno ===
Digite a primeira nota:5
Digite a segunda nota:10
A média final é: 7.50
status: Aprovado!
    
```

### Gustavo Bernardo Costa
###### linkedin.com/in/gustavobernardo-/

