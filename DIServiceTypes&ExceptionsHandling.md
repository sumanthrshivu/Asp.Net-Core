# Dependency InjectionService Register Types in Asp.Net Core
* There are three ways by which dependencies can be registered in Startup.cs. i.e. AddSingleton, AddScoped and AddTransient.
### Add Singleton
* When we register a type as singleton, only one instance is available throughout the application and for every request.
* The instance is created for the first request and the same is available throughout the application and for each subsequent requests.
* use this  When Singleton implementation is required.
### Add Scoped
* When we register a type as Scoped, one instance is available throughout the application per request. When a new request comes in, the new instance is created. Add scoped specifies that a single object is available per request.
* use this when Applications which have different behavior per user.
### Add Transient
* When we register a type as Transient, every time a new instance is created. Transient creates new instance for every service/ controller as well as for every request and every user.
* use this when it is Light weight and stateless services.

--- 

# ASP.NET Core Error Handling
* An ExceptionFilterAttribute is used to collect unhandled exceptions. You can register it as a global filter, and it will function as a global exception handler. Another option is to use a custom middleware designed to catch unhandled exceptions.
* To handle exceptions and display user friendly messages, we need to install Microsoft.AspNetCore.Diagnostics NuGet package and add middleware in the Configure() method.
### The Microsoft.AspNetCore.Diagnostics package includes following extension methods to handle exceptions in different scenario:
* **UseDeveloperExceptionPage**:The UseDeveloperExceptionPage extension method adds middleware into the request pipeline which displays developer friendly exception detail page. This helps developers in tracing errors that occur during development phase.
* As this middleware displays sensitive information, it is advisable to add it only in development environment.
*  **UseExceptionHandler**: In MVC Core application, we might want some other controller to handle all exceptions and display custom user friendly error messages. The UseExceptionHandler extension method allows us to configure custom error handling route. This is useful when an application runs under production environment.
