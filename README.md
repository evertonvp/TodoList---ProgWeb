# TODO-LIST Web Application

Este projeto é uma aplicação web de gerenciamento de tarefas (TODO List). O sistema permite que usuários registrem, editem, concluam, excluam e organizem suas tarefas de forma simples e eficiente.

## ✨ Funcionalidades

- Registro e login de usuários com autenticação JWT.
- Interface moderna e responsiva.
- Adição, edição (inline), exclusão e conclusão de tarefas.
- Agrupamento de tarefas por pendentes e concluídas.
- Confirmação ao excluir tarefas.
- Envio de e-mail com tarefas pendentes.
- Animações suaves e opção de ocultar/exibir grupos de tarefas.

## 🧠 Tecnologias utilizadas

### Frontend:
- HTML5
- CSS3
- JavaScript Puro

### Backend:
- Node.js
- Express.js
- SQLite3
- JWT (Json Web Token)
- Nodemailer

## 📁 Estrutura do Projeto  

```
todo-list/
├── backend/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── database.sqlite
├── database/
│   └── db.sqlite
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── style.css
│   └── script.js
```

## 🚀 Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/todo-list.git
cd todo-list
```

### 2. Instalar dependências do backend

```bash
cd backend
npm install
```

### 3. Iniciar o servidor backend

```bash
npm start
```

O servidor será iniciado em: `http://localhost:3000`

### 4. Abrir o frontend

Abra o arquivo `frontend/index.html` ou `frontend/login.html` no seu navegador.


## 📝 Observações

- A base de dados SQLite é criada automaticamente.
- As credenciais e tokens são armazenados em `localStorage`.
- Envio de email funciona por meio do Ethereal, um serviço gratuito de e-mail falso usado exclusivamente para testes de desenvolvimento.


