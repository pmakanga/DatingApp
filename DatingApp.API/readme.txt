DotNet Commands
==============

Check Version
================
dotnet --version

CLI commands
============
dotnet -h

Contextual help to build a new .net project
===========================================
dotnet new -h

Create a new api project
========================
dotnet new webapi -o DatingApp.API -n DatingApp.API

C# Extensions for vs code
========================
1. C# for visual studio code (powered by OmniSharp)
2. C# Extensions
3. Nuget Package Manager

Angular Extensions for vs code
=============================
1. Angular v7 Snippets
2. Angular Files
3. Angular Language Service
4. angular2-switcher
5. Auto Rename Tag
6. Bracket Pair Colorizer
7. Debugger for Chrome
8. Material Icon Theme
9. Path Intellisense

Run application
==============
dotnet run

Run application with watch
===========================
dotnet watch run - watch file changes while running

Entity Framework commands
=========================
dotnet ef -h

Add migrations
==============
dotnet ef migrations add InitialCreate

Update Database
==============
dotnet ef database update

npm Install Bootstrap and font-awesome
======================================
npm install bootstrap font-awesome

Check git status
================
git status

Initialize git
==============
git init

Stage Changes locally
======================
Under source control click stage + button

Production build with Angular CLI
================================
under angular.json in order to run with the kestrel server
for the API, change the outputPath to "outputPath": "../DatingApp.API/wwwroot"

then run
ng build

Get ksetrel server to serve angular app within the API
======================================================
Changes to Startup.cs

build for Production
===================
apiUrl: 'api/' --add this code to environment.prod.ts
ng build --prod

build with build-optimizer switched off
=======================================
This is in case you loose out on css functionality due to file minification
-build optimizer is turned on by default
-turning off build optimizer increases the file sizes but optimizes on css
ng build --prod --build-optimizer=false

set development environment to production
==========================================
console - set ASPNETCORE_ENVIRONMENT=Production
powershell - Env:ASPNETCORE_ENVIRONMENT = "Production"
add migrations - dotnet ef migrations add sqlInitial

DotNet Publish
==============
dotnet publish -o /d/Projects/hosting/datingapp

Dotnet database drop
====================
dotnet ef database drop

Dotnet ef remove migrations
===========================
dotnet ef migrations remove


