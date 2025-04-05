# MeritoWebApp

MeritoWebApp is an ASP.NET Core MVC application designed to demonstrate the structure and functionality of a typical web application. 

## Project Structure

- **Controllers**: Contains the controllers that handle user requests and return responses.
  - `HomeController.cs`: Manages the home page and about page requests.

- **Models**: Contains the data models used in the application.
  - `ExampleModel.cs`: Defines the data structure for the application.

- **Views**: Contains the Razor views that render the user interface.
  - **Home**: Contains views related to the home page.
    - `Index.cshtml`: The homepage view.
    - `About.cshtml`: The about page view.
  - **Shared**: Contains shared views and layout.
    - `_Layout.cshtml`: The layout view for consistent page structure.
    - `_ViewStart.cshtml`: Sets the layout for the views.

- **wwwroot**: Contains static files such as CSS, JavaScript, and third-party libraries.
  - **css**: Contains stylesheets.
    - `site.css`: The main stylesheet for the application.
  - **js**: Contains JavaScript files.
    - `site.js`: The main JavaScript file for the application.
  - **lib**: Intended for third-party libraries and dependencies.

- **Configuration Files**:
  - `appsettings.json`: Contains application configuration settings.
  - `Program.cs`: The entry point of the application.
  - `Startup.cs`: Configures services and the request pipeline.

## Getting Started

To run the application, ensure you have the .NET SDK installed. Clone the repository and run the following commands:

```bash
dotnet restore
dotnet run
```

Visit `http://localhost:5000` in your browser to view the application. 

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements. 

## License

This project is licensed under the MIT License.