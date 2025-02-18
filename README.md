Creating the project:

dotnet new webapi -n EcommerceAPI
cd EcommerceAPI

Installing Entity framework core and SQL server provider:

dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools
dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer

Create main framework for project:
Folders of:

Controllers
Models
Data
Services
Repositories

