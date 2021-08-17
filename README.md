## API Restful com Node.js, Express, Typescript, TypeORM, Postgres, Redis, Docker, ...

Seja muito bem-vindo ao projeto  API Restful com Node.js, Express, Typescript, TypeORM, Postgres, Redis, Docker, ...

Uma aplicação backend para gestão de vendas com funcionalidades para criação de cadastro de produtos, cadastro de clientes, pedidos de compras e uma completa gestão de usuários da aplicação, com autenticação via Token JWT, recuperação de senha por email, atualização de perfil, atualização de avatar, e muito mais.

Através do TypeORM implementaremos Entidades e Repositórios para cada recurso a ser consumido na API.

## Tecnologias

- Node.js
- Express
- Typescript
- TypeORM (Pagination,Migrations)
- Postgres
- Redis
- Docker

## Entidades

- Produtos (CRUD)
- Pedidos  (CRUD Complexo)
- Clientes (CRUD)
- Usuarios (Session, CRUD)

## Modulos

- Auth JWT
- FileSystem / Upload de arquivos
- Envio de email fake (dev env) e email profissional com o Zoho Mail e Amazon SES
- Middleware
- Route, Controller, Service, Entities, Repositories
- AWS S3, SES Dev e Prod

## Refatoração
- DDD
- Generic TypeORM
- Inversao de Dependencia (Remove Dependencia)
- Injecao de Dependencia (tsyringe, singleton)
- Jest com testes automatizados

## Instalação

Faça um clone deste repositório e instale no seu ambiente de desenvolvimento usando o seguinte comando no seu terminal (escolha um diretório apropriado):

```
git clone
```

Após clonar o conteúdo do repositório, acesse o diretório criado e efetue a instalação das dependências:

```
cd api-vendas

yarn

# ou

npm install
```
Após essa instalação execute a aplicação com o comando `yarn dev` ou `npm run dev`. O servidor estará em execução no endereço `http://localhost:3333`.

Para rodar as migrations

```
yarn typeorm migration:run
```

## Requisições
- Collection do POSTMAN na raiz do projeto

## Materiais úteis
- https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing
- https://martinfowler.com/articles/microservices.html
- https://medium.com/@erickwendel/generic-repository-with-typescript-and-node-js-731c10a1b98e
- https://iperiago.medium.com/node-js-app-in-the-real-world-what-they-never-really-tell-you-part-2-of-a-5-part-series-8e9d41d1824
- https://typeorm.io/#/
- https://sequelize.org

## Repository Pattern

Os repositórios são geralmente um empacotador comum para seu modelo e o lugar onde você escreveria diferentes consultas em seu banco de dados. Um serviço, por outro lado, é uma camada para lidar com toda a lógica de seu aplicativo. Com base na experiência, é realmente útil separar a lógica e o invólucro do modelo, especialmente quando você está trabalhando em equipe ou grandes projetos.

<img src="https://i.ibb.co/VHjpqWF/Whats-App-Image-2021-08-17-at-15-20-53.jpg" >


