# Utils

# Configure API

- Modules
-- yarn init -y
-- yarn add express
-- yarn add nodemon sucrase -D
-- yarn add eslint -D
-- yarn add prettier eslint-config-prettier eslint-plugin-prettier -D
-- 

- Configure Tools
-- yarn eslint --init (
    .To check syntax, find problems, and enforce,
    .JavaScript modules (import/export),
    .None of these,
    .Node,
    .Use a popular style guide,
    .Airbnb,
    .JavaScript,
    .Npm? Y,
    --- Deletar arquivo package-lock.json do NPM e baixar novamente pelo yarn,
    --- Configurar arquivo .eslintrc.js
)
-- Generate editorconfig (
    --- Configurar arquivo .editorconfig
)
-- Criar arquivo .prettierrc (
    --- Configurar arquivo .prettierrc,
    --- yarn eslint --fix src --ext .js (para fixar já arquivos criados dentro da pasta src com a extenção js)
)


# Estrutura:

> Projeto
  > src
    app.js
    routes.js
    server.js
.editorconfig
.eslintrc.js
.prettierrc
nodemon.json
package.json
