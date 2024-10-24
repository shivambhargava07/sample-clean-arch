# sample-clean-arch
This repository is meant for clean architecture setup using realworld example.

## Commands to setup project from scratch in vscode

1. Make sure to run below commands from **src** folder level

    `
    dotnet new sln -n cleanarch
    dotnet new webapi -n Api
    dotnet new classlib -n Application
    dotnet new classlib -n Infrastructure
    dotnet sln .\cleanarch.sln add .\Api\Api.csproj 
    dotnet sln .\cleanarch.sln add .\Application\Application.csproj
    dotnet sln .\cleanarch.sln add .\Infrastructure\Infrastructure.csproj
	
	
## This is the reference clean architecture template to start with
    `