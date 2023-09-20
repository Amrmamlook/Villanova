# Villanova 
is a web application built on a .NET 7 . It provides a set of functionalities using Web API, Entity Framework Core, and SQL Server for managing villas. 
The project includes authentication and authorization => using JWT (JSON Web Token) for different user roles (user and admin).
# Features 
 - ### User Management:
1. Users can register and log in using authentication with JWT.
1. Different user roles (user and admin) with corresponding authorization actions.
- ### Villa Controller:
1. CRUD operations (Create, Read, Update, Delete,Patch) for managing villa data.
1. Authorization checks based on user roles for each action.
- ### VillaNumber Controller :
  1. Similar CRUD operations for managing villa numbers.
  1. Authorization checks based on user roles for each action.
  - ### Entity Framework Core:
  1. Utilizes EF Core for database access and management.
 - ### Unit of Work (UOW) and Repository Pattern:
  - Implements the UOW and Repository pattern using a generic class for efficient data access.
    - ### Api Interaction With
    - Postman
    - Swagger (provide it with documentation and Beare In Action)
