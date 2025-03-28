# ASP.NET Todo List Example

This repository contains a simple ASP.NET application demonstrating basic API endpoints (`MapGet`, `MapPost`, and `MapDelete`). It is built following the official [Microsoft ASP.NET tutorial](https://learn.microsoft.com/aspnet/core/tutorials/min-web-api) on creating a minimal web API Todo List.

## Project Description

The project provides a basic understanding of:

- Creating minimal APIs using ASP.NET
- Handling HTTP requests:
  - `GET` (retrieve tasks)
  - `POST` (add new tasks)
  - `DELETE` (remove existing tasks)

This example is ideal for beginners who want to understand the fundamentals of ASP.NET Core and RESTful API operations.

## Technologies Used

- [.NET](https://dotnet.microsoft.com/)
- [ASP.NET Core](https://learn.microsoft.com/aspnet/core/)

## How to Run

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) installed on your machine.

### Running the application

Run the following command:

```bash
dotnet run
```

By default, the application will be accessible at:

```
http://localhost:5100
```

## API Endpoints

| Method | Endpoint        | Description                          |
|--------|-----------------|--------------------------------------|
| GET    | `/todos`        | Retrieve all todo items.             |
| GET    | `/todos/{id}`   | Retrieve a specific todo item by ID. |
| POST   | `/todos`        | Create a new todo item.              |
| DELETE | `/todos/{id}`   | Delete a specific todo item by ID.   |

## Resources

- [Official ASP.NET Minimal API Guide](https://learn.microsoft.com/aspnet/core/tutorials/min-web-api)
- [ASP.NET Core Documentation](https://learn.microsoft.com/aspnet/core/)

