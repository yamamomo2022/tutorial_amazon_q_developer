# ASP.NET Core Web Application

This is a simple ASP.NET Core MVC web application built with .NET 8. It demonstrates the basic structure and components of an ASP.NET Core application.

## Project Structure

The project follows the standard MVC (Model-View-Controller) pattern:

- **Controllers**: Handle incoming HTTP requests and return responses
- **Models**: Represent the data and business logic of the application
- **Views**: Provide the UI of the application using Razor syntax

## Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/) with C# extension

### Running the Application

1. Clone this repository
2. Navigate to the project directory
3. Run the application using the .NET CLI:

```bash
cd WebApp
dotnet run
```

4. Open your browser and navigate to `https://localhost:5001` or `http://localhost:5000`

## Features

- Basic MVC structure with Home controller and views
- Responsive layout using Bootstrap
- Error handling
- Configuration for development and production environments

## Development Environment

The application is configured with different settings for development and production environments:

- **Development**: Detailed error information, developer exception page
- **Production**: Custom error pages, no sensitive information exposed

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.