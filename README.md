# Infinity Beauty — Spa & Wellness Management System

**Full-Stack Application | ASP.NET Core Web API · ASP.NET MVC · .NET MAUI · SQL Server**

Infinity Beauty is a full-stack management application designed for a beauty, spa and wellness centre. It brings together appointment scheduling, service management, customer information and administrative operations through an integrated software solution.

## Project Overview

The solution consists of three applications:

- **REST API:** ASP.NET Core backend responsible for business logic, data access and communication with client applications.
- **Web Application:** ASP.NET Core MVC interface for interacting with the management system.
- **Mobile Application:** .NET MAUI application that integrates with the backend.

## Main Features

- User registration, authentication and role-based access
- Service and category management
- Appointment booking and management
- Employee and customer management
- Employee availability management
- Administrative dashboards and reporting
- Billing and financial information

## Technology Stack

| Layer | Technologies |
|---|---|
| Backend | C#, ASP.NET Core Web API |
| Web | ASP.NET Core MVC, Razor, HTML, CSS, JavaScript |
| Mobile | .NET MAUI |
| Database | Microsoft SQL Server |
| Data Access | Entity Framework Core |
| Architecture | REST APIs, Dependency Injection, layered application structure |

## Solution Structure

```text
InfinityBeauty/
├── ProjetoFinalCet105.API/
├── ProjetoFinalCet105.Web/
├── ProjetoFinalCet105.Mobile/
└── ProjetoFinalCet105.API.slnx
```

The applications communicate through the REST API, which centralizes backend operations and database access.

## Project Highlights

This project demonstrates practical experience in full-stack C#/.NET development, including backend services, relational databases, web interfaces, mobile integration and role-based application workflows.

### Running the Application

1. Clone the repository:

   ```bash
   git clone https://github.com/rde-espi/InfinityBeauty.git
   ```

2. Open `ProjetoFinalCet105.API.slnx` in Visual Studio.

3. Configure the SQL Server connection string and the required application settings.

4. Restore NuGet packages and prepare the database using Entity Framework Core migrations.

5. Configure the API endpoints used by the Web and Mobile applications.

6. In Visual Studio, right-click the solution and select **Configure Startup Projects**.

7. Select **Multiple startup projects** and configure all three projects to start:
   - `ProjetoFinalCet105.API`
   - `ProjetoFinalCet105.Web`
   - `ProjetoFinalCet105.Mobile`

8. Select a compatible target device or emulator for the .NET MAUI application.

9. Run the solution to launch the API, Web and Mobile applications together.

**Note:** The applications require correctly configured API endpoints, database connectivity and a compatible mobile development environment.

## Author

**Reinaldo Espindola Souza**

[LinkedIn](https://www.linkedin.com/in/reinaldoespindolasouza) | [GitHub](https://github.com/rde-espi)

*Developed as an individual software development project.*
