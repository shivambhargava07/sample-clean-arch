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
`
## Pushed to this repo via below commands

### Add your files
1. git add .
    `
### Commit it locally
2. git commit -m "initial commit"

### Push it to respective branch
3. git push origin master

### Way branch locally and checkout from current branch
4. git checkout -b feature/archtemplate

### Fetch all branches from remote repository
5. git fetch --all

### List all branches locally
6. git branch --all

### Checkout exisiting branch
7. git checkout feature/exisiting-branch
