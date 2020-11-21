# Testes Node - React e React Native
Treinamento RocketSeat - Testes Node - React e React Native

## Adicionando um projeto da RocketSeat de forma global - CLI que nos ajudará a inicializar projetos node, React e React Native
C:\Temp\Bootcamp2019\ yarn global add 2rocketseat/omni

## Inicializando somente a parte do node -  se informar sem "only" cria para React e Native também
C:\Temp\Bootcamp2019\ omni init modulo11 --only=server

## Acessando a pasta e chamando vscode
cd C:\Temp\Bootcamp2019\modulo11\server

## Criando banco de dados `modulotestes` no PostBird

## Adicionando um framework de testes chamado 'Jest'
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

## Resolvendo os import/export
yarn add --dev @sucrase/jest-plugin

## Adicionando as definições de tipos pro `Jest` - habilita o intellisense
yarn add -D @types/jest




## Treinamento
https://app.rocketseat.com.br/node/testes-no-node-js

## Parei aqui - 11:22
https://app.rocketseat.com.br/node/testes-no-node-js/group/ambiente-e-conceitos-7/lesson/configurando-jest-2

## Rodando a aplicação
yarn dev

## Rodando os testes
yarn test