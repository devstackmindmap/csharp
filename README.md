[Link]

- C# https://learn.microsoft.com/ko-kr/dotnet/csharp/
- LINQ https://github.com/dotnet/try-samples

1. Make Solution
dotnet new sln -n "SolutionName"

2. Make Project
dotnet new console -n "ProjectName"

3. Build and Run
dotnet run

4. Build
dotnet build

5. Add Project in solution
dotnet sln "SolutionName" add "ProjectName\ProjectName.csproj


# Entity Framework

In Package Management Console
- Add-Migration InitialCreate
- Update-Database
- Add-Migration Rating(arbitrary name)
- Update-Database