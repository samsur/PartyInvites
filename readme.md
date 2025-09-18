# PartyInvites

A modern ASP.NET Core MVC web application built with .NET 9.0. This project provides a foundation for managing party invitations with a clean, responsive interface.

## Features

- **Modern ASP.NET Core MVC Architecture**: Built on .NET 9.0 with the latest framework features
- **Responsive Design**: Bootstrap-powered UI that works on desktop and mobile devices
- **Clean Code Structure**: Well-organized MVC pattern with separation of concerns
- **Development Ready**: Configured for easy development and debugging

##  Technology Stack

- **Framework**: ASP.NET Core 9.0
- **Pattern**: Model-View-Controller (MVC)
- **Frontend**: Bootstrap 5, jQuery
- **Language**: C# with nullable reference types enabled
- **Runtime**: .NET 9.0

##  Project Structure

```
PartyInvites/
├── Controllers/           # MVC Controllers
│   └── HomeController.cs  # Main application controller
├── Models/               # Data models and view models
│   └── ErrorViewModel.cs # Error handling model
├── Views/                # Razor views and layouts
│   ├── Home/            # Home controller views
│   │   ├── Index.cshtml # Landing page
│   │   └── Privacy.cshtml # Privacy policy page
│   └── Shared/          # Shared layouts and partials
│       ├── _Layout.cshtml # Main layout template
│       └── Error.cshtml   # Error page template
├── wwwroot/             # Static web assets
│   ├── css/            # Custom stylesheets
│   ├── js/             # Custom JavaScript
│   └── lib/            # Third-party libraries
├── Properties/          # Launch and build configurations
└── Program.cs          # Application entry point
```

##  Getting Started

### Prerequisites

- [.NET 9.0 SDK](https://dotnet.microsoft.com/download/dotnet/9.0) or later
- A code editor (Visual Studio, Visual Studio Code, or JetBrains Rider)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/samsur/PartyInvites.git
   cd PartyInvites
   ```

2. **Restore dependencies**
   ```bash
   dotnet restore
   ```

3. **Build the project**
   ```bash
   dotnet build
   ```

4. **Run the application**
   ```bash
   dotnet run
   ```

5. **Access the application**
   
   Open your browser and navigate to: `http://localhost:5279`

## Development

### Running in Development Mode

The application is configured to run in development mode by default, which includes:
- Detailed error pages
- Hot reload capabilities
- Development-specific logging

### Project Configuration

- **Launch Settings**: Configure ports and environment variables in `Properties/launchSettings.json`
- **App Settings**: Modify application configuration in `appsettings.json` and `appsettings.Development.json`
- **Global Settings**: .NET SDK version specified in `global.json`

### Key Features

- **Logging**: Built-in logging with configurable levels
- **Error Handling**: Comprehensive error handling with custom error pages
- **Static Assets**: Optimized static file serving with versioning
- **Routing**: Conventional MVC routing with default patterns

## 📝 Available Routes

- `/` or `/Home` - Landing page
- `/Home/Privacy` - Privacy policy page
- `/Home/Error` - Error handling page

## Customization

### Adding New Features

1. **Controllers**: Add new controllers in the `Controllers/` folder
2. **Models**: Create data models in the `Models/` folder  
3. **Views**: Add corresponding views in the `Views/[ControllerName]/` folder
4. **Styles**: Add custom CSS in `wwwroot/css/site.css`
5. **Scripts**: Add custom JavaScript in `wwwroot/js/site.js`

### Styling

The application uses Bootstrap 5 for styling. You can:
- Modify the main stylesheet: `wwwroot/css/site.css`
- Update the layout template: `Views/Shared/_Layout.cshtml`
- Add custom Bootstrap themes or components

##  Build and Deployment

### Build for Production

```bash
dotnet publish -c Release -o ./publish
```

### Configuration for Production

Update `appsettings.json` for production settings:
- Set appropriate logging levels
- Configure connection strings
- Update allowed hosts

## 📚 Learn More

- [ASP.NET Core Documentation](https://docs.microsoft.com/en-us/aspnet/core/)
- [MVC Pattern in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/overview)
- [Bootstrap Documentation](https://getbootstrap.com/docs/)

## 📄 License

This project is part of the Sheridan College PROG30000 course curriculum.

---

**Course**: PROG30000 - Fall 2025  
**Institution**: Sheridan College