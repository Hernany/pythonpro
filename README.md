# pythonpro
Curso Python Pro | Anotações, códigos e testes

## Python Birds
1- Parâmetros de Função
```
def student(firstname, lastname, age):
...  return f'Dados do Aluno: {name} {lastname} - {age}'
...
>>> student('Hernany', 'Santos', 39)
'Dados do Aluno: Hernany Santos - 39'

 
def student(firstname, lastname, age=39):
...  return f'Dados do Aluno: {name} {lastname} - {age}'
...
>>> student('Hernany', 'Santos')
'Dados do Aluno: Hernany Santos - 39'


def student(firstname, lastname='Santos', age=39):
...  return f'Dados do Aluno: {name} {lastname} - {age}'
...
>>> student('Hernany', idade=38)
'Dados do Aluno: Hernany Santos - 38'


// A ordem  indiferente devido a passagem de parametros nomeados
def student(firstname, lastname='Santos', age=39):
...  return f'Dados do Aluno: {name} {lastname} - {age}'
...
>>> student('Hernany', idade=38, lastname='dos Santos')
'Dados do Aluno: Hernany dos Santos - 38'




```
