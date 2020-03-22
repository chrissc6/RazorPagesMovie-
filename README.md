# RazorPagesMovie-

Tutorial: Create a Razor Pages web app with ASP.NET Core
https://docs.microsoft.com/en-us/aspnet/core/tutorials/razor-pages/?view=aspnetcore-3.1

Package Manager Console (PMC) commands:
Add-Migration InitialCreate
Update-Database
Add-Migration Rating
Update-Database
Add-Migration New_DataAnnotations
Update-Database


The scaffolding engine did a lot of work

The Movie property uses the [BindProperty] attribute to opt-in to model binding.

The RazorPagesMovieContext object handles the task of connecting to the database and mapping Movie objects to 
database records. 
The database context is registered with the Dependency Injection container in the ConfigureServices method in Startup.cs
