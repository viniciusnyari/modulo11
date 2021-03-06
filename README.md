# Testes Node - React e React Native
Treinamento RocketSeat - Testes Node - React e React Native

## Adicionando um projeto da RocketSeat de forma global - CLI que nos ajudará a inicializar projetos node, React e React Native
C:\Temp\Bootcamp2019\ yarn global add 2rocketseat/omni

## Inicializando somente a parte do node -  se informar sem "only" cria para React e Native também
C:\Temp\Bootcamp2019\ omni init modulo11 --only=server

## Criando banco de dados `modulotestes` no PostBird

## Adicionando um framework de testes chamado `Jest`
yarn add jest -D

## Inicializando o 'Jest'
yarn jest --init 

The following questions will help Jest to create a suitable configuration for your project
√ Would you like to use Jest when running "test" script in "package.json"? ... yes
√ Would you like to use Typescript for the configuration file? ... no
√ Choose the test environment that will be used for testing » node
√ Do you want Jest to add coverage reports? ... yes
√ Which provider should be used to instrument code for coverage? » v8
√ Automatically clear mock calls and instances between every test? ... yes

✏️  Modified C:\Temp\Bootcamp2019\modulo11\server\package.json

📝  Configuration file created at C:\Temp\Bootcamp2019\modulo11\server\jest.config.js
Done in 234.59s.

## Resolvendo os `import/export`
yarn add --dev @sucrase/jest-plugin

## Adicionando as definições de tipos pro `Jest` - habilita o intellisense
yarn add -D @types/jest

## Criando `migration` - criação de estrutura de banco
yarn sequelize migration:create --name=create-users

## Instalando `sqlLite3` - armazenamento local das informações
yarn add sqlite3 -D

## Instalando `supertest` para fazer as chamadas http para testes
yarn add supertest -D

## Instalando `bcryptjs` - encriptar senha
yarn add bcryptjs

## Instalando `factory-girl` e `faker` - Gerar dados aleatórios
yarn add factory-girl faker -D


## Acessando a pasta e chamando vscode
cd C:\Temp\Bootcamp2019\modulo11\server

## Treinamento
https://app.rocketseat.com.br/node/testes-no-node-js

## Rodando a aplicação - validando se tem erros
yarn dev

## Rodando os testes - rodando os testes - não precisa o anterior estar rodando
yarn test

## Projeto original
https://github.com/rocketseat-education/bootcamp-gostack-11