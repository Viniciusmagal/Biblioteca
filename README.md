🎨🛍️ VenezArt – Plataforma de E-commerce de Materiais Artísticos

React + Vite | Flask | SQLite | SQLAlchemy | JWT | PDF & Excel Generator

📌 Visão Geral

O VenezArt é uma aplicação full stack desenvolvida como projeto semestral do curso de Análise e Desenvolvimento de Sistemas – IFSP Bragança Paulista.
O sistema simula uma loja virtual especializada em materiais artísticos, oferecendo ferramentas completas para:

Clientes comprarem produtos com praticidade

Administradores gerenciarem catálogo e pedidos

Geração automática de PDFs e planilhas

Autenticação segura

Fluxo completo do carrinho à finalização da compra

O projeto integra tecnologias modernas, rápidas e confiáveis para entregar uma experiência fluida tanto no cliente quanto no servidor.

🛠️ Tecnologias Utilizadas no Projeto

O sistema foi desenvolvido com três camadas principais:
Frontend com React + Vite, Backend com Python + Flask, e Banco de Dados SQLite com ORM SQLAlchemy.

🎨 Frontend – React + Vite

O frontend foi construído com React, utilizando o Vite como bundler para garantir desempenho superior no desenvolvimento e build.

💡 Por que React?

Componentização limpa e reutilizável

Estado sincronizado em tempo real

Fácil integração com API REST Flask

Ideal para aplicações dinâmicas e interativas

⚡ Por que Vite?

Build extremamente rápido

HMR (Hot Module Replacement) instantâneo

Menos consumo de recursos

Ambiente moderno e otimizado

🔧 Funcionalidades Implementadas no Frontend

Interface completa do cliente e administrador

Listagem de produtos

Carrinho (add, remove, update)

Login e cadastro conectados ao backend

Tela de pedidos + histórico

Área administrativa (CRUD completo)

Consumo de API via fetch ou axios

Layout responsivo e atualizado pelo estado global

🐍 Backend — Python + Flask

O backend utiliza Flask, garantindo leveza, segurança e flexibilidade na construção da API.
Python foi escolhido pela clareza da linguagem e pela força de seu ecossistema.

🔧 Recursos do Flask Utilizados
🔀 Roteamento da API

Gerencia endpoints como:

/api/login

/api/usuarios

/api/produtos

/api/carrinho

/api/pedidos

/api/favoritos

📥 request

Recebe dados enviados pelo frontend.

📤 jsonify

Retorna respostas estruturadas em JSON para o React.

🔐 Autenticação JWT

Com Flask-JWT-Extended:

create_access_token() – gera tokens

jwt_required() – protege rotas sensíveis

get_jwt_identity() – identifica usuário logado

🔑 Segurança de Senhas

Usando Werkzeug Security:

generate_password_hash() — cria hash seguro

check_password_hash() — valida senha no login

📄 Geração de Arquivos — PDF e Excel

A aplicação conta com geração automática de arquivos:

📘 PDF – via ReportLab

Utilizado para gerar:

Comprovantes de pedido

Relatórios administrativos

Documentos com tabelas, títulos e formatação personalizada

📊 Excel – via openpyxl + pandas

Usado para:

Exportação de pedidos

Relatórios da área administrativa

🧠 BytesIO

Permite criar PDFs e planilhas sem salvar no disco, enviando diretamente para o usuário.

🗄 Banco de Dados — SQLite + SQLAlchemy (ORM)

O projeto utiliza SQLite pela simplicidade e desempenho em projetos pequenos/médios.
O ORM SQLAlchemy permite trabalhar com tabelas usando classes Python.

✔ Por que SQLite?

Sem necessidade de servidor

Ideal para desenvolvimento local

Estável, rápido e confiável

Integração perfeita com SQLAlchemy

🧱 Modelos Principais
👤 User

id, nome, email, senha hash

perfil (cliente/admin)

🎨 Product

nome, descrição, preço, estoque, imagem

🛒 CartItem

itens no carrinho, armazenados por usuário

📦 Pedido

dados do pedido + data

📦➡️🖼 PedidoItem

itens pertencentes a cada pedido

⭐ Favorite

lista de favoritos de cada cliente

Esses modelos garantem integridade e facilitam operações CRUD.

🔌 Integração Frontend + Backend

O React se comunica com Flask via API RESTful, com as seguintes características:

Padrão JSON

Rotas protegidas com JWT

Sessões persistentes

Controle de erros refinado

Organização limpa por controladores

🎯 Objetivos do Sistema

Organizar catálogo de produtos

Criar fluxo completo de compra

Gerenciar usuários

Controlar pedidos e gerar comprovantes

Entregar uma plataforma robusta e intuitiva

Aplicar conceitos de análise orientada a objetos

Estruturar uma solução completa do zero

📌 Status do Projeto

✔ Back-end funcional
✔ Front-end integrado
✔ Login + JWT implementado
✔ CRUD administrativo completo
✔ Carrinho funcional
✔ PDF e Excel funcionando
✔ Banco de dados operante
✔ Layout responsivo

🧑‍💻 Desenvolvedores
Nome	Prontuário
Geisiele de Oliveira	BP3053563
Thiago Oliveira	BP3053636
Vinicius Arantes	BP3053709
Vinícius Magalhães	BP3054365
