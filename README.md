# ProvaMolicaIT

Prezados, conforme o solitado no desafio este é um exemplo de um projeto de cadastro de pessoas e de seus contatos

Para iniciar a aplicação é necessaria:

  * Node.js
  * Angular.js 14 
  * Java jdk 11
  * Docker (caso queira rodar o projeto utilizando o banco de dados Postgrees)
  * Dbeaver
  
Instalada as dependências do projeto será necessario:

  * Executar o comando ``npm install`` na pasta do front-end afim de que seja aderido ao projeto o ``nodeModules``
  * Em seguida no terminal executar o comando ``npm start``

No back-end devemos primeramente:

  * Executar o comando ``docker-compose up`` dentro do diretório aonde esta o ``docker-compose.yaml``
  * Depois inicializar a aplicação do back-end 
  * Seguido estes passos poderemos conectar ao banco de dados da aplicação utilizando a ferramenta Dbeaver com os respectivos usuário e senha que estao contidos no arquivo do docker compose 
  e por fim visualizar a aplicação digitando no browser a url: ``localhost:4200``
