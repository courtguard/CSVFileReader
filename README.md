# Implementation details
* Target framework - .NET 8.0
* ASP.NET Core Web App (Model-View-Controller)
* Database - SQLite

# Libraries
* CSVHelper - Used for reading the records from the uploaded files. Chosen because it works great for .NET appplications and is must updated for newer versions of .NET as well.
* EntityFrameworkCore.Sqlite
* System.Data.SQLite - Chose SQLite due to the lightwieght of the db, and the ease of setup for a small project like this with no additional instalations.

# Patterns
* MVC Pattern - Widely used, has a large ecosystem and community support. Provides Separaation of Concerns, is also easily maintainable.
* Repository Pattern - decouples business logic from data access logic. Can help adhere to Single Responsibility Principle
