# React Challenge

Este é um desafio para testar seus conhecimentos em JavaScript, React e Redux;

Neste teste existem várias respostas corretas, pois o objetivo é avaliar a sua forma de codificação, e suas habilidades usando a tecnologia proposta.

# Carrinho de Compras

Seu objetivo é montar um carrinho de compras simples, conforme o prototipo a seguir:

O layout deve ser como de um 

A tela de listagem de produtos deve:

- Buscar os produtos de um serviço Rest;
- Exibir os produtos;
- Exibir detalhes de um produto individual;

O carrinho deve:

- Permitir remover itens;
- Permitir alterar a quantidade de um item;
- Exibir o somatório total dos itens incluidos;

# Serviço Rest

Criar o backend não é o foco deste teste, portanto está sendo disponibilizado um serviço Rest que deve ser utilizado para recuperar a lista de produtos do projeto.

Para rodar o serviço, é necessário instalar o json-server:

`npm install -g json-server`

Após isso, rodar o comando: `json-server --watch rest-api/products.json`

Isso irá disponibilizar uma api REST rodando no endereço http://localhost:3000/products.

Um produto especifico pode ser acessado através da url http://localhost:3000/products/{id};