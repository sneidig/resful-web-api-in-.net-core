# RoyalVilla API

A RESTful Web API built with ASP.NET Core and C# for managing villas and villa
bookings, created as a hands-on project to practice modern .NET API development.

## Tech Stack
- C# / ASP.NET Core Web API
- Entity Framework Core
- SQL Server
- AutoMapper

## Features
- Full CRUD endpoints for Villa and VillaNumber resources
- DTOs with AutoMapper for clean separation between domain models and API contracts
- Repository pattern for data access
- API versioning
- Standardized responses and error handling
- Async/await throughout

## Getting Started
1. Clone the repo:
   `git clone https://github.com/sneidig/restful-web-api-in-.net-core.git`
2. Update the connection string in `appsettings.json` to your SQL Server instance.
3. Apply the database migrations:
   `dotnet ef database update`
4. Run the API:
   `dotnet run`
5. Open Swagger at `https://localhost:<port>/swagger` to explore the endpoints.
