# MexCoreWebAPI - ASP.NET Core Web API

Modern **ASP.NET Core 6** Web API providing backend services for hotel/travel platform integrations.

## Overview
RESTful API project used as a service layer for client applications (web/admin/mobile). Focused on clean API structure, SQL-backed data access, and deployable .NET Core hosting.

## Key Features
- ASP.NET Core Web API endpoints
- Service-oriented backend for hotel/travel domain operations
- Configurable environment settings via `appsettings`
- Compatible with IIS / Kestrel hosting

## Tech Stack
- **Framework:** .NET 6 (`net6.0`)
- **Language:** C#
- **Style:** ASP.NET Core Web API
- **Solution:** `MexCoreWebAPI.sln`

## Getting Started
1. Open `MexCoreWebAPI.sln` in Visual Studio / VS Code
2. Update `appsettings.json` for DB and secrets
3. `dotnet restore`
4. `dotnet run --project MexCoreWebAPI`

## Security Note
Do not commit production connection strings or API keys. Use User Secrets or environment variables.

## Author
**Zubair Hussain** - Senior .NET Solutions Architect
GitHub: [@expertcoder1988](https://github.com/expertcoder1988) | [LinkedIn](https://linkedin.com/in/zubairsoftware)
