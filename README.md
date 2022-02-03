<h1 align="center">WatchMe</h1>

<p align="center">
  Rocketseat Ignite Trilha ReactJS Chapter I - Desafio 02 - Componentizando a aplicação
</p>

<p align="center">
  Nesse desafio o principal objetivo foi refatorar uma página para listagem de filmes de acordo com gênero. 

  A aplicação estava totalmente funcional mas grande parte do seu código estava diretamente no arquivo `App.tsx`. Para resolver isso da melhor forma,  a tarefa era dividir a aplicação em **pelo menos** duas partes principais: sidebar e o conteúdo principal que possui o header e a listagem de filmes.

- A aplicação possui apenas uma funcionalidade principal que é a listagem de filmes;
- Na sidebar é possível selecionar qual categoria de filmes deve ser listada;
- A primeira categoria da lista (que é "Ação") já deve começar como marcada;
- O header da aplicação possui apenas o nome da categoria selecionada que deve mudar dinamicamente.

  O desafio foi realizado a partir de um template do GitHub fornecido pela Rocketseat e as tarefas que foram concluídas podem ser observadas através dos commits.
</p>


## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [React](https://pt-br.reactjs.org/)
- [Webpack](https://webpack.js.org/)
- [Babel](https://babeljs.io/)
- [SASS](https://sass-lang.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [Axios](https://axios-http.com/docs/intro)
- [JSON Server](https://github.com/typicode/json-server)

## 🚀 Como executar

Clone o projeto e acesse sua pasta.

```bash
$ git clone https://github.com/gustavocotrim11/desafio-conceitos-react
$ cd desafio-conceitos-react
```

Para iniciar, use os comandos:
```bash
# Instale as dependências
$ yarn install
# Execute a Fake API com JSON Server
$ yarn server
# Para iniciar o projeto
$ yarn dev
```

A Fake API com JSON Server pode ser acessada em [`localhost:3333`](http://localhost:3333), com os recursos /genres e /movies.

A aplicação pode ser acessada em [`localhost:8080`](http://localhost:8080).

## 💻 Projeto

WatchMe é uma pequena aplicação de listagem de filmes de acordo com gênero.
