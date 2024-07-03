# Demonstração Docker: Arquitetura Simples de 3 Páginas e Aplicação TodoList

Esta é uma demonstração de Docker para implementar uma arquitetura simples de 3 páginas e uma aplicação TodoList como parte da disciplina de Denso Envolvimento em Nuvem ☁.

## Arquitetura

- O **frontend** é capaz de acessar o **backend**.
- O **backend** é capaz de acessar o **banco de dados**.

## Execução

Para executar essa configuração no Docker, basta digitar `docker-compose up` no prompt de comando. O Docker criará o MongoDB a partir da imagem padrão `mongo`. 

- A API usa Node.js com Express e é construída a partir da imagem [node:alpine](https://hub.docker.com/_/node).
- O front-end usa ReactJS e também é construído a partir da imagem `node:alpine`.

## Comandos

1. **Subir a aplicação**:
   ```sh
   docker-compose up
