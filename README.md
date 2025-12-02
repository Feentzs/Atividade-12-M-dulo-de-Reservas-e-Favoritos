# BackEndLivraria



Este projeto tem como objetivo desenvolver um back-end completo para gerenciamento de uma livraria, utilizando Node.js, Express e MariaDB.
A aplicação abrange desde a configuração inicial do servidor até a criação de rotas, controladores, conexão com o banco de dados e organização modular do código.

Primeira parte do projeto

Nesta primeira etapa, o foco é configurar o ambiente e executar o servidor básico.

npm init -y
npm install express mysql2 body-parser cors
node server.js

Segunda parte

Após testar o servidor inicial, a estrutura do projeto será reorganizada para melhor organização do código, separando responsabilidades entre configuração, controle e rotas.

projeto-backend
 ┣ src
 ┃ ┣ config
 ┃ ┃ ┗ db.js                ← conexão com o banco MariaDB
 ┃ ┣ controllers
 ┃ ┃ ┗ usuarios.controller.js  ← lógica das rotas e regras de negócio
 ┃ ┣ routes
 ┃ ┃ ┗ usuarios.routes.js   ← define os endpoints da API
 ┃ ┗ server.js              ← ponto de entrada da aplicação
 ┗ ds.sql                   ← script SQL com criação do banco e da tabela
