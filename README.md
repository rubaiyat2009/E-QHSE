# E-QHSE
This is an example project to accompany Quality, Health, Safety and Environment system. 
Also, preventive maintenance system modules are available here. 
You can see in the commit history the basic steps taken to move from the previous project structure to one with a basic, but flexible Group-based security model. 

You may need to enable Nuget Package Restore in Visual Studio in order to download and restore Nuget packages during build. If you are not sure how to do this, see [Keep Nuget Packages Out of Source Control with Nuget Package Manager Restore] 
Apparrently, this is supposedly not required with Nuget anymore, but in case you need to . . .

You will also need to run Entity Framework Migrations `Update-Database` command per the article. The migration files are included in the repo, so you will NOT need to `Enable-Migrations` or run `Add-Migration Init`. 

https://github.com/rubaiyat2009/E-QHSE.git

## Getting Started 
After you've cloned the project, go ahead and restore the NuGet Packages from the solution or console. Then run the project. 
You'll be able to log in and administer the groups and roles as well as users with the "test@test.com" user.

    Username: test@test.com
    Password: Password1
    
   ## Technology Used
   ASP .NET MVC, MVVM, Knockout JS, Entity Framework (Code First), SQL
   
   ## Template Used
   Inspinia Admin template used to reduce task and focus on business logic. To host this project needs to get new template licese from:
   https://wrapbootstrap.com/theme/inspinia-responsive-admin-template-WB0R5L90S
