# Desafio Nginx com Node.js

Colocando em prática os ensinamentos em relação ao uso do Nginx como proxy reverso. O usuário acessa uma aplicação Node.js através do Nginx.

O retorno da aplicação node.js para o nginx deverá ser:

```
<h1>Full Cycle Rocks!</h1>

- Lista dos usuários cadastrados no banco
```

\* Cada atualização na página irá cadastrar um novo usuário

## Como usar

```bash

# Faça o colne do repositório na sua máquina usando o comando abaixo:
$ git clone git@github.com:carlos3duardo/fullcycle-desafio-nginx-com-nodejs

# Acesse a pasta do projeto
$ cd fullcycle-desafio-nginx-com-nodejs

# Construa os containers docker
$ docker-compose up -d

```

A aplicação vai estar disponível na porta 8080.
Tente acessar via seu navegador:

http://localhost:8080