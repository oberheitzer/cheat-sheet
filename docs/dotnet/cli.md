# Frequently used commands of .NET CLI

[Official documentation of the CLI with all the available commands.](https://learn.microsoft.com/en-us/dotnet/core/tools/)

Creation of a solution file in the current folder/repository with the name switch. Useful when the name of the solution is different than the name of the folder.
```
dotnet new sln --name [name of the solution]
```
Creation of a console project with the output directory switch.
```
dotnet new console -o [name of the folder/location of the console project]
```
Creation of a class library with the output directory switch.
```
dotnet new classlib -o [name of the folder/location of the class library/project]
```
Add a project to the solution.
```
dotnet sln add [location of the project]
```
