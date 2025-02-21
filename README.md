# Crave Food Delivery App

## Overview
A comprehensive web-based food delivery application built with ASP.NET Framework. This platform connects hungry customers with local restaurants, enabling seamless food ordering and delivery services.

## Features

- **Restaurant Browsing**
  - Search restaurants by cuisine, location, or rating
  - View detailed restaurant menus and prices
  - Read customer reviews and ratings

- **Order Management**
  - Real-time order tracking
  - Multiple payment options
  - Order history and favorites
  - Special instructions for orders

- **User Features**
  - Secure user registration and authentication
  - Profile management
  - Address book functionality
  - Order history tracking

- **Payment Processing**
  - Secure payment gateway integration
  - Multiple payment methods supported
  - Order total calculation with taxes and delivery fees

## Tech Stack

- **Backend**
  - ASP.NET Framework 4.8
  - C# programming language
  - SQL Server Database
  - Entity Framework

- **Frontend**
  - HTML5/CSS3
  - Bootstrap 4.6
  - JavaScript/jQuery
  - Font Awesome 4.7.0

## Prerequisites

- Visual Studio 2017 or later
- .NET Framework 4.8 SDK
- SQL Server 2016 or later
- IIS Express (included with Visual Studio)
- Node.js (for package management)

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Vrajpatel2912/CraveFoodDeliveryApp.git
   cd CraveFoodDeliveryApp
   ```

2. **Database Setup**
   - Open SQL Server Management Studio
   - Execute the Database script
   - Update connection string in `Web.config`

3. **Application Setup**
   - Open `CraveFoodDeliveryApp.sln` in Visual Studio
   - Right-click on solution and select "Restore NuGet Packages"
   - Build the solution (Ctrl + Shift + B)

## Running the Application

1. In Visual Studio:
   - Press F5 to run with debugging
   - Press Ctrl + F5 to run without debugging
   - Access the application at `http://localhost:63538/`

2. Default Admin Credentials:
   - Username: admin@crave.com
   - Password: Admin123!

## Project Structure

```
CraveFoodDeliveryApp/
├── App_Start/          # Application configuration
├── Controllers/        # MVC Controllers
├── Models/            # Data models and ViewModels
├── Views/             # Razor views
├── Scripts/           # JavaScript files
├── Content/           # CSS and static files
├── App_Data/          # Application data
└── Tests/             # Unit tests
```

## Deployment

1. **Publishing to IIS**
   - Right-click on project in Solution Explorer
   - Select "Publish"
   - Follow the deployment wizard

2. **Database Migration**
   - Update connection strings
   - Run Entity Framework migrations
   - Verify database integrity

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## Authors

1. Vraj Patel - [Vrajpatel2912](https://github.com/Vrajpatel2912)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


**Why I Choose This License?**
A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.
