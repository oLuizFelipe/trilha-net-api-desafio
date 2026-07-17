# API de Gerenciamento de Tarefas

Projeto desenvolvido durante a trilha .NET da DIO.

## Tecnologias utilizadas

- C#
- ASP.NET Core
- Entity Framework Core
- SQL Server
- Swagger/OpenAPI

## Funcionalidades

- ✅ Buscar tarefa por ID
- ✅ Listar todas as tarefas
- ✅ Buscar tarefas por título
- ✅ Buscar tarefas por data
- ✅ Buscar tarefas por status
- ✅ Criar tarefa
- ✅ Atualizar tarefa
- ✅ Excluir tarefa

## Como executar

1. Clone o repositório

```bash
git clone https://github.com/oLuizFelipe/trilha-net-api-desafio.git
```

2. Configure a Connection String no `appsettings.json`

3. Execute as migrations

```bash
dotnet ef database update
```

4. Execute o projeto

```bash
dotnet run
```

5. Acesse o Swagger

```
https://localhost:xxxx/swagger
```

## Autor

Luiz Felipe Oliveira
