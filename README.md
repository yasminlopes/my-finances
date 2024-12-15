## My Finances

Uma aplicação que visa oferecer ao seu usuário a possibilidade de análise, acompanhamento e planejamento financeiro, através do controle de suas receitas e despesas. Foi desenvolvida para plataformas web com design responsivo para renderização em aplicações mobile, como smartphones e tablets.

## Quickstart

As instruções descritas abaixo lhe permitirão obter uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

### Pré-requisitos

Para rodar o projeto em sua máquina, é necessário ter instalado:

- Visual Studio Code ou alguma IDE análoga
- Algum gerenciador de banco de dados SQL, como SQL Management Studio (SSMS) ou DBeaver

### Instalação

As etapas para operação do projeto são descritas abaixo:

1. Abrir o projeto `myfinance-web-dotnet` em sua IDE
2. Abrir o terminal da IDE
3. Executar o comando `dotnet build` para compilação do projeto
4. Executar o comando `dotnet run` ou `dotnet watch run` para execução do projeto
5. Acessar a pasta `Scripts` para criação do banco de dados e executá-los em seu gerenciador de banco de dados. O primeiro script a ser executado é o `myfinanceweb_DB.sql`

## Diagrama arquitetural

![288883694-f06b2fb3-00bd-4014-97ef-77237c82e404](https://github.com/user-attachments/assets/14752ad2-6fed-43ec-b9cc-ef73899c0487)

## Tecnologias utilizadas

* [Visual Studio Code](https://code.visualstudio.com/download): Ambiente de desenvolvimento (IDE)
* [.NET Core SDK 7.0.402](https://dotnet.microsoft.com/en-us/download): Linguagem de implementação (Obs.: Foi utilizada a extensão do C#, instalada internamente no VS Code)
* [Microsoft ASPNetCore Identity Entity Framework Core 7.0.13](https://www.nuget.org/packages/Microsoft.AspNetCore.Identity.EntityFrameworkCore): Framework
* [SQL Server 2019 Express Edition](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads): Banco de Dados

