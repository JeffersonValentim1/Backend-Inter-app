<h1 align="center">
   --- APLICAÇÃO BACKEND CONSTRUINDA COM O BANCO INTER E DIO ---
</h1>

<p align="center">
  <img alt="Repository size" src="https://raw.githubusercontent.com/JeffersonValentim1/Backend-Inter-app/aca96e196f5fcb18dc244801e3fa9b8b1835469c/img/me.jpg">
</p>

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="INTER" title="#INTER" src="https://raw.githubusercontent.com/JeffersonValentim1/Backend-Inter-app/main/img/transition.jpg" width="400px">
</p>


## 💻 Sobre o Projeto

Esta API foi construída na Semana Inter. Uma semana ofertada pela Digital Innovation e o Banco Inter. Por meio da API é possível  cadastrar usuários, realizar o login, bem como fazer transações de valores por meio de uma chave pix gerada pela API. Na aplicação, o banco de dados utilizado é o Postgres

## 💡 Informações de como executar o projeto

```bash

  # Clonar todo o repositório ou em partes "backend-app" e "frontend-app"

  # Acessar a pasta do projeto

  ## Estando na pasta com projeto, abrir no console 
  
  # Rodar npm install ou yarn  

  # Backend-app, Rodar o comando para subir a base de dados para o seu docker -> docker-compose up 

  # Backend-app, Rodar o comando -> npm run dev ou yarn dev


```
## 💡 Como executar o projeto

```bash

  # Clonar o repositório do projeto backend-app

  # Acessar a pasta do projeto

  # Rodar npm install ou yarn

  # Rodar o comando para subir a base de dados para o seu docker -> docker-compose up 

  # Rodar npm run dev ou yarn dev

```

## 💡 Informações das rotas

  # Rota padrão - http://localhost:3333

  # User
    * /user/signup -> Cria um usuário no banco de dados
    * /user/signin -> Exibe o token para esse usuário ao logar
    * /user/me -> Exige usuário logado passando o token

  # Pix
    * /pix/transactions -> Mostra as transações
    * /pix/request -> Mostra a chave pix para transferência
    * /pix/pay/:id     ==> :id -> É a chave pix para realizar uma transferência


## 🛠 Tecnologias

As seguintes ferramentas estão sendo usadas na construção do projeto:


- [Node.js][nodejs]
- [Express][express]
- [TypeScript][typescript]
- [Docker][docker]  
- [TypeOrm][typeorm]
- [JsonWebToken][jsonwebtoken]
- [Nodemon][nodemon]
- [Crypto-JS][cryptojs]
- [express-async-erros][expresserrors]
- [Vscode][vscode]

Feito por Jefferson Valentim 👋🏽 [Contato!](https://www.linkedin.com/in/jefferson-valentim-a3b64a124/)


[nodejs]: https://nodejs.org/
[express]: https://expressjs.com/pt-br/
[typescript]: https://www.typescriptlang.org/
[typeorm]: https://typeorm.io/#/
[Joi]: https://joi.dev/api/?v=17.4.2
[docker]: https://docs.docker.com/
[bcrypt]: https://www.npmjs.com/package/bcryptjs
[jsonwebtoken]: https://www.npmjs.com/package/jsonwebtoken
[multer]: https://www.npmjs.com/package/multer
[datefns]: https://date-fns.org/
[ethereal]: https://ethereal.email/
[handlebars]: https://handlebarsjs.com/
[Vscode]: https://code.visualstudio.com/
[nodemon]: https://www.npmjs.com/package/nodemon
[cryptojs]: https://www.npmjs.com/package/crypto-js
[expresserrors]: https://www.npmjs.com/package/express-async-errors
