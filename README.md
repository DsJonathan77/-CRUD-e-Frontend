# CRUD de Usuários com Flask, MySQL e Interface Web

Este projeto é uma aplicação web simples desenvolvida com **Python (Flask)**, **MySQL** e **HTML/CSS**. O objetivo é implementar um CRUD completo (Create, Read, Update, Delete) de usuários, com interface gráfica.

## 🧩 Funcionalidades

- ✅ Cadastrar usuário
- ✅ Visualizar lista de usuários
- ✅ Atualizar dados do usuário
- ✅ Excluir usuário

## 📦 Tecnologias Utilizadas

- **Back-end:** Python + Flask
- **Banco de dados:** MySQL
- **Front-end:** HTML + CSS (Bootstrap)
- **ORM:** Flask-MySQLdb

## 🧑‍💻 Entidade `usuario`

| Campo | Tipo         | Descrição                     |
|-------|--------------|-------------------------------|
| id    | INT (PK)     | Chave primária (auto incremento) |
| nome  | VARCHAR(100) | Nome do usuário               |
| email | VARCHAR(100) | E-mail do usuário             |
| senha | VARCHAR(100) | Senha do usuário (simples)    |

## 🚀 Como Executar o Projeto

1. Clone este repositório ou baixe o ZIP:
```bash
git clone https://github.com/seu-usuario/seu-repo.git
