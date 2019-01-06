# zsq.MvcWithEf
dotnet core Mvc and Ef Demo


1.dotnet new mvc -au Individual -uld --name zsq.MvcWithEf

2.cd zsq.MvcWithEf

3.dotnet ef database update

/////////////////////////////////////

vscode ef powershell

dotnet ef migrations add xxx ----Add-Migration

dotnet ef database update	---Update-Database

dotnet ef migrations remove	----Remove-Migration

dotnet ef database update lastMigration	----Update-Database lastMigration

dotnet ef migrations script ----Script-Migration
