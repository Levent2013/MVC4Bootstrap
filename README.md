MVC4 Bootstrap
=============

ASP. Net MVC4 base solution with Twitter Bootstrap theme applied.

I've created this solution to avoid having to mess around with removing the bloat that MVC provides you when you start a new project.  I've also applied basic Twitter Bootstrap responsive theming to allow you to get a project up and running quickly.

I've added nuget.exe to the root folder to make it simple to download the necessary dependencies.  To download these, open a command prompt to the solution root folder and run the following command:

    nuget.exe install -o packages MVC4Bootstrap\packages.config
    
You should now be able to load the solution in Visual Studio 2012 and run it.