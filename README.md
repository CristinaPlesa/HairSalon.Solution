# Hair Salon

#### By Cristina Plesa

#### A C# application that 

## Technologies Used

* C#
* .NET 5 SDK
* VS Code
* MySQL Workbench
* License
* MIT License.

## Setup and Use

### Prerequisites

* .NET 5 SDK
* MySQL Workbench
* A text editor like VS Code
* A command line interface like Terminal or GitBash to run and interact with the console app.

### Installation

1. Clone the repository: $ git clone {https://github.com/CristinaPlesa/HairSalon.Solution}
2. Navigate to the {HairSalon.Solution} directory on your computer
3. Open with your preferred text editor to view the code base

4. To run the console app:
  * Navigate to {HairSalon.Solution/HairSalon} in your command line
  * Run the command dotnet restore to restore the dependencies that are listed in {HairSalon.csproj}
  * Run the command dotnet build to build the project and its dependencies into a set of binaries
  * Finally, run the command dotnet run to run the project!
  * Note: dotnet run also restores and builds the project, so you can use this single command to start the console app

  <!-- // THIS IS THE MOST IMPORTANT STEP, AND IT’S NEW. YOU MUST TELL US HOW TO SET UP YOUR DATABASE -->

5. Create a database using SQL via MySQL:
   
> `CREATE DATABASE <firstname_lastname>;`
> `USE <firstname_lastname>;`
> `CREATE TABLE <tablename> (<column/property information>);`
> `CREATE TABLE <tablename> (<column/property information>);`
      ` ….(more if there are more!)`

## Known Bugs

* No known bugs

## License

[MIT](https://opensource.org/licenses/MIT) Copyright (c) 2021 Cristina Plesa

## Contact Information

Please reach out through my GitHub account.
[github.com/CristinaPlesa](https://github.com/CristinaPlesa)

<!-- Index, Create, Delete, DeleteConfirm, and...
Details(), Create(), Create() (with an HttpPost), Delete(), DeleteConfirmed(), Index(), Edit(), Edit() (with an HttpPost).  -->


<!-- Don't forget to add styling at the end! 
  * also should this proxies package from Entity Framework Core be part of the instructions? : $ dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0

  * also need to add specific specialties and date of hire fields for Stylists. Do this in constructor and SQL Database.

  * Is CREATE functionality included for one class and is CREATE and VIEW functionality included for the other class? (What does this mean? Why wouldn't both classes have VIEW functionality?)

  *  instructions are given to the user on how to recreate the appsettings.json file
-->

<!-- * DON'T FORGET TO FINISH OUT YOUR README INSTRUCTIONS, ADD STYLING, AND EXPORT YOUR SQL DATABASE TO YOUR ROOT DIRECTORY :) -->