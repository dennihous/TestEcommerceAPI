## Creating the project:

mkdir EcommerceAPI
cd EcommerceAPI
dotnet new webapi
code .

## Create structure similar to this:

#### Adding the folders for Models, Controllers, Services, Repositories, and DTOs:

Controllers
Models
Services
Repositories
DTOs
appsettings.json
Program.cs
EcommerceAPI.csproj

builder.Services.AddScoped<IProductService, ProductService>();
builder.Services.AddScoped<IProductRepository, ProductRepository>();

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

