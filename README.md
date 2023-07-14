# asp.net-core-6.0

ASP.NET Core apps created with the web templates contain the application startup code in the Program.cs file. The Program.cs file is where:
  Services required by the app are configured.
  The app's request handling pipeline is defined as a series of middleware components.

The request handling pipeline is composed as a series of middleware components. Each component performs operations on an HttpContext and either invokes the next middleware in the pipeline or terminates the request.

ASP.NET Core supports the dependency injection (DI) software design pattern, which is a technique for achieving Inversion of Control (IoC) between classes and their dependencies.

# References
[ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/?view=aspnetcore-7.0&tabs=windows)
[Dependency injection in ASP.NET Core] (https://learn.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-7.0)
