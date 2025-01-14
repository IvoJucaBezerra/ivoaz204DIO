# DIO204-ValidaCPF

Atividade de hands-on do bootcamp da DIO AZ-204: Criando um Microsserviço Serverless para Validação de CPF

Para realizar a atividade foi seguido os seguintes passos:

## Configuração do ambiente

Foi configurado um github codespace com .net 8, e extensões do Azure e do Azure Functions
Feito login na Azure pelo vsCode

## Projeto

Foi criado um projeto de exemplo de uma function simples do azure com um trigger http
Foi criado uma função para validar um CPF
Foi alterado a function para receber na requisição POST um cpf
O codigo então verifica se o cpf é valido e da uma resposta se é ou não é valido

![alt text]({05215311-FC26-4A35-A417-F56B630B61F3}.png)

![alt text]({F7BB438A-5CDA-401E-A565-2BEA58A4B3B1}.png)

## Deploy na Azure

Para fazer o deplou na Azure primeiro foi preciso criar um FunctionApp
Depois foi feito o deploy com o auxilio do vsCode

![alt text]({D60234FC-9340-4C11-B76E-1F3360CC6D99}.png)

## Consumo do endpoint

Como foi deixado que o endpoint era de acesso anonimo, não precisou adicionar nada na chamada

![alt text](endpointaz.png)
![alt text](endpointaz2.png)
