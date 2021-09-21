# CORS
* Stands for Cross Origin Resource Sharing (CORS).
* Using CORS, a server can explicitly allow some cross-origin requests while rejecting others

## To register/enable CORS we are going to use EnableCorsAttribute class and it takes three params.
* **Origins:** Here, we need to set Origins which means from which domain the requests will accept. If you have more than one domain, then you can set as comma separated. Additionally if you want any domain request to be accepted then use wild card as "*".
*  **Request Headers:** The Request header parameter specifies which Request headers are allowed. To allow any header set value to "*".
*  **HTTP Methods:** The methods parameter specifies which HTTP methods are allowed to access the resource. Use comma-separated values when you have multiple HTTP methods like "get,put,post". To allow all HTTP methods, use the wildcard value "*".

# Asp.Net v/s Asp.Net Core

|           .NET FRAMEWORK                                    |                    .NET CORE                                         |
|-------------------------------------------------------------|----------------------------------------------------------------------|
| Old Framework                                               | new Framework                                                        |
|.Net Framework is a full-fledged development framework.      | .Net Core is a platform on top of which there are                    |
|The framework provides all the basic requirements for        |  frameworks such as ASP .Net Core and Universal                      |
|the development of applications – UI, DB connectivity,       |  Windows Platform that leverage and extend the                       |
| Services, APIs, etc                                         |  features of .Net Core                                               |
|  .Net Framework is used to build both                       |   .Net Core focuses more on Web,                                     |
|   Desktop as well as Web applications.                      |    Windows Mobile, and Windows Store applications.                   |
|  .Net Framework is too heavy for Command Line Interface.    |     Net Core supports a very lightweight CLI for all platforms.      |                 
|                                                             |                                                                      | 
| not open source                                             | open source                                                          |
| Supports only Windows                                       | It is a cross platform,It supports windows,mac and Linux             |
| all asp.net components asp.net web form asp.net MVC Web API | asp.net core + Universal Windows apps                                |
| Monolithic                                                  | modular LED collection                                               |
| 4.8 is the last version of .net Framework                   | 3.0 is the last version of .net core                                 |
| A high-performance and scalable system without UI           | .NET Core is much faster.                                            |
| Docker containers support                                   | Both, but .NET Core is born to live in a container.                  |
| Stable version for an immediate need to build and deploy    | .NET Framework has been around since 2001. .NET Core is just a baby. |
# Asp.Net MVC v/s Asp.Net Core
| Criteria                       | ASP.NET MVC                                      | ASP.NET Core                                                            |
|--------------------------------|--------------------------------------------------|-------------------------------------------------------------------------|
| platform support               |  Windows only                                    | Windows,Linux,Mac OS                                                    |
| performance                    | high performing Framework                        | Demonstrated a better performance than ASP.NET                          |
| dependencies                   | more dependencies, less monitoring options       | A stricter control over the number od dependies                         |
| architecture                   | Based on .net framework only                     | Based on .net framework and core framework                              |
| supported files                | WCF,WF,WPF,VB,Web Config and others              | no support for global.asax files and web config. but appsettings.json is integrated  |     
| Isolation, models, containers  | Low level of isolation,not highly suitable  for microservice,and container developement     |   Improved modular support,integration with docker,powerful isolatiion algorithms |
|  Visual Studio support         | support all version                              | only the latest versions are supported starting from 2015               |
