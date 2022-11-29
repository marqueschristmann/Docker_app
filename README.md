Uma demonstração do Docker para implementar uma arquitetura simples de 3 camadas

* frontend será capaz de acessar o Backend
* Backend será capaz de acessar o banco de dados

Para executar isso no docker, simplesmente digite ```docker-compose up``` no prompt de comando. O Docker criará o [MongoDB](https://www.mongodb.com/) a partir da imagem padrão [mongo](https://hub.docker.com/_/mongo). A API usa [nodejs](https://nodejs.org/) com [express](http://expressjs.com/) e é construída a partir de um [node:alpine](https://hub.docker.com /_/nó) imagem. O front-end usa [ReactJS](https://reactjs.org/) e é construído a partir de uma imagem [node:alpine](https://hub.docker.com/_/node).