# IVO - DIO204-ValidaCPF

Atividade de hands-on do bootcamp da DIO AZ-204: Criando um Microsserviço Serverless para Validação de CPF

Este repositório contém a solução para a atividade de criação de um microsserviço Serverless utilizando o Azure Functions para validar CPF.

## Passos para realização da atividade

### 1. Configuração do Ambiente

- Foi configurado um **GitHub Codespace** com **.NET 8**.
- As extensões do **Azure** e **Azure Functions** foram instaladas no VS Code.
- Realizado login no **Azure** através do **VS Code**.

### 2. Criando o Projeto

- Criamos um projeto de exemplo de uma função simples do Azure com **trigger HTTP**.
- Foi criada uma função para **validar o CPF**.
- A função foi modificada para aceitar um **CPF** via requisição **POST**.
- O código então realiza a validação do CPF e retorna uma resposta indicando se o CPF é válido ou não.

### 3. Deploy na Azure

- Foi criado um **FunctionApp** na plataforma Azure.
- Realizado o deploy da função utilizando o **VS Code** com a extensão do Azure Functions.

### 4. Consumo do Endpoint

- O endpoint foi configurado para **acesso anônimo**, portanto, não foi necessário adicionar autenticação para realizar chamadas.
- O serviço pode ser acessado diretamente via requisição HTTP, enviando o CPF no corpo da requisição.

## Como testar a aplicação

1. Envie uma requisição **POST** para o endpoint do serviço com um CPF no corpo da requisição.
2. O serviço irá validar o CPF e retornar uma resposta indicando se ele é válido ou não.

---

Se precisar de mais detalhes sobre como rodar ou configurar o projeto, fique à vontade para abrir uma issue ou contribuir com melhorias.
