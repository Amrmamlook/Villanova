# Villanova Api
is a web application built on a .NET 7 . It provides a set of functionalities using Web API, Entity Framework Core, and SQL Server for managing villas. 
The project includes authentication and authorization => using JWT (JSON Web Token) for different user roles (user and admin).
# Features 
 - ### User Management:
- Users can register and log in using authentication with ** JWT **.
- Different user roles (user and admin) with corresponding authorization actions.
 ### Villa Controller:
- CRUD operations (Create, Read, Update, Delete,Patch) for managing villa data.
- Authorization checks based on user roles for each action.
 ### VillaNumber Controller :
  - Similar CRUD operations for managing villa numbers.
  - Authorization checks based on user roles for each action.
   
 ### Using Entity Framework Core :
   - Utilizes EF Core for database access and management.
   - SQL Server as the backend database.

     ### Using AutoMapper :
     - Seperates DTOS
    
  ### Unit of Work (UOW) and Repository Pattern:
  - Implements the UOW and Repository pattern using a generic class for efficient data access.
    
    - ### Api Interaction With
    - Postman
    - Swagger (provided with documentation and Bearer JWT In Action)
   
      ### ** Consume Api In MVC Project **
   
    # Villonova MVC
    
