# 🎵 ScreenSound API

A **ScreenSound** é uma Web API desenvolvida com **C# .NET** para cadastro e gerenciamento de **artistas** e suas **músicas**, utilizando o **Entity Framework Core** com **PostgreSQL** como banco de dados relacional.

## 🚀 Objetivo do Projeto

O principal objetivo deste projeto é praticar a criação de APIs RESTful com ASP.NET Core, focando em:
- Utilização do **Entity Framework Core**
- Estruturação de uma Web API moderna
- Boas práticas de desenvolvimento

## 🛠️ Tecnologias Utilizadas

- [.NET 8](https://dotnet.microsoft.com/)
- [ASP.NET Core Web API](https://learn.microsoft.com/aspnet/core/web-api)
- [Entity Framework Core](https://learn.microsoft.com/ef/core/)
- [PostgreSQL](https://www.postgresql.org/)

## 📦 Funcionalidades

- ✅ Cadastro de Artistas
- ✅ Cadastro de Músicas vinculadas a um Artista
- ✅ Consulta de Artistas e Músicas
- ✅ Atualização e remoção de registros
- 🔧 Documentação interativa com Swagger *(em desenvolvimento)*

## 📁 Estrutura do Projeto (Atualmente)

- /ScreenSound
- ├── Program.cs
- /ScreenSound.API
- ├── Program.cs
- └── appsettings.json
- /ScreenSound.Shared.Dados
- ├── Banco
- └── Migrations
- /ScreenSound.Shared.Modelos
- └── Modelos


## 🔧 Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/screensound.git
   cd screensound
   
2. Restaure os pacotes:
  dotnet restore

3. Configure a connection string para PostgreSQL no appsettings.json:
  "ConnectionStrings": {"DefaultConnection": "Host=localhost;Port=5432;Database=ScreenSoundDb;Username=postgres;Password=senha"}

4. Aplique as migrations:
  dotnet ef database update

5. Execute a aplicação:
     dotnet run

## 🔮 Próximas melhorias
 - Autenticação e autorização com JWT

 - ⬜ Paginação e filtros nas consultas

 - ⬜ Testes unitários com xUnit

 - ⬜ Validações com FluentValidation

 - ⬜ Deploy em nuvem

 - ⬜ Swagger

