# ASP.NET Core Web Database Application

This project is a web database application built using ASP.NET Core, VSCode, and the C# programming language. It follows the MVC (Model-View-Controller) design pattern and demonstrates how to configure database tables using Entity Framework, create models, controllers, views, and implement a search function to filter database results.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Database Setup](#database-setup)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

## Introduction

This project is developed based on the "ASP.NET Core Crash Course - C# Applications in One Hour" by Shad Sluiter. The tutorial covers the following topics:

- Using the MVC design pattern.
- Configuring database tables using Entity Framework.
- Creating models, controllers, and views.
- Styling ASP.NET pages with CSS and Bootstrap.
- Implementing a search function to filter database results.

## Features

- MVC Architecture
- Entity Framework Core for database management
- Razor Views for dynamic web pages
- Bootstrap for responsive design
- Search functionality to filter results

## Technologies

- ASP.NET Core
- C#
- Entity Framework Core
- Razor
- Bootstrap
- CSS

## Getting Started

### Prerequisites

To run this project, you will need:

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) (or use SQLite for simplicity)

### Installation

Clone the repository:

   ```bash
   git clone https://github.com/your-username/aspnet-core-web-app.git
   cd aspnet-core-web-app
   ```

### Database Setup

Apply migrations and update the database:

   ```bash
   dotnet ef migrations add InitialCreate
   dotnet ef database update
   ```

## Usage

Run the application from VSCode by pressing `F5` or using the command:

```bash
dotnet run
```

Navigate to `https://localhost:5008` to see the application in action.

## Acknowledgements

- Course developed by Shad Sluiter. Check out his [YouTube channel](https://www.youtube.com/shadsluiter).
- [ASP.NET Core Documentation](https://docs.microsoft.com/en-us/aspnet/core/)
- [Entity Framework Core Documentation](https://docs.microsoft.com/en-us/ef/core/)