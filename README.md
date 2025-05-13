# MyApp - API .NET com Oracle

Esta API permite gerenciar produtos com conexão a banco de dados Oracle.

## 🚀 Rotas

- GET `/api/product`
- GET `/api/product/{id}`
- POST `/api/product`
- PUT `/api/product/{id}`
- DELETE `/api/product/{id}`

## 🛠️ Instalação

```bash
dotnet restore
dotnet ef database update -p MyApp.Infrastructure -s MyApp.WebApi
dotnet run --project MyApp.WebApi
