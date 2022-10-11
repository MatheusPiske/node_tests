# Ferramentas utilizadas no decorrer do curso

## -- Para a instalação do eslint:
=> npm install --save-dev eslint@8.16.0 --save-exact

## Configurando o eslint:
=> npx eslint --init

## Etapas da configuração do eslint:
=> To check syntax, find problems, and enforce code style
=> JavaScript modules (import/export)
=> None of these
=> Does your project use TypeScript? » No
=> Where does your code run? Node
=> How would you like to define a style for your project? Use a popular style guide / Airbnb: https://github.com/airbnb/javascript
=> What format do you want your config file to be in? JSON
=> Would you like to install them now? Yes
=> Which package manager do you want to use? npm

## -- Para a instalação do jest:
=> npm install --save-exact jest@28.1.0 --save-dev

## -- Configurando o package.json: 
=> "test": "jest"
=> "type": "module"

## -- Configurando os testes para serem assistidos (testes dinâmicos)
=> "test:watch": "node --experimental-vm-modules node_modules/jest/bin/jest.js --watch"

## Configurando a cobertura de testes da aplicação (geração de relatórios)
=> "test:coverage": "node --experimental-vm-modules node_modules/jest/bin/jest.js --coverage"

## Links:

=> https://jestjs.io/pt-BR/docs/using-matchers
=> REPOSITÓRIO DO PROJETO COMPLETO: https://github.com/alura-cursos/2495_node_testes/tree/aula-3