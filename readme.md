# Automated Trigger Pipeline Azure (ASP.NET Core Razor Pages)

A professional full-stack project demonstrating an **ASP.NET Core Razor Pages** web application integrated with **Azure DevOps CI/CD pipelines** for automated build and trigger workflows.

## 🚀 Project Overview
This repository contains a modular .NET Core web application paired with an automated build and release pipeline. Every time code changes are committed and pushed, Azure DevOps automatically detects the trigger, builds the solution, and validates the deployment process.

## 🛠️ Tech Stack & Architecture
* **Framework:** ASP.NET Core (.NET / C#)
* **UI Pattern:** Razor Pages (`.cshtml` pages with code-behind `.cs` logic)[cite: 5]
* **CI/CD & DevOps:** Azure DevOps Pipelines (Automated Triggers)
* **Version Control:** Git, GitHub, and Azure Repos
* **IDE:** Visual Studio[cite: 5]

## 📁 Repository Structure
```text
Automated trigger pipeline azure/
│── Pages/             # Razor view templates and page models (Index, Privacy, Error)[cite: 5]
│── Properties/        # Launch and hosting configurations (launchSettings.json)[cite: 5]
│── wwwroot/           # Static web assets (CSS styling, JavaScript, and libraries)[cite: 5]
│── Program.cs         # Application entry point, services, and endpoint routing configuration[cite: 5]
│── WebApplication1.csproj # Core C# project configuration file[cite: 5]
└── README.md          # Project documentation
