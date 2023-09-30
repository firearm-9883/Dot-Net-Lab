# Dot-Net-Lab
#lab 1: Setup Environment

Activities:
Setup Environment

• Open the integrated terminal.
• Change directories (cd) to the folder that will contain the project folder.
• Run the following commands:
.NET Core CLI
dotnet new webapi -o TodoApi
cd TodoApi
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.InMemory
code -r ../TodoApi
• When a dialog box asks if you want to add required assets to the project,
select Yes.
The preceding commands:
o Creates a new web API project and opens it in Visual Studio Code.
o Adds the NuGet packages which are required in the next section.

URL: 
http://localhost:5225/WeatherForecast

output: 
[{"date":"2023-10-01","temperatureC":29,"temperatureF":84,"summary":"Balmy"},{"date":"2023-10-02","temperatureC":10,"temperatureF":49,"summary":"Sweltering"},{"date":"2023-10-03","temperatureC":-12,"temperatureF":11,"summary":"Cool"},{"date":"2023-10-04","temperatureC":11,"temperatureF":51,"summary":"Chilly"},{"date":"2023-10-05","temperatureC":-16,"temperatureF":4,"summary":"Freezing"}]
