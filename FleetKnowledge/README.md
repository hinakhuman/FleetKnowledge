# FleetKnowledge
## Overview 
This project focuses on creating a whole eosystem on how the fleet management works. Its is a AI-powdered knowledge plateform for a fleet maintenance organization

## Problem Statement
Fleet management in itself is a huge system where different modules work like a connected dots. Fleet technicians spend valuable time searching through repiar manuals, maintenance procedures, historical work orders, and troubleshoot guides. Theis slows repiars and increase down time

FleetKnowledge helps technicians find accurate answers in seconds using AI and enterprise search.

## Target Users
- Fleet Managers
- Mechanics
- Service Advisors
- Dispatchers

## MVP Features
- Secure Login
- Document Upload
- AI-powered chat
- Source Citation
- Conversation History
  
## Technolog Stack
- .Net Core
- Clean Architecture
- Github Actions
- PostgresSQL
The project was generated using the [Clean.Architecture.Solution.Template](https://github.com/jasontaylordev/CleanArchitecture) version 10.8.0.
- 
## Build

Run `dotnet build` to build the solution.

## Run

To run the application:

```bash
dotnet run --project .\src\AppHost
```

The Aspire dashboard will open automatically, showing the application URLs and logs.

## Code Styles & Formatting

The template includes [EditorConfig](https://editorconfig.org/) support to help maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs. The **.editorconfig** file defines the coding styles applicable to this solution.

## Code Scaffolding

The template includes support to scaffold new commands and queries.

Start in the `.\src\Application\` folder.

Create a new command:

```
dotnet new ca-usecase --name CreateTodoList --feature-name TodoLists --usecase-type command --return-type int
```

Create a new query:

```
dotnet new ca-usecase -n GetTodos -fn TodoLists -ut query -rt TodosVm
```

If you encounter the error *"No templates or subcommands found matching: 'ca-usecase'."*, install the template and try again:

```bash
dotnet new install Clean.Architecture.Solution.Template::10.8.0
```

## Test

The solution contains unit, integration, and functional tests.

To run the tests:
```bash
dotnet test
```

## Help
To learn more about the template go to the [project website](https://cleanarchitecture.jasontaylor.dev). Here you can find additional guidance, request new features, report a bug, and discuss the template with other users.
