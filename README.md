# Projeto - desafio-angular

Angular na versão 9.1.7

Author: Leandro Pinheiro Leite

## Conteúdo

- [Visão Geral do Projeto](#visão-geral-do-projeto)
- [Desafio](#desafio)
- [Tecnologias](#tecnologias)
- [Documentação API Marvel](#documentação-api-marvel)
- [Informações Iniciais](#informações-iniciais)
- [Instalando as Dependências](#instalando-as-dependências)
- [Servidor de Desenvolvimento](#servidor-de-desenvolvimento)
- [Servidor de Produção](#servidor-de-Produção)

## Visão Geral do Projeto

O objetivo do desafio é o desenvolvimento de uma aplicação que exibisse todas as informações sobre a fraquia e Personagens Marvel

### Tecnologias

- HTML5
- CSS

  - [SCSS](https://sass-lang.com/)
  - TypeScript
  - JavaScript
  - [Angular] (https://angular.io/)
  - [Ant Design](https://ng.ant.design/docs/introduce/en)

  ### Desafio

  O desafio terá 3 telas:

1 - Listagem de personagens:

- Faça o consumo da API de listagem de personagens: "/v1/public/characters";
- Exiba o nome e foto de cada personagem;
- Ao selecionar o personagem, deverá direcionar para a tela de detalhes.

2 - Detalhes do Personagem:

- Exiba a imagem do personagem, o nome, a descrição e um botão de direcionamento para a uma tela que mostre
  qual a HQ mais cara daquele personagem.
  3 - Detalhe da HQ mais cara do personagem:
- Faça o consumo da API de listagem de HQs por personagem: "/v1/public/characters/{characterId}/comics";
- Exiba na tela somente a revista mais cara daquele personagem com imagem, título, descrição e o preço.

### Documentação API Marvel

A documentação da API utilizada para obter os dados está disponível em: [Marvel](https://developer.marvel.com/docs#!/public/getCreatorCollection_get_12).

## Informações Iniciais

Para realizar as passos a seguir, será necessário que tenha instalado em seu computador o **git** e o **node.js**. Abaixo seguem os sites para realizar o download e efetuar a instalação:

- [Git](https://git-scm.com/downloads)
- [Node.js - Windows/Mac](https://nodejs.org/en/download/)
- [Node.js - Linux](https://nodejs.org/en/download/package-manager/)

### Instalando as Dependências

Para instalar as dependências do projeto basta abrir o **Prompt de Comando** (caso você esteja no linux, basta utilizar o terminal), acessar a pasta do repositório e inserir o seguinte comando:
npm install

## Servidor de Desenvolvimento

Execute no **Prompt de Comando** (caso você esteja no linux, basta utilizar o terminal) `ng serve` para rodar o projeto em um servidor dev. Navegue para `http://localhost:4200/`. O aplicativo será recarregado automaticamente se você alterar qualquer um dos arquivos de origem.

## Servidor de Produção

Execute no **Prompt de Comando** (caso você esteja no linux, basta utilizar o terminal) `ng build` para criar o projeto. Os arquivos de construção serão armazenados no diretório `dist`

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.7.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
