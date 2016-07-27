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

For more info https://docs.asp.net/en/latest/intro.html
