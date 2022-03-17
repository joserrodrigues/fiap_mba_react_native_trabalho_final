# FIAP MBA Mobile - Trabalho Final - React Native

Olá, seja bem-vindo a entrega final do Aula Aplicações Nativas Cross-Platform com React Nativ.

Você terá de desenvolver um aplicativo React Native que irá listar os produtos de uma loja.

**Principais instruções**

- Após o login, o usuário poderá visualizar os detalhes de cada produto e saber quais as lojas eles estão disponíveis.
- Também será possível favoritar o produto e ver uma página com os produtos favoritos.
- Ao realizar o refresh do navegador, a aplicação deverá permanecer logada.
> **Dica:** Em todas as APIs você deve usar a URL: **https://fiap-reactjs-presencial.herokuapp.com**.

# Telas

## Tela de login

- Tela com e-mail e senha para autenticar o usuário
- Abaixo aparecerá um botão de realizar cadastro
- Você utilizará a **API MBA Presencial - Trabalho Final - Realiza o login do usuário /storeProducts/login**
- Utilizar o Yup para realizar a validação

## Tela de cadastro

- Tela com nome, telefone, e-mail e senha para cadastrar o usuário
- Você utilizará a **API MBA Presencial - Trabalho Final - Realiza o cadastro do usuário /storeProducts/signup**
- Utilizar o Yup para realizar a validação

## Menu Lateral

- Em todas as telas principais (1a tela do Stack), deverá aparecer um menu lateral com as opções:
  - Nome do usuário
  - Principal (Tela de produtos)
  - favoritos (Tela de favoritos)  
  - Botão de logout

## Tela de produtos

- Tela que exibirá em uma lista os dados dos produtos
- Cada item deverá mostrar: Nome do Produto, Preço do Produto, Favorito e um botão de visualizar detalhe (Ir a tela **Detalhe do produto**).
- Esse ListView utilizará a paginação de resultados.
- Você utilizará a **API MBA Presencial - Trabalho Final - Busca todos os produtos /storeProducts/**
- Ao carregar a tela, deverá buscar a posição do usuário.

## Tela de favoritos

- Tela exibirá os produtos determinados como favoritos dos usuários.
- A tabela deverá mostrar: Nome do Produto, Preço do Produto, Favorito e um botão de visualizar detalhe (Ir a tela **Detalhe do produto**).
- Você utilizará a **API MBA Presencial - Trabalho Final - Busca todos os produtos favoritos /storeProducts/getFavProduts**

## Tela detalhe do produto

- Tela que exibirá os detalhes de um produto.
- A tela deverá mostrar:
  - Nome do Produto
  - Preço do Produto
  - Se é Favorito do usuário (e um botão para marcar/desmarcar favorito)
  - Mapa com a posição do usuário e as lojas com o produto disponível
- Você utilizará a **API MBA Presencial - Trabalho Final - Busca informação de um produto /storeProducts/product/:productID** e **API MBA Presencial - Trabalho Final - Adicionar ou remove um produto como favorito da pessoa /storeProducts/manageFavorite**

# Doc das APIs

A documentação das APIs está disponível em: **https://fiap-reactjs-presencial.herokuapp.com/doc**