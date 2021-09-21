# CORS
* Stands for Cross Origin Resource Sharing (CORS).
* Using CORS, a server can explicitly allow some cross-origin requests while rejecting others

## To register/enable CORS we are going to use EnableCorsAttribute class and it takes three params.
* **Origins:** Here, we need to set Origins which means from which domain the requests will accept. If you have more than one domain, then you can set as comma separated. Additionally if you want any domain request to be accepted then use wild card as "*".
*  **Request Headers:** The Request header parameter specifies which Request headers are allowed. To allow any header set value to "*".
*  **HTTP Methods:** The methods parameter specifies which HTTP methods are allowed to access the resource. Use comma-separated values when you have multiple HTTP methods like "get,put,post". To allow all HTTP methods, use the wildcard value "*".

# Asp.Net v/s Asp.Net Core

|  .NET FRAMEWORK                                      |         .NET CORE                                                                   |
|------------------------------------------------------|-------------------------------------------------------------------------------------|
| Old Framework                                        | new Framework                                                                       |
| Asp.Net has good performance                         | .Net Core gives 4 times the high performanace                                       |
| Supports WebForms,MVC,WebApi                         | Supports WebForms,MVC,WebApi and Asp.Net Webpages originally added in .Net core 2.0 |
| We need to Re-Compile the code after the code change | core browser refresh will compile and execute the code with no need for re-compile  |
| Supports only Windows                                | It is a cross platform,It supports windows,mac and Linux                            |


# Asp.Net MVC v/s Asp.Net Core
| Criteria                       | ASP.NET MVC                                      | ASP.NET Core                                                            |
|--------------------------------|--------------------------------------------------|-------------------------------------------------------------------------|
| platform support               |  Windows only                                    | Windows,Linux,Mac OS                                                    |
| performance                    | high performing Framework                        | Demonstrated a better performance than ASP.NET                          |
| dependencies                   | more dependencies, less monitoring options       | A stricter control over the number od dependies                         |
| architecture                   | Based on .net framework only                     | Based on .net framework and core framework                              |
| Isolation, models, containers  | Low level of isolation,not highly suitable  for microservice,and container developement     |   Improved modular support,integration with docker,powerful isolatiion algorithms |
|  Visual Studio support         | support all version                              | only the latest versions are supported starting from 2015               |
