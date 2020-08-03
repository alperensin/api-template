# API Template

## Configurar API

### Instalação dos Módulos

#### Módulos Gerais
##### Servidor
`$ yarn init -y ` </br>
[`$ yarn add express `](https://www.npmjs.com/package/express) </br>
##### Banco de Dados
`$ yarn add sequelize` </br>

#### Módulos de Desenvolvimento
`$ yarn add `[`nodemon`](https://www.npmjs.com/package/nodemon)[` sucrase `](https://www.npmjs.com/package/sucrase)` -D ` </br>
`$ yarn add eslint -D ` </br>
`$ yarn add prettier eslint-config-prettier eslint-plugin-prettier -D ` </br>
`$ yarn add sequelize-cli` </br>

### Configuração das Ferramentas de Desenvolvimento
> **`$ yarn eslint --init`** ( </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- To check syntax, find problems, and enforce, </br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- JavaScript modules (import/export), </br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- None of these, </br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Node, </br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Use a popular style guide, </br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Airbnb, </br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- JavaScript, </br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Npm? Y, </br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Deletar arquivo package-lock.json do NPM e baixar novamente pelo yarn, </br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Configurar arquivo **.eslintrc.js** </br>
)

> **Generate editorconfig** ( </br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Configurar arquivo **.editorconfig** </br>
) </br>

> **Criar arquivo .prettierrc** ( </br> 
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Configurar arquivo **.prettierrc**, </br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- `$ yarn eslint --fix src --ext .js` (para fixar já arquivos criados dentro da pasta src com a extenção js) </br>
)

### Configurando **Sequelize**(ORM) e **Postgresql**(DB) 

## Estrutura API

```
  └── Projeto
       ├── src
       |   ├── app
       |   |    ├── controllers
       |   |    └── models
       │   ├── app.js
       │   ├── routes.js
       │   └── server.js
       ├── .editorconfig
       ├── .eslintrc.js
       ├── .prettierrc
       ├── nodemon.json
       └── package.json
```
