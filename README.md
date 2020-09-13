# BobsStoreSln
MSSA Lab1B SportsStore
This is a student excersise for the MSSA Cloud Application Developer course.
Credit for this excercise is Adam Freeman, https://www.apress.com/gp/book/9781484254394.

## Create Solution and Projects

  dotnet new globaljson --sdk-version 3.1.101 --output BobsStoreSln/OutdoorProducts
  dotnet new web --no-https --output BobsStoreSln/OutdoorProducts --framework netcoreapp3.1
  dotnet new sln -o BobsStoreSln
  dotnet sln BobsStoreSln add BobsStoreSln/OutdoorProducts 
  dotnet new xunit -o BobsStoreSln/OutdoorProducts.Tests --framework netcoreapp3.1
  dotnet sln BobsStoreSln add BobsStoreSln/OutdoorProducts.Tests 
  dotnet add BobsStoreSln/OutdoorProducts.Tests reference BobsStoreSln/OutdoorProducts 

##
