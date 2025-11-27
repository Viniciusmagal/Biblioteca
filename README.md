# 🎨 Projeto VenezArt

![React](https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react)
![Flask](https://img.shields.io/badge/Backend-Flask-black?style=for-the-badge&logo=flask)
![Vite](https://img.shields.io/badge/Bundler-Vite-purple?style=for-the-badge&logo=vite)
![SQLite](https://img.shields.io/badge/Database-SQLite-blue?style=for-the-badge&logo=sqlite)
![JWT](https://img.shields.io/badge/Auth-JWT-orange?style=for-the-badge)

---

## 📑 Sumário

- [Descrição](#descrição)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Arquitetura](#arquitetura)
- [Instruções](#instruções)
- [Desenvolvedores](#desenvolvedores)

---

## 📌 Descrição

O **VenezArt** é um sistema web desenvolvido para funcionar como uma **loja virtual de materiais artísticos**, com foco em itens para pintura em tela.

O projeto foi desenvolvido como parte do Projeto Semestral do curso de **Análise e Desenvolvimento de Sistemas – IFSP**, utilizando uma arquitetura moderna e tecnologias atuais.

A aplicação permite que clientes realizem compras de forma simples e rápida, enquanto o administrador possui recursos avançados de gerenciamento.

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
- Cadastro, edição e exclusão de produtos
- Visualização de pedidos
- Gerenciamento de usuários
- Exportação de relatórios em PDF e Excel

---

## 🧠 Tecnologias Utilizadas

### 🎨 Frontend
- **React**
- **Vite**
- JavaScript (ES2024)
- HTML5 e CSS3

### 🐍 Backend
- **Python**
- **Flask**
- Flask-JWT-Extended
- Werkzeug Security

### 🗄 Banco de Dados
- **SQLite**

### 🔗 ORM
- **SQLAlchemy**

### 📄 Geração de Arquivos
- **ReportLab** (PDF)
- **openpyxl** + **pandas** (Excel)

---

## 🧱 Arquitetura

O sistema segue o modelo **Cliente–Servidor**, onde:

- O frontend em React consome a API REST do Flask.
- O backend gerencia regras de negócio e autenticação.
- O banco de dados SQLite armazena as informações.

---

## ⚙️ Instruções

### 🔧 Configuração do Backend

```bash
cd backend
python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate

pip install -r requirements.txt
python app.py
```

### 🌐 Configuração do Frontend

```bash
cd frontend
npm install
npm run dev
```

A aplicação estará disponível em:
```
http://localhost:5173
```

A API Flask roda em:
```
http://localhost:5000
```

---

## 👨‍💻 Desenvolvedores

| Nome | Prontuário |
|------|------------|
| Geisiele de Oliveira | BP3053563 |
| Thiago Oliveira | BP3053636 |
| Vinicius Arantes | BP3053709 |
| **Vinícius Magalhães** | **BP3054365** |

---

✔ Projeto desenvolvido para fins acadêmicos  
✔ Arquitetura moderna  
✔ Código organizado e modular  
✔ Fácil manutenção e escalabilidade
