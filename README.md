Make sure you have the latest Version of Angular:16, Asp.Net Core, and SQLClient installed
First of all create a folder Todo and then open it..
again create 2 folders in it... namely TodoApp.API and TodoApp.UI and unzip the TodoApp.API in TodoApp.API 
and about TodoApp.UI .. here is the google drive link to download TodoApp.UI:  https://drive.google.com/file/d/1AHJSjckdLeNiCalOs69I5G5FSiA8eTeY/view?usp=sharing
extract all the file in respected folder ....open the TodoApp.API in Visual Studio and open the TodoApp.UI in VS Code and for backend SQL Server is need .. 
I prefer to download Microsoft SQL Server 2022  and SQL Server Management Studio (SSMS)... and create connection with device name.. and
after that open the TodoApp.API in Visual Studio... 
go to file appsettings.json .. here update the server name with your connection name which you used in SSMS to create connection
Go to Tools>>NuGet Package Manager>>Package Manager Console.. Type Update-Database.. then database will be connected to .net.. and then run the code in a browser
after that open TodoApp.UI and create new terminal(powershell or cmd) if you installed angular.js you can type ... ng serve -o
..
DEMO:
https://github.com/Madhuvan143/todolist-backend-.net-and-angular.js-frontend/assets/142998619/4dfa8958-ea0d-44b4-be0f-805ceae57100
