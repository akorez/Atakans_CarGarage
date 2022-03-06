

Application Pre Requirements

1) .Net Core 5.0
2) Angular CLI: 11.2.3


Application Running Steps:

a) Clone the current repo from GitHub.

(Back-End)
a) Set the SQL Server Connection String in 'appsettings.Development.json' and 'appsettings.json' files.
b) Navigate to 'CarGarageBackEnd' Folder in CMD
c) run the command -> dotnet restore
d) run the commad -> dotnet ef database update
e) run the command -> dotnet run

(Front-End)
a) Navigate to 'CarGarageFrontEnd' Folder in CMD
b) run the command -> npm install
c) run the command -> ng serve
d) open broser on localhost:4200

(Back-End Unit-Test)
a) Navigate to 'CarGarageBackEnd.Tests' Folder in CMD
b) run the command -> dotnet restore
c) run the command -> dotnet test



You can access Admin Page from "/login" 
Username : Admin
Password: password
