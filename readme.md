# Overview

This repository was created for the purpose of comparing Blazor WASM projects created with the *dotnet*.

## Build Instructions

```powershell
dotnet new gitignore
dotnet new blazorwasm --hosted --auth Individual --pwa --output Hosted --name Hosted
dotnet new blazorwasm --auth Individual --pwa --name Auth-PWA
dotnet new blazorwasm --auth Individual --name Auth
git add .
```
