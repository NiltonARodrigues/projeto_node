# Nginx com Node.js
Curso FullCycle 3.0 DevOps, Docker.

### Descrição do desafio
> Nesse desafio você colocará em prática o que aprendemos em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

__O retorno da aplicação node.js para o nginx deverá ser:__
```html
<h1>Full Cycle Rocks!</h1>

- Lista de nomes cadastrada no banco de dados.
```

### Requisitos
1. A porta 8080 deve estar disponível.

  
### Para rodar :zap:
**Execute o comando:
docker-compose up -d

