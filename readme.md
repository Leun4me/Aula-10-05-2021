# Projeto para entender como as branches funcionam 
 
## Branch master ou main
 
É a branch principal do repositorio, é a partir dela que nosso sitema sera entregue os clientes.
 
O 'git' usa o nome da branch como master o 'github'como main.
 
Para converter use ''git branch -M main'' depois que fizer o primeiro commit a partir do repositorio criado com o ''git init''
# manipulação de branch

Para listar use:
```
$ git branch --list
```

para excluir uma branch
```
$ git branch -d nome_da_branch
```
Para alterar o nome de uma branch
```
$ git branch -m nome_da_branch

