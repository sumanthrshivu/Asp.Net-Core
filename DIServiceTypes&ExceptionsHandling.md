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
