# Projeto TryBeer!

Esse projeto faz parte do curso de desenvolvimento de Software da Trybe. Foi usado em caráter educacional como forma de avaliação e foi desenvolvido em grupo no penúltimo módulo do curso - Backend. 

## O que foi desenvolvido

Essa aplicação consiste numa plataforma de entrega de bebidas. O usuário pode se cadastrar como cliente ou como Administrador. Como cliente é possível efetuar uma compra e acompanhar o pedido. Como administrador é possível administrar os pedidos e finalizar uma compra.


## Instruções para rodar o projeto:

1. Clone o repositório
  * `git clone https://github.com/tryber/sd-06-project-trybeer-v2.git`.
  * Entre na pasta do repositório que você acabou de clonar:
    * `cd sd-06-project-trybeer-v2`

2. Instale as dependências [**Caso existam**]
  * `npm install`

3. Entre na pasta de Backend/
* `cd back-end`

4. Rode os comandos para instalar as dependências, criar o banco de dados Trybeer e semeá-lo
* `npm install`
* `npm run prestart`
* `npm run seed`

5. Inicie o servidor
* `npm start`

6. Inicie a conexão com o MySql
* `sudo systemctl start mysql`

8. Entre na pasta do Frontend/
* `cd ../front-end`

9. Instale as dependências e inicie a Aplicação
* `npm install`
* `npm start`

## Tecnologias usadas no Projeto

### Frontend

Linguagem: Javascript com React

### Backend

Linguagem: NodeJs </br>
Banco de dados: MySql com uso do Sequelize

## Linter

Foi usado o [ESLint](https://eslint.org/) para fazer a análise estática do seu código.

Este projeto já vem com as dependências relacionadas ao _linter_ configuradas nos arquivos `package.json` nos seguintes caminhos:

- `sd-06-project-trybeer-v2/back-end/package.json`
- `sd-06-project-trybeer-v2/front-end/package.json`

Devido ao fato de as configurações das regras do `ESLint` dos projetos de front e back **serem diferentes**, **é preciso executar o `ESLint` em cada projeto**.

Você pode também instalar o plugin do `ESLint` no `VSCode`, bastar ir em extensions e baixar o [plugin `ESLint`](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint).

---

Usamos também o [StyleLint](https://stylelint.io/) para fazer a análise estática do seu código.

**O Stylelint é aplicável _APENAS_ no frontend**

Para poder rodar o `StyleLint` em um projeto basta executar o comando `npm install` dentro do projeto e depois `npm run lint:styles`. Se a análise do `StyleLint` encontrar problemas no seu código, tais problemas serão mostrados no seu terminal. Se não houver problema no seu código, nada será impresso no seu terminal.

## Maio / 2021
---
