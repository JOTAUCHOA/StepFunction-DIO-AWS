# StepFunction-DIO-AWS-valida-saldo-positvoOuNegativo
Este é o meu primeiro stepfuction criado na AWS que foi entregue no desafio da DIO.

Pontos que achei interesante ao criação.

- Mesmo usando o stepfunction para criar elementos durante o flow, a criação de perfil para executar é super importante, algo que na permissões não colocadas, mesmo se seu usuário for um admin.
- O elemento de Publish, achei bem perculiar, pois provalmente como é um item personalizavel, tem que criar previamente antes de utilizar no Step Fuction da AWS.
- Quando estava criando o projeto, eu não percebi até buscar exemplos na internet, que necessáriamento não precisamos ficar presos aaba de recursos para criar um flow simples, como exemplo na validação de saldo em um sistema bancário, que no requisitária um elemento de Lambda para funcionar.

O projeto que eu fiz foi uma orquestração de sistema bancário utilizando AWS Step Functions com integração direta ao DynamoDB e SNS que vai mandar mensagem dizendo se há valor postivo ou negativo na conta.
