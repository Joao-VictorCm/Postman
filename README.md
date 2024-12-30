# Postman

Este projeto criado para visualizar (por meio de API) endpoints utilizando o Postman localmente, com exemplos de diferentes métodos HTTP (`GET`, `POST`, `PUT`, `PATCH`, `DELETE`).

---

## 🛠️ Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript.
- **Express.js**: Framework para criação de servidores web.

---

## 🚀 Como Executar o Projeto

1. **Clone o Repositório**:
   ```bash
   git clone git@github.com:Joao-VictorCm/Postman.git

2. **Instale as Dependências**:

   ```bash
    npm install
   ```

3. **Execute o Servidor**:

   ```bash
    node index.js
   ```
   
4. **Acesse a Aplicação**:

    O servidor será iniciado em http://localhost:3001.

---

## 📚 Endpoints

1. **GET /**
  - Descrição: Retorna a página inicial com o título "Home Page".
  - Resposta:
   ``` html
     <h1>Home Page</h1>
   ```
2. **POST /register**
   - Descrição: Simula um registro de usuário.
   - Resposta: HTTP Status 201 Created.
     
3. **PUT /user/angela/**
   - Descrição: Simula a atualização completa do recurso de um usuário específico.
   - Resposta: HTTP Status 200 OK.
     
5. **PATCH /user/angela**
   - Descrição: Simula a atualização parcial do recurso de um usuário específico.
   - Resposta: HTTP Status 200 OK.
     
6. **DELETE /user/angela**
   - Descrição: Simula a exclusão do recurso de um usuário específico.
   - Resposta: HTTP Status 200 OK.
