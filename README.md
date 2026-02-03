# Jornada Fullstack .NET

## 📌 Visão Geral

O **Jornada Fullstack .NET** é uma aplicação **fullstack desenvolvida em C# com .NET**, composta por uma **API REST**, uma **camada de domínio** e uma **aplicação web**, organizadas em uma única solução. O projeto tem como objetivo demonstrar, de forma prática, a construção de aplicações completas utilizando boas práticas de desenvolvimento backend e integração com frontend.

Este repositório foi desenvolvido com foco em **portfólio profissional**, evidenciando organização, separação de responsabilidades e domínio da stack .NET.

---

## 🎯 Objetivo do Projeto

* Desenvolver uma aplicação fullstack utilizando .NET
* Expor uma API REST organizada em camadas
* Demonstrar integração entre backend e frontend
* Aplicar boas práticas de código e arquitetura
* Servir como projeto demonstrativo para recrutadores

---

## 🛠️ Tecnologias Utilizadas

* **C#**
* **.NET / ASP.NET Core**
* **Web API REST**
* **Entity Framework Core**
* **Arquitetura em Camadas**
* **Frontend Web (HTML, CSS, JavaScript)**
* **Git / GitHub**

---

## 🧱 Arquitetura

O projeto está organizado seguindo o padrão de **arquitetura em camadas**, separando claramente as responsabilidades:

* **Fina.Api** – Camada de apresentação (API REST)
* **Fina.Core** – Domínio e regras de negócio
* **Fina.Web** – Camada de interface web

Essa abordagem facilita a manutenção, evolução e entendimento do código.

---

## ▶️ Como Executar o Projeto

### Pré-requisitos

* .NET SDK 6.0 ou superior
* Visual Studio ou VS Code

### Passos

```bash
# Clonar o repositório
git clone https://github.com/OtavioAndradeCR/Jornada-Fullstack.net.git

# Acessar a pasta do projeto
cd Jornada-Fullstack.net

# Restaurar dependências
dotnet restore

# Executar a API
cd Fina.Api
dotnet run
```

A aplicação será iniciada localmente conforme configuração padrão do ASP.NET Core.

---

## 📡 Endpoints Principais

```
GET    /api/[controller]
GET    /api/[controller]/{id}
POST   /api/[controller]
PUT    /api/[controller]/{id}
DELETE /api/[controller]/{id}
```

---

## 🧪 Exemplos de Uso (curl)

```bash
curl http://localhost:5000/api/exemplo
```

---

## 🧩 Diferenciais Técnicos

* Separação clara entre API, domínio e frontend
* Organização profissional da solução .NET
* Estrutura preparada para crescimento e novas funcionalidades
* Código limpo e de fácil entendimento

---

## 📈 Possíveis Evoluções

* Autenticação e autorização (JWT / Identity)
* Implementação de testes automatizados
* Integração com banco de dados relacional
* Deploy em ambiente de nuvem (Azure)
* Documentação com Swagger / OpenAPI
