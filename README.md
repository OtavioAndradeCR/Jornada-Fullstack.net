📘 Jornada Fullstack .NET
📌 Visão Geral

O Jornada Fullstack .NET é um projeto fullstack desenvolvido utilizando a plataforma .NET (C#) com foco em backend (API) e frontend (web). Ele reúne o código da API, da lógica de domínio e da interface de usuário, demonstrando habilidades em desenvolvimento de aplicações completas.

O projeto apresenta uma solução organizada em camadas com boa separação de responsabilidades, ideal para demonstração técnica em portfólio profissional e para avaliação em processos seletivos.

🎯 Objetivo do Projeto

Construir uma aplicação fullstack com .NET e frontend web.

Expor uma API REST com lógica de negócios.

Demonstrar integração entre backend e frontend.

Mostrar organização de projeto profissional em camadas e pastas.

🛠️ Tecnologias Utilizadas

✔ C# / .NET
✔ ASP.NET Core (Web API)
✔ Entity Framework Core
✔ MVC / Padrões de projeto
✔ Frontend Web (HTML, CSS, JavaScript)
✔ Arquitetura em camadas
✔ Maven/CLI .NET (dotnet CLI)

O projeto traz backend e frontend no mesmo repositório organizados por pastas (Fina.Api, Fina.Core, Fina.Web).

🧱 Estrutura do Projeto

O repositório está organizado da seguinte forma:

📦 Jornada-Fullstack.net
 ┣ 📂 Fina.Api      → Projeto de API REST (backend)
 ┣ 📂 Fina.Core     → Lógica de domínio / classes de negócio
 ┣ 📂 Fina.Web      → Aplicação frontend (web)
 ┣ 📜 Fina.sln      → Solução .NET completa
 ┣ 📜 .gitignore


Essa estrutura permite isolar:

Backend (API)

Lógica de negócios

Frontend web

▶️ Como Executar o Projeto
Requisitos

Antes de começar, você vai precisar ter instalado:

✔ .NET SDK 6.0 ou superior
✔ Um editor/IDE como Visual Studio ou VS Code
✔ (Opcional) Postman para testar API

Passos

Clone o repositório

git clone https://github.com/OtavioAndradeCR/Jornada-Fullstack.net.git


Abra a solução

No Visual Studio: abra o arquivo Fina.sln

No VS Code: abra a pasta raiz

Restaure dependências e compile

dotnet restore
dotnet build


Execute a API

cd Fina.Api
dotnet run


Execute o frontend

cd Fina.Web
# Se for projeto estático, abra no navegador
# Se houver build de frontend, siga instruções internas

📡 Endpoints Principais (Exemplo)

Estes exemplos são genéricos — adapte conforme os controllers do projeto.

✔️ Listar itens

GET /api/[controller]


✔️ Buscar item por ID

GET /api/[controller]/{id}


✔️ Criar novo item

POST /api/[controller]

🧪 Exemplos de Uso (curl)
curl http://localhost:5000/api/Items

curl http://localhost:5000/api/Items/1

🧩 Diferenciais Técnicos

✔ Organização por camadas (Domain / API / Web)
✔ Uso de ASP.NET Core para API
✔ Possível integração com Entity Framework e persistência
✔ Código limpo e estruturado para escala e manutenção

📈 Possíveis Evoluções

✔ Autenticação (JWT / Identity)
✔ Paginação e filtros
✔ Testes automatizados (unit / integration)
✔ Deploy em nuvem (Azure / AWS / Railway)
✔ Documentação OpenAPI / Swagger
