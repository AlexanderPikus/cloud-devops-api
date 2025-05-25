# Cloud & DevOps Sample Project – ASP.NET Core API

This project showcases a cloud-native microservice built with ASP.NET Core, containerized using Docker, and deployed to Azure App Service using GitHub Actions.

## Features

- ✅ ASP.NET Core 7.0 Web API
- ✅ RESTful endpoints with Swagger documentation
- ✅ SQL Server integration using Entity Framework Core
- ✅ Docker containerization with multi-stage build
- ✅ GitHub Actions CI/CD pipeline
- ✅ Azure App Service deployment via ARM template

## Tech Stack

- C# / .NET 7
- Entity Framework Core
- SQL Server
- Docker
- GitHub Actions
- Azure App Service

## Project Structure

loud-devops-api/
│
├── .github/workflows/ # GitHub Actions CI/CD pipeline
├── CloudApi/ # ASP.NET Core Web API project
├── CloudApi.Tests/ # Unit tests (xUnit)
├── Dockerfile # Container build definition
├── azure-pipeline.yml # Azure-specific deployment configs
└── README.md # You're here!

shell
Copy
Edit
This project is licensed under the MIT License.

