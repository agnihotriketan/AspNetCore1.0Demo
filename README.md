# AspNetCore1.0Demo

ASP.NET Core is a new open-source and cross-platform framework for building modern cloud based internet connected applications, such as web apps, IoT apps and mobile backends. ASP.NET Core apps can run on .NET Core or on the full .NET Framework. It was architected to provide an optimized development framework for apps that are deployed to the cloud or run on-premises. It consists of modular components with minimal overhead, so you retain flexibility while constructing your solutions. You can develop and run your ASP.NET Core apps cross-platform on Windows, Mac and Linux. ASP.NET Core is open source at GitHub.

#Getting Started 

1.Install .NET Core --https://microsoft.com/net/core

2.Create a new .NET Core project:
mkdir aspnetcoreapp
cd aspnetcoreapp
dotnet new
Update the project.json file to add the Kestrel HTTP server package as a dependency:
 
3.Restore the packages:
dotnet restore
Add a Startup.cs file that defines the request handling logic:
 
4.Update the code in Program.cs to setup and start the Web host:
 
5.Run the app (the dotnet run command will build the app when it’s out of date):
dotnet run
Browse to http://localhost:5000:


#With ASP.NET Core you gain the following foundational improvements:

* A unified story for building web UI and web APIs
* Integration of modern client-side frameworks and development workflows
* A cloud-ready environment-based configuration system
* Built-in dependency injection
* New light-weight and modular HTTP request pipeline
* Ability to host on IIS or self-host in your own process
* Built on .NET Core, which supports true side-by-side app versioning
* Ships entirely as NuGet packages
* New tooling that simplifies modern web development
* Build and run cross-platform ASP.NET apps on Windows, Mac and Linux
* Open source and community focused

For more info https://docs.asp.net/en/latest/intro.html
