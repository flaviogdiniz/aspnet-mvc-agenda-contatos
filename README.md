# 📇 Projeto Agenda de Contatos - ASP.NET MVC

Este projeto é uma aplicação web desenvolvida com **ASP.NET Core MVC**, com o objetivo de praticar e consolidar os conceitos fundamentais do padrão MVC, integração com banco de dados e operações CRUD.

## 🚀 Funcionalidades

- ✅ Listagem de contatos  
- ➕ Cadastro de novos contatos  
- ✏️ Edição de contatos existentes  
- 🔍 Visualização de detalhes  
- ❌ Exclusão de contatos com confirmação   
- 🧱 Layout compartilhado com `_Layout.cshtml`  

## 🛠️ Tecnologias Utilizadas

- **C#**
- **ASP.NET Core MVC**
- **Entity Framework Core**
- **Razor Pages**
- **SQL Server** (ou banco configurado no projeto)
- **HTML5 / CSS3**
- **Bootstrap** (para estilização)

## 🧩 Padrão Arquitetural

O projeto segue o padrão **MVC (Model–View–Controller)**:

- **Model**: Representa as entidades e regras de negócio  
- **View**: Responsável pela interface com o usuário  
- **Controller**: Gerencia as requisições, regras e comunicação com o banco  

## 📂 Estrutura do Projeto

<img width="243" height="648" alt="image" src="https://github.com/user-attachments/assets/1a19f6ad-38e1-4fbb-b99b-112010b1f245" />


## 🗄️ Banco de Dados

A aplicação utiliza **Entity Framework Core** para:
- Mapeamento das entidades
- Persistência dos dados
- Operações de CRUD

As migrações podem ser criadas com:


dotnet ef migrations add InitialCreate
dotnet ef database update

## Como Executar o Projeto

Clone o repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git

Abra o projeto no Visual Studio ou VS Code

Configure a string de conexão no appsettings.json

Execute o projeto: dotnet run

Acesse no navegador: https://localhost:xxxx

## 📚 Aprendizados

Durante o desenvolvimento deste projeto, foram reforçados conceitos como:

- Model Binding
- Rotas no ASP.NET MVC
- Separação de responsabilidades
- Boas práticas em Controllers e Views
- Segurança básica com validação de formulários







