# :rocket: Bootcamp Gostack Banco de dados e upload de arquivos no Node.js
Desafio: Database + upload Node.js

## Objetivo
Criar uma aplicação para praticar o que foi aprendido no [Bootcamp GoStack da RocketSeat](https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-database-upload)

----------

## Pré-requisitos

- NodeJs
- Yarn
- Docker

## Instalando dependências.

``` bash
yarn
```

## Rodando aplicação

``` bash
# Rodar Postgres
docker run --name gostack_postgres -e POSTGRES_PASSWORD=[[SUASENHA]] -p 5432:5432 -d postgres

```
⚠️ Criar banco de dados no: ***gostack_desafio06*** e ***gostack_desafio06_tests*** ⚠️


``` bash
yarn dev:server
```

## Rodando os testes

``` bash
yarn test
```
