# Utils!

## Configurar API

### Instalação Módulos
`$ yarn init -y `
`$ yarn add express `
`$ yarn add nodemon sucrase -D `
`$ yarn add eslint -D `
`$ yarn add prettier eslint-config-prettier eslint-plugin-prettier -D `

### Configurar Ferramentas Desenvolvimento
> **`$ yarn eslint --init`** (
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- To check syntax, find problems, and enforce,
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- JavaScript modules (import/export),
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- None of these,
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Node,
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Use a popular style guide,
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Airbnb,
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- JavaScript,
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Npm? Y,
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Deletar arquivo package-lock.json do NPM e baixar novamente pelo yarn,
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Configurar arquivo **.eslintrc.js**
)

> **Generate editorconfig** (
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Configurar arquivo **.editorconfig**
)

> **Criar arquivo .prettierrc** (
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- Configurar arquivo **.prettierrc**,
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- `$ yarn eslint --fix src --ext .js` (para fixar já arquivos criados dentro da pasta src com a extenção js)
)

## Estrutura

```
  └── Projeto
       ├── src
       │   ├── app.js
       │   ├── routes.js
       │   └── server.js
	   ├── .editorconfig
	   ├── .eslintrc.js
	   ├── .prettierrc
	   ├── nodemon.json
	   └── package.json
```
