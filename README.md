# Biblioteca API

API para gerenciamento de uma coleção de livros, desenvolvida utilizando Flask.

## 🚧 Status do Projeto

Este projeto está concluído.

## 🚀 Tecnologias Utilizadas:

- **Framework:** Flask
- **Linguagem:** Python
- **Banco de Dados:** Em memória (lista de dicionários)
- **Ferramentas de Desenvolvimento:** Flask, jsonify, request

## 📦 Funcionalidades:

- **Consultar todos os livros:** Permite obter a lista de todos os livros cadastrados.
- **Consultar livro por ID:** Permite obter detalhes de um livro específico pelo seu ID.
- **Editar livro:** Permite editar as informações de um livro existente.
- **Adicionar novo livro:** Permite adicionar um novo livro à coleção.
- **Excluir livro:** Permite excluir um livro existente da coleção.

## 📋 Rotas da API:

- **`GET /livros`** - Retorna todos os livros.
- **`GET /livros/<int:id>`** - Retorna o livro com o ID especificado.
- **`PUT /livros/<int:id>`** - Edita o livro com o ID especificado.
- **`POST /livros`** - Adiciona um novo livro.
- **`DELETE /livros/<int:id>`** - Exclui o livro com o ID especificado.

## 🚀 Repositórios Autoral:

- [Biblioteca API](https://github.com/joaogdv/api-py) 

## 📬 Contato:

- **Pessoal:** joaoguilherme.morinari@gmail.com 

Sinta-se à vontade para contribuir com este projeto open source. Sugestões, relatórios de bugs e pull requests são muito bem-vindos!
