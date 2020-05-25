# Projeto gerenciador de Usuarios (CRUD) - feito Servidor Cliente e servidor RESTful API

Servidor Client utilizando Express e Restify

API desenvolvida em Node.js com o Curso Completo de JavaScript na Udemy.com feito pela Hcode

### Instalação de ambas pastas
```
npm install
```

### Excutando servidor de ambas pastas
```
npm start
```

### Servidor Cliente no browser
```
http://localhost:3000/
```

### Servidor RestFul browser
```
http://localhost:5000/
```

## Rotas
Obter todos os usuários:
```
GET /users
```
Exemplo de resultado:
```json
{
    "users":[]
}
```

Cadastrar um novo usuário:
```
POST /users
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324",
    "name":"João Rangel"
}
```

Obter dados de um usuário:
```
GET /users/:id
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324",
    "name":"João Rangel"
}
```

Editar um usuário:
```
PUT /users/:id
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324"
}
```

Excluir um usuário:
```
DELETE /users/:id
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324"
}
```"# projeto-crud-utilizando-restify-para-acessar-api-rest" 
