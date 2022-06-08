
Declarei algumas variáveis no qual vão ser auto completadas quando o usuário digitar o CEP de sua residência.

Vinculei um evento na variável "input CEP" chamada "blur". Assim que o usuários sair do campo CEP vai ser feito a consulta no sistema VIA CEP. 

A primeira função é recuperar o valor digitado no campo CEP pelo usuário.

Seguindo criei uma variável chamada "script" depois atribui o atributo src com o link do VIA CEP, que é onde vai ser feito a consultado do CEP digitado pelo usuário

Após esse processo inclui essa tag no HTML

Ao final criei uma função chamada popularForm que vai receber as respostas das nossas "pergunta" no VIP CEP. 

Sendo assim ele atribui um valor "repostas" das "perguntas" feitas no processo anterior nas variáveis que foi criada no inicio do JS.
