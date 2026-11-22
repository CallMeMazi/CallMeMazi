<p align="center">
  <img src="banner.svg" alt="Maziyar — backend developer, ASP.NET Core" width="100%">
</p>

<p align="center">
  I build backends in C# and ASP.NET Core.<br>
  بک‌اند را با قانون‌های روشن و دادهٔ قابل‌اعتماد می‌سازم.
</p>

## Selected work

### [TaskManagement API](https://github.com/CallMeMazi/TaskManagement-API)

Collaborative work for organizations, projects, and tasks, on .NET 10.

Entities enforce their own rules. Use cases go through MediatR, with FluentValidation in front of a transaction pipeline on writes. Entity Framework Core keeps the application in SQL Server and writes logs to a second database. Access tokens are signed and encrypted, and each device session rotates its own refresh token.

<p>
  <img alt="C#" src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white">
  <img alt=".NET 10" src="https://img.shields.io/badge/.NET-10-512BD4?style=flat-square&logo=dotnet&logoColor=white">
  <img alt="MediatR" src="https://img.shields.io/badge/MediatR-CQRS-0A7EA4?style=flat-square">
  <img alt="EF Core and SQL Server" src="https://img.shields.io/badge/EF%20Core-SQL%20Server-512BD4?style=flat-square&logo=microsoftsqlserver&logoColor=white">
  <img alt="Serilog" src="https://img.shields.io/badge/Serilog-logs-4B4B4B?style=flat-square">
</p>

### [PersonalFinance](https://github.com/CallMeMazi/PersonalFinance)

A local personal-finance application on ASP.NET Core MVC. The interface is Persian and right to left. Weeks run from Saturday to Friday, and reports use the Jalali calendar. Income for a period is hours times the rate stored on that entry, so changing today's rate does not rewrite the past. A category budget is a share of realized income, kept separate from the expense itself.

<p>
  <img alt=".NET 8" src="https://img.shields.io/badge/.NET-8-512BD4?style=flat-square&logo=dotnet&logoColor=white">
  <img alt="ASP.NET Core MVC" src="https://img.shields.io/badge/ASP.NET%20Core-MVC-512BD4?style=flat-square&logo=dotnet&logoColor=white">
  <img alt="SQL Server" src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white">
  <img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-5%20RTL-7952B3?style=flat-square&logo=bootstrap&logoColor=white">
</p>

## How I build

- Rules live on the domain model. Handlers orchestrate a use case; they do not invent policy.
- A write is validated before it opens a transaction. Application data and logs stay on separate databases.
- When a person uses the product, the screen gets the same care as the endpoint. PersonalFinance does its date math and its money math in the open.

## Stack

| Area | Tools |
|---|---|
| Language | C# |
| Web | ASP.NET Core, MVC, OpenAPI, Scalar |
| Application | MediatR, FluentValidation, AutoMapper |
| Data | Entity Framework Core, SQL Server |
| Operations | Serilog, JWT sessions, problem details |

<p align="center">
  <a href="https://github.com/CallMeMazi?tab=repositories">All repositories</a>
</p>
