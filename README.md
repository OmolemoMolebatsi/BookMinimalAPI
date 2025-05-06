# BookMinimalAPI
Book Manager API built with ASP.NET Core Minimal APIs and Entity Framework Core using a Code-First approach. It provides full CRUD functionality for managing books stored in a SQL database and is entirely implemented in Program.cs without controllers. 

# 📚 Quickfire API Creation – Book Manager with Minimal APIs

This project is a lightweight, professional-grade **Book Manager API** built with **ASP.NET Core Minimal APIs** and **Entity Framework Core** using a Code-First approach. It supports full CRUD operations for managing a collection of books stored in a SQL database.

---

## 🚀 Features

- RESTful API built with Minimal APIs (no controllers)
- Full CRUD (Create, Read, Update, Delete) support
- Clean architecture in a single `Program.cs` file
- SQL database integration using EF Core
- Data validation and error handling
- Swagger UI for interactive testing
- Seeded with dummy book data (10 books across genres)

---

## 🛠️ Technologies Used

- ASP.NET Core 8
- Entity Framework Core
- SQL Server / LocalDB / SQLite
- Swashbuckle (Swagger)
- .NET CLI & EF Core tools

---

## 🧩 Endpoints

| Method | Endpoint       | Description              |
|--------|----------------|--------------------------|
| GET    | /books         | Get all books            |
| GET    | /books/{id}    | Get book by ID           |
| POST   | /books         | Add a new book           |
| PUT    | /books/{id}    | Update an existing book  |
| DELETE | /books/{id}    | Delete a book by ID      |

---

## 📦 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/book-manager-api.git
   cd book-manager-api
  2. **Modify your connection string**
  ```appsettings.json
    "ConnectionStrings": {
  "DefaultConnection": "Your_Connection_String_Here"
}
```
3. **Run migrations**
```PowerShell
dotnet ef migrations add InitialCreate
dotnet ef database update"
```
