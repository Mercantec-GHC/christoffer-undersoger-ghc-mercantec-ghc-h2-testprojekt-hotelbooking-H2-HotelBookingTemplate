# H2 Project {Insert Group Name}

This is where all information about your project should be. All your OOP classes, diagrams (UML, database, etc.), Blazor code, and API code.  
The project can be found here - [H2 Project Progress on Notion](Link to Notion)

It is divided into 5 folders:

## [Blazor](Link to GitHub)
This is the majority of your project, containing all the UI.  
The Blazor version has now been updated to .NET 8.0, which is LTS.

## [DomainModels](Link to GitHub)
This folder contains all your classes, which are needed for your Blazor and API projects.  
The Domain Models/Class Library version has now been updated to .NET 8.0, which is LTS.

## [Documentation](Link to GitHub)
This folder is mostly empty because you need to fill it with documentation from your project!  
It should include your UML diagram, either just the latest version or all versions.  
Your database diagram created with [DrawSQL.app](drawsql.app) or another tool should also be included.

## [API](Link to GitHub)
This folder contains your API, which is used to securely connect to your database and to feed data to your Blazor project.  
The ASP.NET Core Web API version has now been updated to .NET 8.0, which is LTS.
However, we are <strong>not</strong> using the Native AOT version with ahead-of-time compilation!

## [SQL Scripts](Link to GitHub)
We need to write scripts to query our database, which can either be hosted locally or on a cloud platform.  
It is important to save these scripts in this folder as `.SQL` files.  
They can be executed with many GUIs.  
[TablePlus](https://tableplus.com/) and [HeidiSQL](https://www.heidisql.com/) are great options!
