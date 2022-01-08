# .NET 5.0 Web API Authentication from Scratch

This repostitory consists of project for following aricles in my blog (originally written for .NET Core 3.1 but packages are __updated to match .NET 5.0__)

  - [.NET Core 3.0 (Preview 4) Web API Authentication from Scratch (Part 1): Up and Running.](https://medium.com/@nishancw/net-core-3-0-preview-4-web-api-up-and-running-5204ecaef0fc)
  - [.NET Core 3.0 (Preview 4) Web API Authentication from Scratch (Part 2): Password Hashing.](https://medium.com/@nishancw/net-core-3-0-preview-4-web-api-authentication-from-scratch-part-2-password-hashing-7e43b64cbe25)
  - [.NET Core 3.0 (Preview 4) Web API Authentication from Scratch (Part 3): Token Authentication](https://medium.com/@nishancw/net-core-3-0-preview-4-web-api-authentication-from-scratch-part-3-token-authentication-2d8af41b0045)

  ## Setting Up
  * Download / Clone this repository.
  * Install latest [.NET](https://dotnet.microsoft.com/download/dotnet/5.0)
  * Create new database `MyDatabase` in SQL Server.
  * Open Visual Studio Code in `WebApiCore50` folder.
  * Open integrated terminal using Ctrl+Shift+`
  * Execute command `dotnet restore` in the terminal.
  * Execute command `dotnet tool update --global dotnet-ef --version 5.0.0` in the terminal to update Entity Framework Core .NET Command-line Tools.
  * Execute command `dotnet ef database update` in the terminal. (to update the database using migrations)
  * Execute command `dotnet watch run` in the terminal.
