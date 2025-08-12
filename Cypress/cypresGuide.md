Verificando requisitos

[x] Node.js
O Cypress depende do Node.js para funcionar.
Checar se está instalado:
    node -v

Verificar se o npm está funcionando corretamente:
    npm -v


[x] Verificar ou criar uma pasta de projeto com package.json
Se já estiver em uma pasta de projeto:
    npm init -y

Isso irá criar um package.json, necessário para gerenciar dependências.


[x] Instalar o Cypress
    npm install cypress --save-dev
    npx cypress open
    npx cypress run


[x] Dependências auxiliares (opcionalmente úteis para projetos mais robustos)

Você pode adicionar isso posteriormente, mas vale a pena já conhecer:
    cypress-file-upload (upload de arquivos)
    faker-js/faker (geração de dados fake)
    cypress-axe (testes de acessibilidade)
    dotenv (carregar variáveis de ambiente)
    eslint-plugin-cypress (lint específico)
    Testes com interceptação de APIs (cy.intercept)
    Rodar testes em CI/CD
    Geração de relatórios (ex: mochawesome)