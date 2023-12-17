# Hi there
you can find me here [linekedin](https://www.linkedin.com/in/afsane-honarmand-7970b618a/)

## 1. Create Directory:
...
md FirstProject
...

## 2.Create Project Structure:
...
cd "[FirstProject]"
...

## 3.Create sln Project in src folder:
...
cd "src"
dotnet new sln -n FirstProject
...


## 4. Create Web API Project in src folder:
...
dotnet new console --name "WebApiProject"
...

## 4. Create Domain in src folder:
...
dotnet new console --name "FirstProject.Domain"
...

## 5. Create Test Directory:
...
md Tests
...

## 6. WebApiProject Test:
...
dotnet new xunit --name "WebApiProject.Tests"
cd "WebApiProject.Tests"
...

## 7. Domain Test:
...
dotnet new xunit --name "Domain.Tests"
cd "Domain.Tests"
...

## 8.Build the Project
...
dotnet build
...


## 9. Git Commit:
...
cd ..
git checkout <AfsaneHonarmand>
git add -A
git commit -m "FirstProject"
git push origin <AfsaneHonarmand>
...






