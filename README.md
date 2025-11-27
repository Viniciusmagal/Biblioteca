# 🎨 Projeto VenezArt

![React](https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react)
![Flask](https://img.shields.io/badge/Backend-Flask-black?style=for-the-badge&logo=flask)
![Vite](https://img.shields.io/badge/Bundler-Vite-purple?style=for-the-badge&logo=vite)
![SQLite](https://img.shields.io/badge/Database-SQLite-blue?style=for-the-badge&logo=sqlite)
![JWT](https://img.shields.io/badge/Auth-JWT-orange?style=for-the-badge&logo=jwt)

---

## 📌 Descrição

O **VenezArt** é uma loja virtual de materiais artísticos, com foco em produtos para pintura em tela.

O projeto foi desenvolvido como parte do Projeto Semestral do curso de **Análise e Desenvolvimento de Sistemas – IFSP**, utilizando uma arquitetura moderna e tecnologias atuais.

---

## 🛠 Funcionalidades

### 👤 Cliente
- Navegação no catálogo de produtos
- Visualização detalhada de itens
- Adição e remoção de produtos no carrinho
- Finalização de pedidos
- Geração automática de comprovante em PDF
- Histórico de compras

### 🔧 Administrador
- Cadastro, edição e exclusão de produtos (CRUD)
- Visualização e gerenciamento de pedidos
- Gerenciamento de usuários
- Exportação de relatórios em PDF e Excel

---

## 🧠 Tecnologias Utilizadas

### 🎨 Frontend
- React
- Vite
- JavaScript (ES2024)
- HTML5 e CSS3

### 🐍 Backend
- Python
- Flask
- Flask-JWT-Extended
- Werkzeug Security

### 🗄 Banco de Dados
- SQLite

### 🔗 ORM
- SQLAlchemy

### 📄 Geração de Arquivos
- ReportLab (PDF)
- openpyxl + pandas (Excel)

---

## 🧱 Arquitetura

O sistema segue o modelo **Cliente–Servidor**, onde:

- O frontend em React consome a API REST desenvolvida em Flask.
- O backend em Flask lida com regras de negócio, autenticação e geração de arquivos.
- O banco de dados SQLite armazena usuários, produtos e pedidos.

---

## ⚙️ Instruções

### 🔧 Configuração do Backend

    cd backend
    python -m venv venv

    # Ativar ambiente virtual (Windows)
    venv\Scripts\activate

    # Ativar ambiente virtual (Linux/Mac)
    source venv/bin/activate

    pip install -r requirements.txt
    python app.py

A API Flask estará em:

    http://localhost:5000

---

### 🌐 Configuração do Frontend

    cd frontend
    npm install
    npm run dev

A aplicação React estará disponível em:

    http://localhost:5173

---

## 👨‍💻 Desenvolvedores

[![Geisiele Oliveira](https://img.shields.io/badge/GitHub-GeisieleOliveira-black?style=for-the-badge&logo=github)](https://github.com/GeisieleOliveira)
[![Thiago Oliveira Cmargo](https://img.shields.io/badge/GitHub-Thiagolvc-black?style=for-the-badge&logo=github)](https://github.com/Thiagolvc)

[![Vinícius Magalhães](https://img.shields.io/badge/GitHub-Viniciusmagal-black?style=for-the-badge&logo=github)](https://github.com/Viniciusmagal)

---

✔ Projeto desenvolvido para fins acadêmicos  
✔ Arquitetura moderna  
✔ Código organizado e modular  
✔ Fácil manutenção e escalabilidade
