# GoBarber API

API REST de uma aplicação para gerenciar serviços de barbearia.
Parte do bootcamp GoStack da Rocketseat

A aplicação permite com que usuários registrados façam agendamentos com provedores de serviço cadastrados no app.

## Tecnologias utilizadas

Esta API utiliza node.js com typescript para estabelecer o servidor.
Foi utilizado o Express para facilitar a criação das rotas

Também foram utilizados os seguintes pacotes:

- bcryptjs: para encriptação de senha;
- jsonwebtoken: para geração do token de autenticação;
- typeorm: para estabelecer as interações com o banco de dados postgres;
- mongodb: para gerenciar o envio de notificações e e-mails;
- redis: para criar dados em cache;
- multer: para envio de arquivos via formulário;

## Clonando o repositório

Para usar esta API em um servidor local:

- git clone:

- yarn para instalar as dependências;

- yarn test para rodar os testes;

- yarn dev:server para iniciar o servidor local na porta 3333;

- yarn build para gerar o arquivo de produção
